---
title: "05_MOC: Grants & Funding"
aliases:
  - 05_MOC
  - Grants MOC
tags:
  - type/moc
  - context/grants
date: 2026-09-01
last_updated: 2026-09-06
dg-publish: false
dg-render-dataview: true
---

# 05 — Grants and Funding

This area manages the financial side of doctoral research: CTU student grants, national and international projects, and funding for conferences and research travel.

---

## Funding map

- [[SGS Grants Overview|CTU student grants and expenditure]]
- [[GAČR & External Projects|GAČR, TAČR, and other external projects]]
- [[Travel & Conference Funding|Travel and conference funding]]
- [[I Projects/04_Grants/Grant SGS 2026-2027|Active Grant SGS 2026-2027]]

---

## Active grant projects

```dataview
TABLE
    grant_provider as "Provider",
    grant_code as "Project code",
    submission_deadline as "Report or application deadline"
FROM "I Projects/04_Grants" OR "II Areas/05_Grants"
WHERE type = "grant" OR contains(tags, "type/grant")
SORT submission_deadline ASC
```
