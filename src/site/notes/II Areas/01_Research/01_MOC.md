---
{"dg-publish":true,"permalink":"/ii-areas/01-research/01-moc/","title":"01_MOC: Research & Methodology","tags":["type/moc","context/research"],"dgHomeLink":true,"noteIcon":"","created":"2026-09-01","updated":"2026-09-14","dg-note-properties":{"title":"01_MOC: Research & Methodology","aliases":["01_MOC","Research MOC"],"tags":["type/moc","context/research"],"type":"moc","status":"active","context":"research","topics":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/model"],"date":"2026-09-01","last_updated":"2026-09-14"}}
---


# 01_MOC: Research & Methodology

The long-term goal of the research programme is to contribute to technically and economically viable high-voltage equipment without SF₆. The selected dissertation is **Tier 1: atmospheric-air metrology, stochastic prediction and mandatory bounded TCO**, with **submission targeted for August 2028**. Tier 2 (CO₂/pressure transfer) and Tier 3 (applications) are separately resourced follow-on research, outside mandatory completion and its publication requirements. Full replacement of SF₆ is the programme's direction, not a demonstrated result or a dissertation completion condition.

Working authority: [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026\|Doctoral Progress Review & Dissertation Plan (2024–2028)]], revised 14 September 2026. This records the candidate's planning choice; formal supervisor, committee and ISP/KOS approval remains separately evidenced.

Current evidence register: [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix\|Claim Ledger & Evidence Matrix]]; mandatory economics: [[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice\|P3 - Techno-economic operating choice]].

This map brings together the scientific and experimental foundations of the doctoral research across three primary branches: **Concepts**, **Experiments**, and **Simulations**.

---

## 1. Concepts (Theoretical Foundations & Zettelkasten)

Core physical theory, analytical scaling laws, and atomic conceptual notes:

- [[II Areas/01_Research/Concepts/Laser-Induced Plasma Dynamics\|Physical dynamics of laser-induced plasma]]
- [[II Areas/01_Research/Concepts/Laser-Triggered Spark Gaps (LTSG)\|Laser-triggered spark gaps and switching mechanisms]]
- [[II Areas/01_Research/Concepts/Theory - Laser-Triggered Breakdown and Switching\|Theory, scaling laws and modelling assumptions]]
- [[II Areas/01_Research/Concepts/Diagnostics - Timing EMP and Radiation\|Timing, EMP and ionising-radiation diagnostics]]
- [[II Areas/01_Research/Concepts/Statistics - Breakdown Probability Delay and Jitter\|Breakdown probability, censoring and jitter statistics]]
- [[II Areas/01_Research/Concepts/High-Voltage Arc Quenching & Protection\|High-voltage arc quenching and grid protection]]
- [[II Areas/01_Research/Concepts/Techno-Economic Modeling of Grid Switching\|Mandatory atmospheric TCO and follow-on grid economics]]
- [[II Areas/01_Research/Concepts/Zettelkasten Index\|Atomic Permanent Notes Index (Concepts)]]

```dataview
LIST
FROM "II Areas/01_Research/Concepts"
WHERE (type = "concept" OR contains(tags, "type/permanent")) AND row["dg-publish"] = true
SORT file.name ASC
```

---

## 2. Experiments (Laboratories, Diagnostics & Evidence)

Measurement campaigns, raw diagnostic logs, calibration records, and quality manifests:

- [[II Areas/01_Research/Experiments/Experiments Index|Experiments Index]]
- [[II Areas/01_Research/Experiments/HiLASE Research Hub|HiLASE research hub]]
- [[II Areas/01_Research/Experiments/HiLASE LIDT Laboratory|HiLASE LIDT laboratory and PERLA context]]
- [[II Areas/01_Research/Experiments/Experimental Measurements Archive|Experimental Measurements Archive (HiLASE / CTU)]]
- [[II Areas/01_Research/Experiments/Evidence Index|Evidence & Traceability Index]]
- [[II Areas/01_Research/Experiments/Calibrations/Calibrations Index|Calibrations Index]]
- [[II Areas/01_Research/Experiments/Calibrations/HiLASE Trigger-to-Optical Timing - Verification Plan|Trigger-to-optical timing verification]]
- [[II Areas/01_Research/Experiments/Analysis Records/Analysis Records Index|Analysis Records Index]]
- [[II Areas/01_Research/Experiments/Dataset Manifests/Dataset Manifests Index|Dataset Manifests Index]]

---

## 3. Simulations (COMSOL Multiphysics & Numerical Models)

Finite-element numerical modelling, plasma kinetics, fluid dynamics, and solver configurations:

- [[II Areas/01_Research/Simulations/Simulations Index|Simulations Index]]
- [[II Areas/01_Research/Simulations/COMSOL Multiphysics Setups|COMSOL Multiphysics Setups]]
- [[II Areas/01_Research/Simulations/Simulation Datasets & Models|Simulation Datasets & Models Catalog]]

---

## 4. Apparatus & Laboratory Safety

Experimental rig configuration, optical beamline specifications, and high-voltage / laser safety protocols:

- [[II Areas/01_Research/Apparatus_and_Safety/LTSG Apparatus & Laboratory Safety|LTSG Apparatus & Laboratory Safety Protocols]]

---

## Executable Research Plan & Outputs

- [[I Projects/03_Milestones/20260925 Minimum/Minimum Dissertation Study & Research Discussion 2026|Immediate three-week topic-freeze and minimum project]]
- [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028|Core research package and 2026-2028 schedule]]
- [[Experimental Diagnostics Campaign|Experimental campaign task board]]
- [[II Areas/01_Research/Concepts/Research Extensions Roadmap|Staged extensions and activation gates]]
- [[I Projects/01_Manuscripts/Paper - IEEE Transactions 2026|IEEE Transactions manuscript]]
- [[I Projects/01_Manuscripts/Dissertation Manuscript|Dissertation manuscript]]
- [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix|Claim ledger and evidence matrix]]

---

## Key Literature

```dataview
TABLE WITHOUT ID
    file.link as "Literature note",
    authors as "Authors",
    year as "Year",
    journal_conference as "Journal / conference"
FROM "III Resources/03_Literature"
WHERE (type = "literature" OR contains(tags, "type/literature")) AND row["dg-publish"] = true
SORT year DESC
```
