---
{"dg-publish":true,"permalink":"/ii-areas/01-research/experiments/evidence-index/","title":"Evidence Index","tags":["topic/ltsg/metrology"],"noteIcon":"","updated":"2026-09-14","dg-note-properties":{"title":"Evidence Index","aliases":["Research Evidence Dashboard"],"type":"moc","status":"active","context":"research","topics":["topic/ltsg/metrology"],"tags":["topic/ltsg/metrology"],"created":"2026-09-03","last_updated":"2026-09-14"}}
---


# Evidence Index

Current historical record: [[II Areas/01_Research/Experiments/Dataset Manifests/Historical Measurements 2024-2025 - Provenance\|Historical Measurements 2024-2025 - Provenance]]. Counts and the general delay trend remain [[II Areas/01_Research/Experiments/Analysis Records/Historical Counts and Delay Trend - Verification Pending\|unverified]]. The new atmospheric predictive and TCO evidence is planned. [[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice\|P3 - Techno-economic operating choice]] requires traceable cost inputs as well as technical data; a provenance note does not promote a claim to supported.

This area contains metadata and interpretive records, not bulk raw data. Every evidence chain should resolve as:

`protocol → calibration → experiment/simulation → dataset manifest → QC/analysis record → CL → manuscript/chapter`.

## Evidence requiring attention

```dataview
TABLE WITHOUT ID file.link AS "Record", type AS "Type", evidence_state AS "State", claims AS "Claims", dataset_id AS "Dataset", last_updated AS "Updated"
FROM "II Areas/01_Research/Experiments"
WHERE file.name != this.file.name AND evidence_state != "published" AND row["dg-publish"] = true
SORT last_updated DESC
```
## Evidence by claim

```dataview
TABLE rows.file.link AS "Evidence", rows.evidence_state AS "State", rows.dataset_id AS "Dataset"
FROM "II Areas/01_Research/Experiments"
FLATTEN claims AS claim
WHERE claim AND row["dg-publish"] = true
GROUP BY claim
SORT key ASC
```
## Rules

- No raw file is considered archived until its storage location and immutable identifier/checksum are recorded.
- `qc-passed` requires explicit quality checks, not visual inspection alone.
- An analysis note never overwrites the raw record; changed methods receive a new analysis ID.
- Private storage paths and sensitive apparatus details are not published.

## Related notes

- [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix|Dissertation Claims & Evidence Ledger]]
- [[_System/Research Methodology & Workflows|Research Methodology & Workflows]]
- [[Methods Index]]

