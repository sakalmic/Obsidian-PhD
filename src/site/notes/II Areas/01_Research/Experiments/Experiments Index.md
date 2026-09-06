---
title: "Experiments Index"
type: moc
status: active
context: research
topics:
  - topic/ltsg/breakdown
  - topic/ltsg/metrology
tags:
  - topic/ltsg/breakdown
  - topic/ltsg/metrology
created: 2026-09-03
last_updated: 2026-09-03
dg-publish: true
---

# Experiments Index

```dataview
TABLE experiment_id, date_performed, work_package, protocol_version, evidence_state, dataset_id, claims
FROM "II Areas/01_Research/Experiments"
WHERE file.name != this.file.name
SORT date_performed DESC
```

