---
title: "Analysis Records Index"
type: moc
status: active
context: research
topics:
  - topic/ltsg/statistics
  - topic/ltsg/model
tags:
  - topic/ltsg/statistics
  - topic/ltsg/model
created: 2026-09-03
last_updated: "2026-09-14"
dg-publish: true
dg-render-dataview: true
---

# Analysis Records Index

Current historical record: [[II Areas/01_Research/Experiments/Dataset Manifests/Historical Measurements 2024-2025 - Provenance]]. Counts and the general delay trend remain [[II Areas/01_Research/Experiments/Analysis Records/Historical Counts and Delay Trend - Verification Pending|unverified]]. The new atmospheric predictive and TCO evidence is planned. [[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice]] requires traceable cost inputs as well as technical data; a provenance note does not promote a claim to supported.

```dataview
TABLE analysis_id, dataset_id, analysis_role, code_commit, status, claims
FROM "II Areas/01_Research/Experiments/Analysis Records"
WHERE file.name != this.file.name AND row["dg-publish"] = true
SORT last_updated DESC
```