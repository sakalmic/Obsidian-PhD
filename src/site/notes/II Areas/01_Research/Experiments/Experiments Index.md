---
{"dg-publish":true,"permalink":"/ii-areas/01-research/experiments/experiments-index/","title":"Experiments Index","tags":["topic/ltsg/breakdown","topic/ltsg/metrology"],"noteIcon":"","updated":"2026-09-03","dg-note-properties":{"title":"Experiments Index","type":"moc","status":"active","context":"research","topics":["topic/ltsg/breakdown","topic/ltsg/metrology"],"tags":["topic/ltsg/breakdown","topic/ltsg/metrology"],"created":"2026-09-03","last_updated":"2026-09-03"}}
---


# Experiments Index

```dataview
TABLE experiment_id, date_performed, work_package, protocol_version, evidence_state, dataset_id, claims
FROM "II Areas/01_Research/Experiments"
WHERE file.name != this.file.name
SORT date_performed DESC
```

