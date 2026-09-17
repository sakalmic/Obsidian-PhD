---
title: "Dataset Manifests Index"
type: moc
status: active
context: research
topics:
  - topic/ltsg/metrology
tags:
  - topic/ltsg/metrology
created: 2026-09-03
last_updated: "2026-09-14"
dg-publish: true
dg-render-dataview: true
---

# Dataset Manifests Index

Current historical record: [[Historical Measurements 2024-2025 - Provenance]]. Counts and the general delay trend remain [[Historical Counts and Delay Trend - Verification Pending|unverified]]. The new atmospheric predictive and TCO evidence is planned. [[P3 - Techno-economic operating choice]] requires traceable cost inputs as well as technical data; a provenance note does not promote a claim to supported.

```dataview
TABLE dataset_id, data_freeze, qc_state, storage_location, protocol_version, claims
FROM "II Areas/01_Research/Experiments/Dataset Manifests"
WHERE file.name != this.file.name AND row["dg-publish"] = true
SORT data_freeze DESC
```