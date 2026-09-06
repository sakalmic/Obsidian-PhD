---
title: "06_MOC: Administration & ISP"
aliases:
  - 06_MOC
  - Administration MOC
tags:
  - type/moc
  - context/admin
date: 2026-09-01
last_updated: 2026-09-06
dg-publish: false
dg-render-dataview: true
---

# 06 — Administration and ISP

This area covers the formal study requirements and doctoral administration at the Faculty of Electrical Engineering, Czech Technical University in Prague.

---

## Administration map

- [[Individual Study Plan (ISP)|Individual Study Plan and annual review]]
- [[Doctoral Study Regulations & Directives|Doctoral regulations and faculty directives]]
- [[Supervisor Meetings Log|Supervisor meeting records]]
- [[Credits & Exam Tracker|Course, credit, and examination tracker]]
- [[I Projects/03_Milestones/ISP & Milestone Tracking|ISP & Milestone Critical Path]]

---

## Recent supervisor meetings

```dataview
TABLE
    file.ctime as "Meeting date",
    attendees as "Attendees"
FROM "II Areas/06_Administration"
WHERE type = "meeting" OR contains(tags, "type/meeting")
SORT file.name DESC
LIMIT 5
```

---

## Upcoming administrative deadlines

- **September 2026:** Formal research discussion on the dissertation topic.
- **October 2026:** Complete the annual ISP review in KOS.
- **November 2026:** Submit the SGS application for 2027.
