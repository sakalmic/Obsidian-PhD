---
title: "Calibrations Index"
type: moc
status: active
context: research
topics:
  - topic/ltsg/metrology
tags:
  - topic/ltsg/metrology
created: 2026-09-03
last_updated: 2026-09-03
dg-publish: true
dg-render-dataview: true
---

# Calibrations Index

Open timing verification: [[II Areas/01_Research/Experiments/Calibrations/HiLASE Trigger-to-Optical Timing - Verification Plan|HiLASE Trigger-to-Optical Timing - Verification Plan]]. No apparatus-specific trigger-to-optical correction is accepted until a configuration-matched record and uncertainty are confirmed.

```dataview
TABLE calibration_id, instrument_id, valid_from, valid_until, status, claims
FROM "II Areas/01_Research/Experiments/Calibrations"
WHERE file.name != this.file.name AND row["dg-publish"] = true
SORT valid_until ASC
```
