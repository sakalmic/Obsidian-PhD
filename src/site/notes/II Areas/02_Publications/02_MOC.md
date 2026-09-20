---
{"dg-publish":true,"permalink":"/ii-areas/02-publications/02-moc/","title":"02_MOC: Publications & Conferences","tags":["type/moc","context/publications"],"dgHomeLink":true,"noteIcon":"","created":"2026-09-01","updated":"2026-09-14","dg-note-properties":{"title":"02_MOC: Publications & Conferences","aliases":["02_MOC","Publications MOC"],"tags":["type/moc","context/publications"],"date":"2026-09-01","last_updated":"2026-09-14"}}
---


# 02_MOC: Publications & Conferences

The broader application context is the transition toward SF₆-free and, where feasible, F-gas-free high-voltage switching. The selected dissertation remains **Tier 1: atmospheric-air metrology, stochastic prediction and bounded TCO**, with **submission targeted for August 2028**. Tier 1 studies laser-triggered closure of a laboratory gap; it does not test the insulation, short-circuit interruption, post-arc recovery or lifetime required to qualify complete switchgear. Any relevance to SF₆ substitution is therefore conditional on later validation for a defined switching function and duty. Tier 2 and Tier 3 are separately resourced follow-on research outside mandatory completion.

Working authority: [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026\|Doctoral Progress Review & Dissertation Plan (2024–2028)]], revised 14 September 2026. This records the candidate's planning choice; formal supervisor, committee and ISP/KOS approval remains separately evidenced.

Current evidence register: [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix\|Claim Ledger & Evidence Matrix]]; mandatory economics: [[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice\|P3 - Techno-economic operating choice]].

This map coordinates the doctoral publication pipeline, from early research concepts and conference papers to peer-reviewed Web of Science journal articles.

---

## Planning documents

- [[II Areas/02_Publications/Journal_Pipelines/Publication Strategy & Targets\|Publication strategy and target journals]]
- [[II Areas/02_Publications/Conferences/Conference Pipeline\|Conference pipeline and submission dates]]
- [[II Areas/02_Publications/Journal_Pipelines/Co-Authorship & Contribution Records\|Co-authorship and contribution records]]

---

## Manuscript pipeline

```dataview
TABLE WITHOUT ID
    file.link as "Manuscript",
    target_journal_conference as "Target venue",
    status as "Status",
    submission_deadline as "Submission deadline"
FROM "I Projects/01_Manuscripts" OR "II Areas/02_Publications"
WHERE (type = "manuscript" OR contains(tags, "type/paper")) AND row["dg-publish"] = true
SORT submission_deadline ASC
```

---

## Published and active outputs

- [[III Resources/03_Literature/LN - Sakala2025 - APL Lightning Protection|Sakala et al. (IEEE APL 2025)]] — DOI: `10.1109/APL65034.2025.11108944`
- [[LN - Mikes2024 - Laser Spark Gaps|Mikeš & Sakala (ICOLSE 2024)]]
- [[I Projects/01_Manuscripts/Paper - IEEE Transactions 2026|IEEE Transactions manuscript]] — in preparation
