---
title: "04_MOC: Teaching & Supervision"
aliases:
  - 04_MOC
  - Teaching MOC
tags:
  - type/moc
  - context/teaching
date: 2026-09-01
last_updated: 2026-09-06
dg-publish: false
dg-render-dataview: true
---

# 04 — Teaching and Supervision

This area manages teaching duties at CTU FEE, including laboratory and seminar instruction, student consultations, and supervision of bachelor’s and master’s theses.

---

## Teaching map

- [[Teaching Responsibilities & Courses|Teaching responsibilities and courses]]
- [[Supervised Theses (BP & DP)|Supervised and consulted student theses]]
- [[Teaching & Labs Support|Teaching and laboratory support project]]

---

## Active courses and tasks

```dataview
TABLE
    course_code as "Course code",
    semester as "Semester",
    role as "Role"
FROM "II Areas/04_Teaching"
WHERE type = "teaching" OR contains(tags, "type/teaching")
SORT semester DESC
```
