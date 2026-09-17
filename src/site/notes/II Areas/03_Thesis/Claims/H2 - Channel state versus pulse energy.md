---
title: "H2 - Channel state versus pulse energy"
aliases:
  - H2
statement_id: H2
type: research_hypothesis
status: planned
claim_role: primary
contribution: "C2"
context: thesis
work_packages: ["WP2", "WP3", "WP4", "WP5"]
datasets: []
analyses: []
manuscripts: ["Paper-2"]
chapters: ["Chapter-5"]
topics:
  - topic/ltsg/channel
  - topic/ltsg/breakdown
tags:
  - topic/ltsg/channel
  - topic/ltsg/breakdown
created: 2026-09-03
last_updated: "2026-09-14"
dg-publish: true
---

# H2 - Channel state versus pulse energy

Contribution: C2. Atmospheric Tier 1 only; the statement remains unverified until linked evidence supports or bounds it. C4 supplies traceability. See [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix|Claim Ledger & Evidence Matrix]].

## Hypothesis

Measured channel descriptors such as focus position, continuity, length or an approved density/emission proxy improve out-of-sample prediction of trigger success or delay compared with a model using pulse energy and voltage alone.

## Primary comparison

- baseline model: $k$, measured pulse energy and declared nuisance variables;
- channel-informed model: baseline variables plus predeclared channel descriptors.

## Required evidence

- calibrated channel imaging or proxy measurement;
- shot-level linkage between optical and electrical records;
- untouched validation subset or later independent session;
- comparison using predictive calibration and a proper scoring rule.

## Decision rule

The metric and minimum worthwhile predictive improvement are fixed after screening and before confirmatory validation. If the channel-informed model does not improve held-out prediction, report the equivalence or upper bound; do not substitute in-sample fit.

## Connections

- **Up:** [[II Areas/01_Research/Concepts/202609031120 - Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions|Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions]] · [[II Areas/01_Research/Concepts/202609031140 - Hydrodynamic Density Depression Creates Electrical Memory|Hydrodynamic Density Depression Creates Electrical Memory]] · [[II Areas/01_Research/Concepts/202609031340 - Predictive Validation Must Be Separated from Model Calibration|Predictive Validation Must Be Separated from Model Calibration]]
- **Side:** [[II Areas/03_Thesis/Claims/P1 - Delay and jitter response|P1 - Delay and jitter response]] · [[II Areas/03_Thesis/Claims/H4 - Reduced predictive model|H4 - Reduced predictive model]]
- **Down:** [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028|LTSG Core Research Package 2026-2028]]
