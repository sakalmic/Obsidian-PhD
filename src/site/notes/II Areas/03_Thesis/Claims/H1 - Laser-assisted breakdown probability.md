---
title: "H1 - Laser-assisted breakdown probability"
aliases:
  - H1
statement_id: H1
type: research_hypothesis
status: planned
claim_role: primary
contribution: "C1"
context: thesis
work_packages:
  - WP1
  - WP3
  - WP4
datasets: []
analyses: []
manuscripts: ["Paper-1"]
chapters: ["Chapter-4"]
topics:
  - topic/ltsg/breakdown
  - topic/ltsg/statistics
tags:
  - topic/ltsg/breakdown
  - topic/ltsg/statistics
created: 2026-09-03
last_updated: "2026-09-14"
dg-publish: true
---

# H1 - Laser-assisted breakdown probability

Contribution: C1. Atmospheric Tier 1 only; the statement remains unverified until linked evidence supports or bounds it. C4 supplies traceability. See [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix|Claim Ledger & Evidence Matrix]].

## Hypothesis

At a fixed subcritical working coefficient $k=U_{app}/U_{50}$, laser excitation changes the probability of breakdown within a predeclared trigger gate relative to a matched no-laser control.

## Primary outcome

Difference or ratio in breakdown probability with an interval estimate, conditional on measured environment, day and electrode state.

## Required evidence

- reproducible WP1 estimate of $U_{50}$;
- randomized matched laser/no-laser observations;
- measured laser variables and complete failed-shot records;
- independent repeat on another day or after a declared electrode-service boundary.

## Decision rule

Before WP4, define the smallest practically relevant probability change and required interval precision. Mark supported only when the confirmatory interval excludes effects smaller than that threshold in the predicted direction and the independent repeat is consistent.

If the interval includes no practically relevant change, report a quantitative upper bound and mark `falsified-bounded` rather than discarding the result.

## Connections

- **Up:** [[II Areas/01_Research/Concepts/202609031230 - Breakdown Voltage Is a Probability Distribution Not a Constant|Breakdown Voltage Is a Probability Distribution Not a Constant]] · [[II Areas/01_Research/Concepts/202609031020 - Townsend Avalanche Is Exponential but Not Yet a Streamer|Townsend Avalanche Is Exponential but Not Yet a Streamer]] · [[II Areas/01_Research/Concepts/202609031240 - Hierarchical Shot-Level Models Separate Effects from Drift|Hierarchical Shot-Level Models Separate Effects from Drift]]
- **Side:** [[II Areas/03_Thesis/Claims/P1 - Delay and jitter response|P1 - Delay and jitter response]]
- **Down:** [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028|LTSG Core Research Package 2026-2028]]
