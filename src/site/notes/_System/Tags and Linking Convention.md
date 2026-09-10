---
{"dg-publish":true,"permalink":"/system/tags-and-linking-convention/","title":"Properties, Tags and Linking Convention","tags":["topic/system/metadata"],"dgHomeLink":true,"noteIcon":"","created":"2026-09-01","updated":"2026-09-03","dg-note-properties":{"title":"Properties, Tags and Linking Convention","aliases":["Tags and Linking Convention","Tagging Rules"],"type":"guide","status":"evergreen","context":"phd","topics":["topic/system/metadata"],"tags":["topic/system/metadata"],"date":"2026-09-01","last_updated":"2026-09-03"}}
---


# Properties, Tags and Linking Convention

The vault uses **properties for workflow state and relationships** and **tags only for topical discovery**. This prevents the same fact from being represented simultaneously by a folder, a tag and a duplicated text field.

## Required properties by note type

### Common properties

```yaml
type: experiment
status: active
context: research
project: LTSG-Core
work_package: WP3
claims:
  - CL-01
  - CL-03
topics:
  - topic/ltsg/breakdown
  - topic/ltsg/channel
tags:
  - topic/ltsg/breakdown
  - topic/ltsg/channel
created: 2026-09-03
last_updated: 2026-09-03
```

`topics` is the queryable property. The identical topical values may also remain in `tags` for native Obsidian tag navigation and Digital Garden compatibility.

### Projects and manuscripts

- `project_id`
- `type: project` or `type: manuscript`
- `status`
- `priority`
- `due`
- `definition_of_done`
- `parent_project` where applicable

### Protocols, experiments and calibrations

- `protocol_id` and `protocol_version`
- `experiment_id` or `calibration_id`
- `project`
- `work_package`
- `claims`
- `evidence_state`
- `dataset_id`
- `operator`
- `date_performed`

### Datasets and analyses

- `dataset_id`
- `storage_location`
- `checksum` or immutable version identifier
- `protocol_version`
- `qc_state`
- `analysis_id`
- `code_commit`
- `data_freeze`
- `claims`

### Claims

- `claim_id`
- `contribution`
- `claim_role: primary` or `supporting`
- `status: hypothesis`, `in-progress`, `supported`, `falsified-bounded`
- `work_packages`
- `datasets`
- `analyses`
- `manuscripts`
- `chapters`

## Controlled vocabularies

### Type

`moc` · `guide` · `project` · `roadmap` · `synthesis` · `method` · `literature` · `concept` · `protocol` · `calibration` · `experiment` · `simulation` · `dataset` · `analysis` · `claim` · `manuscript` · `chapter` · `meeting` · `daily` · `administration` · `teaching` · `grant`

### General status

`inbox` · `idea` · `planned` · `active` · `blocked` · `review` · `submitted` · `revision` · `complete` · `archived` · `evergreen`

### Evidence state

`planned` → `protocol-frozen` → `collected` → `qc-passed` → `analysed` → `replicated` → `published`

An unsuccessful or negative experiment can still reach `analysed`. Evidence state describes processing maturity, not whether the hypothesis was confirmed.

## Canonical topical taxonomy

- `topic/ltsg/breakdown`
- `topic/ltsg/channel`
- `topic/ltsg/timing`
- `topic/ltsg/metrology`
- `topic/ltsg/statistics`
- `topic/ltsg/model`
- `topic/ltsg/emp`
- `topic/ltsg/radiation`
- `topic/ltsg/application`
- `topic/ltsg/economics`
- `topic/system/vault`
- `topic/system/metadata`
- `topic/system/workflow`

Use the narrowest useful topical tag. Do not create synonyms such as both `theme/comsol-simulation` and `theme/methods/comsol-multiphysics`.

## Legacy tag mapping

| Legacy tag | Canonical topic |
| --- | --- |
| `theme/laser-triggering`, `theme/engineering/ltsg` | `topic/ltsg/breakdown` |
| `theme/plasma-dynamics`, `theme/physics/plasma-dynamics` | `topic/ltsg/channel` |
| `theme/optical-diagnostics`, `theme/methods/diagnostics` | `topic/ltsg/metrology` |
| `theme/comsol-simulation`, `theme/methods/comsol-multiphysics` | `topic/ltsg/model` |
| `theme/methods/statistics` | `topic/ltsg/statistics` |
| `theme/emp` | `topic/ltsg/emp` |
| `theme/radiation` | `topic/ltsg/radiation` |
| `theme/techno-economics` | `topic/ltsg/economics` |
| `theme/engineering/power-grid`, `theme/arc-quenching` | `topic/ltsg/application` |

## Linking rules

1. Every evidence note links upward through properties: project → WP → CL.
2. Literature notes link to the concepts and claims they constrain, not merely to a generic MOC.
3. Claim IDs are permanent and never reused. Link to the atomic note, for example `[[CL-03 - Channel state versus pulse energy]]`.
4. Public notes link only to public notes. Private evidence may be referenced in public prose by a non-sensitive identifier without exposing its path.
5. Use descriptive labels in prose and aliases for common abbreviations.
6. Template placeholder links must be replaced before a note leaves the inbox.

## Dataview examples

Active evidence for CL-03:

| File | type | evidence_state | dataset_id | last_updated |
| ---- | ---- | -------------- | ---------- | ------------ |

{ .block-language-dataview}
Upcoming projects:

| File                                                                                                                                                                                                      | priority | due                | status                      |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ------------------ | --------------------------- |
| [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026\|Doctoral Progress Review and Research Plan for Professional Discussion 2026]] | critical | \-                 | draft-for-supervisor-review |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction A - Reliability and Robust Operating Window\|Direction A - Reliability and Robust Operating Window]]                           | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction B - Channel State and Prediction of Switching\|Direction B - Channel State and Prediction of Switching]]                       | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction C - Adaptive Control and Operational Utility\|Direction C - Adaptive Control and Operational Utility]]                         | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction D - Spatial Shaping of the Laser-Created Channel\|Direction D - Spatial Shaping of the Laser-Created Channel]]                 | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction E - Synchronization of Two Spark Gaps\|Direction E - Synchronization of Two Spark Gaps]]                                       | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction F - Dielectric Recovery and Component Wear\|Direction F - Dielectric Recovery and Component Wear]]                             | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O1 - SF6-Free Diagnostics\|Direction O1 - SF6-Free Diagnostics]]                                                               | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O2 - Fluorine-Free Media\|Direction O2 - Fluorine-Free Media]]                                                                 | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O3 - Switchgear Digital Twin\|Direction O3 - Switchgear Digital Twin]]                                                         | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O4 - Hybrid Crowbar\|Direction O4 - Hybrid Crowbar]]                                                                           | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O5 - Multi-Gap Synchronisation\|Direction O5 - Multi-Gap Synchronisation]]                                                     | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O6 - Lightning Attachment\|Direction O6 - Lightning Attachment]]                                                               | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O7 - Luminous Plasma Structures\|Direction O7 - Luminous Plasma Structures]]                                                   | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Direction Tickets/Direction O8 - Hydrogen-Ammonia Ignition\|Direction O8 - Hydrogen-Ammonia Ignition]]                                                     | high     | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Dissertation Direction Portfolio and Winning Variant W 2026-2029\|Dissertation Direction Portfolio and Winning Variant W 2026-2029]]                       | \-       | \-                 | proposal                    |
| [[I Projects/03_Milestones/20260925 Minimum/Minimum Dissertation Study & Research Discussion 2026\|Minimum Dissertation Study & Research Discussion 2026]]                                             | critical | September 24, 2026 | active                      |
| [[I Projects/01_Manuscripts/Paper - IEEE Transactions 2026\|Paper - IEEE Transactions 2026]]                                                                                                           | high     | November 30, 2027  | active                      |
| [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028\|LTSG Core Research Package 2026-2028]]                                                                                                 | critical | April 30, 2028     | active                      |
| [[I Projects/01_Manuscripts/Dissertation Manuscript\|Dissertation Manuscript]]                                                                                                                         | high     | August 31, 2028    | active                      |

{ .block-language-dataview}