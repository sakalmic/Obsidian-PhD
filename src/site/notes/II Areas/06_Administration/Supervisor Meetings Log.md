---
title: "Supervisor Meetings Log"
aliases:
  - Supervisor Meetings Log
  - Supervisor Meetings
tags:
  - type/admin
  - context/admin
  - status/in-progress
date: 2026-09-01
last_updated: 2026-09-01
dg-publish: false
---

# Supervisor Meetings Log

Index of meeting records with **doc. Ing. Jan Mikeš, Ph.D.**

```dataview
TABLE
    file.ctime as "Meeting date",
    tags as "Category"
FROM "II Areas/04_Administration"
WHERE type = "meeting" OR contains(tags, "type/meeting")
SORT file.name DESC
```

---

## Example meeting record

- [[Meeting - 2026-09-01 Supervisor Sync|1 September 2026 — start of WS 2026/2027 and preparation for the research discussion]]
