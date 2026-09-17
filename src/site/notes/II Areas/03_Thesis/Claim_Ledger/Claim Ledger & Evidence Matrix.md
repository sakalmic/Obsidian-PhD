---
title: "Claim Ledger & Evidence Matrix"
aliases:
  - Claim Ledger
  - Evidence Matrix
type: moc
status: active
context: thesis
topics:
  - topic/ltsg/breakdown
  - topic/ltsg/statistics
  - topic/ltsg/model
tags:
  - topic/ltsg/breakdown
  - topic/ltsg/statistics
  - topic/ltsg/model
date: 2026-09-01
last_updated: "2026-09-14"
dg-publish: true
dg-home-link: true
dg-render-dataview: true
---

# Claim Ledger & Evidence Matrix

The long-term goal of the research programme is to contribute to technically and economically viable high-voltage equipment without SF₆. The selected dissertation is **Tier 1: atmospheric-air metrology, stochastic prediction and mandatory bounded TCO**, with **submission targeted for August 2028**. Tier 2 (CO₂/pressure transfer) and Tier 3 (applications) are separately resourced follow-on research, outside mandatory completion and its publication requirements. Full replacement of SF₆ is the programme's direction, not a demonstrated result or a dissertation completion condition.

Working authority: [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026|Doctoral Progress Review & Dissertation Plan (2024–2028)]], revised 14 September 2026. This records the candidate's planning choice; formal supervisor, committee and ISP/KOS approval remains separately evidenced.

This is the dashboard for all scientific claims permitted in the dissertation. The stable H/P identifiers are now represented by atomic notes so that datasets, analyses, manuscripts and chapters can link to them through properties.

## Document authority

Use [[II Areas/03_Thesis/LaTeX_Thesis/Doctoral Document Map]] for the document hierarchy. The reviewer report governs current scope; stable atomic H1–H4 and P1–P3 define the tests. C1–C4 are Tier 1 contribution groups in expected completion order. C5 and C6 are separately resourced Tier 2 contributions. RQ identifies a question, H a testable hypothesis, and P a research proposition.

## Contribution architecture

| Contribution | Evidence and role |
| --- | --- |
| C1 | Reproducible atmospheric operating domain; probability and calibrated timing; H1, P1 and supporting P2 |
| C2 | Independent comparison of M0 and channel-informed M1; H2 and H4 |
| C3 | Mandatory bounded TCO and technically feasible operating choice; P3 |
| C4 | Traceable data, calibrations, analysis, uncertainty and reproducibility across all claims |

H3 is supporting robustness within the frozen atmospheric configuration family. C5 and C6 belong only to follow-on Tier 2. A null result must be accompanied by adequate sensitivity and a quantitative limit; it does not automatically guarantee degree sufficiency.

## Claim dashboard

```dataview
TABLE WITHOUT ID
    file.link AS "Claim",
    contribution AS "Contribution",
    claim_role AS "Role",
    status AS "State",
    work_packages AS "WP",
    datasets AS "Datasets",
    manuscripts AS "Output"
FROM "II Areas/03_Thesis/Claims"
WHERE row["dg-publish"] = true
SORT statement_id ASC
```
## Evidence linked to claims

```dataview
TABLE WITHOUT ID
    file.link AS "Evidence",
    type AS "Type",
    evidence_state AS "Evidence state",
    claims AS "Claims",
    dataset_id AS "Dataset",
    last_updated AS "Updated"
FROM "II Areas/01_Research/Experiments"
WHERE length(claims) > 0 AND row["dg-publish"] = true
SORT last_updated DESC
```
## Evidence-state vocabulary

| State | Meaning |
| --- | --- |
| `planned` | No frozen protocol or primary evidence yet |
| `protocol-frozen` | Outcomes, contrasts, exclusions and stopping rules fixed |
| `collected` | Raw data and manifest exist, QC not complete |
| `qc-passed` | Integrity and measurement checks passed |
| `analysed` | Predeclared analysis executed on a frozen dataset |
| `replicated` | Main result repeated independently |
| `published` | Traceable result accepted or published |

## Rules for deciding claims

1. Define the smallest practically relevant effect or prediction tolerance before confirmatory analysis.
2. Preserve failed shots and negative findings.
3. Distinguish source timing, diagnostic uncertainty and discharge variability.
4. Do not use statistical significance as the sole acceptance criterion.
5. A claim is not supported until it has QC-passed primary evidence, uncertainty and an independent repeat.
6. If evidence cannot support the positive claim, record a quantitative bound and use `falsified-bounded`.
7. Every result figure must identify its dataset freeze and analysis version.

## Required evidence route

```mermaid
flowchart LR
    C[Atomic H/P note] --> P[Frozen protocol]
    P --> E[Experiment or simulation]
    E --> D[Dataset manifest]
    D --> Q[QC record]
    Q --> A[Analysis record]
    A --> R[Independent repeat]
    R --> M[Manuscript and chapter]
```

## Core-to-output matrix

| Claim | WP | Evidence | Output | Chapter |
| --- | --- | --- | --- | --- |
| H1 | WP1, WP3, WP4 | Atmospheric probability and independent repeat | Paper 1 | 4 |
| P1 | WP0, WP3, WP4 | Calibrated delay distributions without assumed monotonicity | Paper 1 | 4 |
| H2 | WP2–WP5 | Independent M0/M1 comparison | Paper 2 | 5 |
| H3 | WP1, WP4 if activated | Supporting geometry/polarity robustness | Supporting only | 4 |
| H4 | WP5 | Reduced prediction with held-out validation | Paper 2 | 5 |
| P2 | WP0, WP2, WP4 | Observable optical/electrical timing and limits | Supporting Paper 1 | 4 |
| P3 | Cost collection from WP0; WP6 synthesis | Feasible operating choice, TCO and uncertainty | Paper 2 | 6 |

C4 spans all rows. Planned evidence is not a completed result.

## Extension claims — inactive by default

| ID | Extension | Activation gate | Status |
| --- | --- | --- | --- |
| **EX-EMP-01** | EMP difference beyond stored energy and timing | Stable core + calibrated RF chain + pickup controls | Planned |
| **EX-RAD-01** | Photon/electron emission probability or spatial distribution | Radiation approval + passive survey + EMP controls | Planned |
| **EX-RAD-02** | Neutron component under specified configuration | Plausible mechanism + multi-response calibration + approval | Planned |
| **EX-APP-01** | System-level advantage in a named pulsed-power demonstrator | Core reliability, recovery and lifetime data | Planned |
| **EX-ECO-01** | System-level reliability/cost envelope beyond the mandatory laboratory TCO | Demonstrator evidence + defensible cost distributions | Planned |

All extension rows are outside mandatory completion. They cannot replace C3 or impose a dependency on August 2028 submission.

## Literature constraints

| Evidence | Supports | Does not establish on this apparatus |
| --- | --- | --- |
| Luther et al. 2001, [doi:10.1063/1.1419036](https://doi.org/10.1063/1.1419036) | Very low jitter is possible in an optimised small pressurised gap | Performance of the present atmospheric system |
| Arantchouk et al. 2013, [doi:10.1063/1.4802927](https://doi.org/10.1063/1.4802927) | Filament triggering can achieve high-current, low-jitter switching | Transfer to the present geometry and laser regime |
| Rosenthal et al. 2020, [doi:10.1364/OE.398836](https://doi.org/10.1364/OE.398836) | Heating and density-channel evolution can be central | Dominance under the present pulse duration and timing |
| [[III Resources/03_Literature/LN - Cikhardt2026 - Electromagnetic and Particle Pulses]] | EMP measurement and source-attribution discipline | Atmospheric LTSG EMP amplitude or particle yield |
| [[III Resources/03_Literature/LN - Stepanova2026 - Ionising Radiation from Impulse Generators]] | Passive diagnostics, spatial mapping and background controls | Radiation presence or mechanism in laser-triggered shots |

## Integrity note

Earlier unsupported values concerning delay reduction, model agreement, wear reduction and economic payback remain excluded. A numerical claim can be reintroduced only with a dataset identifier, analysis version, uncertainty and verification state.

## Stable compatibility anchors

These headings preserve existing block links. The atomic claim note is authoritative.

### H1

See [[II Areas/03_Thesis/Claims/H1 - Laser-assisted breakdown probability]].

### P1

See [[II Areas/03_Thesis/Claims/P1 - Delay and jitter response]].

### H2

See [[II Areas/03_Thesis/Claims/H2 - Channel state versus pulse energy]].

### H3

See [[II Areas/03_Thesis/Claims/H3 - Polarity and field geometry]].

### H4

See [[II Areas/03_Thesis/Claims/H4 - Reduced predictive model]].

### P2

See [[II Areas/03_Thesis/Claims/P2 - Reproducible optical and electrical stages]].

### EX-EMP-01

Inactive EMP extension; activate only after the calibrated-RF-chain gate.

### EX-RAD-01

Inactive photon/electron radiation extension; begin with an approved passive survey.

### EX-RAD-02

Inactive neutron extension requiring mechanism, multi-response calibration and approval.

### EX-APP-01

Inactive named pulsed-power demonstrator extension.

### EX-ECO-01

Inactive system-level economic extension. Mandatory laboratory TCO is P3/C3 and does not depend on EX-APP-01 or EX-ECO-01.

## Operating review

Review this ledger weekly during acquisition and at every supervisor meeting. Each atomic H/P note is the authoritative statement; this dashboard shows relationships and current scope.

## Related notes

- [[I Projects/03_Milestones/20260925 Minimum/Minimum Dissertation Study & Research Discussion 2026]]
- [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028]]
- [[II Areas/03_Thesis/LaTeX_Thesis/Thesis Structure & Chapter Outline]]
- [[_System/Research Methodology & Workflows]]
- [[I Projects/01_Manuscripts/Paper - IEEE Transactions 2026]]

## P3

[[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice]] — mandatory C3; Chapter 6 and Paper 2. State: proposition with planned evidence; no operating optimum has yet been established.
