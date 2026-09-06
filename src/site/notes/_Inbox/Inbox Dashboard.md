---
title: "Inbox Dashboard"
aliases:
  - Inbox
tags:
  - type/moc
  - context/phd
date: 2026-09-01
last_updated: 2026-09-01
dg-publish: false
---

# Inbox and Fleeting Notes

Quick ideas captured during reading, simulation, teaching, and discussion collect here. Process them weekly into permanent notes or projects, or remove them when they no longer add value.

```dataview
TABLE file.ctime as "Created", tags as "Tags"
FROM "_Inbox"
WHERE file.name != this.file.name
SORT file.ctime DESC
```
