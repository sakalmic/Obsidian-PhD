---
{"dg-publish":true,"permalink":"/ii-areas/03-thesis/claims/cl-02-delay-and-jitter-response/","title":"CL-02 - Delay and jitter response","tags":["topic/ltsg/timing","topic/ltsg/statistics"],"noteIcon":"","updated":"2026-09-14","dg-note-properties":{"title":"CL-02 - Delay and jitter response","aliases":["CL-02"],"claim_id":"CL-02","type":"claim","status":"hypothesis","claim_role":"primary","contribution":"C-W1","context":"thesis","work_packages":["WP0","WP3","WP4"],"datasets":[],"analyses":[],"manuscripts":["Paper-1"],"chapters":["Chapter-4"],"topics":["topic/ltsg/timing","topic/ltsg/statistics"],"tags":["topic/ltsg/timing","topic/ltsg/statistics"],"created":"2026-09-03","last_updated":"2026-09-14"}}
---


# CL-02 - Delay and jitter response

Current contribution mapping: C-W1. Atmospheric Tier 1 only; the claim remains a hypothesis until linked evidence supports or bounds it. C-W5 supplies traceability. See [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix\|Claim Ledger & Evidence Matrix]].

## Claim

Within the frozen atmospheric operating domain, test whether measured laser/channel variables change the delay distribution and dispersion after accounting for voltage, session and electrode state. The direction, shape and possible saturation of the relationship are empirical questions. A general monotonic shortening with increasing irradiance is not assumed or adopted from the historical APL interpretation.

## Primary outcomes

- censored delay distribution;
- median or model-based characteristic delay;
- standard deviation for literature comparison and robust MAD-based dispersion with interval estimates.

## Required evidence

- frozen timing-marker definitions and channel-delay budget;
- adequate instrument resolution relative to the claimed jitter;
- failed shots retained as censored observations;
- confirmatory conditions chosen from WP3, not selected retrospectively;
- independent repeat.

## Decision rule

Predeclare a two-sided effect or model comparison and the smallest practically relevant change before confirmatory analysis. Report distributions and uncertainty after adjusting for voltage, session and electrode state. An unresolved trend, null effect or unidentified plateau must be reported as a limit, not converted into a monotonic claim.

## Connections

- **Up:** [[II Areas/01_Research/Concepts/202609031210 - Statistical and Formative Time Lags Are Different Processes\|Statistical and Formative Time Lags Are Different Processes]] · [[II Areas/01_Research/Concepts/202609031220 - Censored Breakdown Delays Require Survival Analysis\|Censored Breakdown Delays Require Survival Analysis]] · [[II Areas/01_Research/Concepts/202609031300 - Timing Jitter Must Be De-Embedded from the Measurement Chain\|Timing Jitter Must Be De-Embedded from the Measurement Chain]]
- **Side:** [[II Areas/03_Thesis/Claims/CL-01 - Laser-assisted breakdown probability\|CL-01 - Laser-assisted breakdown probability]] · [[II Areas/03_Thesis/Claims/CL-03 - Channel state versus pulse energy\|CL-03 - Channel state versus pulse energy]]
- **Down:** [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028\|Core LTSG Research Programme (2026–2028)]]
