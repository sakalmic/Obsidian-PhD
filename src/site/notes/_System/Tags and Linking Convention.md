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

<div class="block-language-dataview"><table><thead><tr><th>File</th><th>type</th><th>evidence_state</th><th>dataset_id</th><th>last_updated</th></tr></thead><tbody><tr><td colspan="5">No matching published records.</td></tr></tbody></table></div>
Upcoming projects:

<div class="block-language-dataview"><table><thead><tr><th>File</th><th>priority</th><th>due</th><th>status</th></tr></thead><tbody><tr><td><a class="internal-link" href="/i-projects/01-manuscripts/dissertation-manuscript/">Dissertation Manuscript</a></td><td>high</td><td>2028-08-31</td><td>active</td></tr><tr><td><a class="internal-link" href="/i-projects/01-manuscripts/paper-ieee-transactions-2026/">Paper 1 - Channel-State-Dependent Laser Triggering</a></td><td>high</td><td>2027-11-30</td><td>active</td></tr></tbody></table></div>