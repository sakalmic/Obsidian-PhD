---
title: "Methods Index"
aliases:
  - Research Methods
type: moc
status: evergreen
context: research
topics:
  - topic/ltsg/metrology
  - topic/ltsg/statistics
tags:
  - topic/ltsg/metrology
  - topic/ltsg/statistics
created: 2026-09-03
last_updated: 2026-09-03
dg-publish: false
---

# Methods Index

Reusable protocols, operating procedures and statistical methods. A protocol describes **how work must be performed**; a project note describes **when and why it will be performed**.

```dataview
TABLE WITHOUT ID file.link AS "Method", type AS "Type", protocol_version AS "Version", status AS "Status", last_updated AS "Updated"
FROM "III Resources/Methods"
WHERE file.name != this.file.name
SORT file.name ASC
```

## Required first methods

- [ ] LTSG metrology and timing protocol
- [ ] Self-breakdown $U_{50}$ protocol
- [ ] Laser/channel calibration protocol
- [ ] Confirmatory statistical analysis plan
- [ ] Electrode conditioning and service SOP

## Related notes

- [[Research Methodology & Workflows]]
- [[LTSG Core Research Package 2026-2028]]

