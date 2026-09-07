---
{"dg-publish":true,"permalink":"/ii-areas/02-publications/02-moc/","title":"02_MOC: Publications & Conferences","tags":["type/moc","context/publications"],"dgHomeLink":true,"noteIcon":"","created":"2026-09-01","updated":"2026-09-06","dg-note-properties":{"title":"02_MOC: Publications & Conferences","aliases":["02_MOC","Publications MOC"],"tags":["type/moc","context/publications"],"date":"2026-09-01","last_updated":"2026-09-06"}}
---


# 02_MOC: Publications & Conferences

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
WHERE (type = "manuscript" OR contains(tags, "type/paper")) AND dg-publish = true
SORT submission_deadline ASC
```

---

## Published and active outputs

- [[III Resources/03_Literature/LN - Sakala2025 - APL Lightning Protection\|Sakala et al. (IEEE APL 2025)]] — DOI: `10.1109/APL65034.2025.11108944`
- [[III Resources/03_Literature/LN - Mikes2024 - Laser Spark Gaps\|Mikeš & Sakala (ICOLSE 2024)]]
- [[I Projects/01_Manuscripts/Paper - IEEE Transactions 2026\|IEEE Transactions manuscript]] — in preparation
