---
{"dg-publish":true,"permalink":"/ii-areas/01-research/experiments/calibrations/calibrations-index/","title":"Calibrations Index","tags":["topic/ltsg/metrology"],"noteIcon":"","updated":"2026-09-03","dg-note-properties":{"title":"Calibrations Index","type":"moc","status":"active","context":"research","topics":["topic/ltsg/metrology"],"tags":["topic/ltsg/metrology"],"created":"2026-09-03","last_updated":"2026-09-03"}}
---


# Calibrations Index

```dataview
TABLE calibration_id, instrument_id, valid_from, valid_until, status, claims
FROM "II Areas/01_Research/Experiments/Calibrations"
WHERE file.name != this.file.name
SORT valid_until ASC
```

