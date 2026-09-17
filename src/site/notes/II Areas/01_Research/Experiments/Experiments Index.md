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
last_updated: "2026-09-14"
dg-publish: true
dg-render-dataview: true
---

# Experiments Index

Laboratory and evidence navigation: [[II Areas/01_Research/Experiments/HiLASE Research Hub]]. The related [[II Areas/01_Research/Experiments/HiLASE LIDT Laboratory]] provides a documented PERLA/LIDT connection, not an automatic timing calibration for the high-voltage gap.

Current historical record: [[II Areas/01_Research/Experiments/Dataset Manifests/Historical Measurements 2024-2025 - Provenance]]. Counts and the general delay trend remain [[II Areas/01_Research/Experiments/Analysis Records/Historical Counts and Delay Trend - Verification Pending|unverified]]. The new atmospheric predictive and TCO evidence is planned. [[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice]] requires traceable cost inputs as well as technical data; a provenance note does not promote a claim to supported.

```dataview
TABLE experiment_id, date_performed, work_package, protocol_version, evidence_state, dataset_id, claims
FROM "II Areas/01_Research/Experiments"
WHERE file.name != this.file.name AND row["dg-publish"] = true
SORT date_performed DESC
```
