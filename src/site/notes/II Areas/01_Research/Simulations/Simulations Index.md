---
{"dg-publish":true,"permalink":"/ii-areas/01-research/simulations/simulations-index/","title":"Simulations Index","tags":["topic/ltsg/model"],"noteIcon":"","updated":"2026-09-03","dg-note-properties":{"title":"Simulations Index","type":"moc","status":"active","context":"research","topics":["topic/ltsg/model"],"tags":["topic/ltsg/model"],"created":"2026-09-03","last_updated":"2026-09-03"}}
---


# Simulations Index

```dataview
TABLE simulation_id, model_version, calibration_dataset, validation_dataset, evidence_state, claims
FROM "II Areas/01_Research/Simulations"
WHERE file.name != this.file.name
SORT last_updated DESC
```

