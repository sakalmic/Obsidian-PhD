---
title: "Archives Index"
aliases:
  - Archives Index
tags:
  - type/moc
  - context/phd
date: 2026-09-01
last_updated: 2026-09-01
dg-publish: false
---

# Archived Projects and Closed Work

Completed projects, superseded applications, and closed grant reports are retained here.

```dataview
TABLE file.ctime as "Created", tags as "Tags"
FROM "IV Archives"
WHERE file.name != this.file.name
SORT file.name ASC
```
