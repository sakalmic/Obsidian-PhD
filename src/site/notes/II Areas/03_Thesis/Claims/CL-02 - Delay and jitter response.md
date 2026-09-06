---
title: "CL-02 - Delay and jitter response"
aliases:
  - CL-02
claim_id: CL-02
type: claim
status: hypothesis
claim_role: primary
contribution: C-A
context: thesis
work_packages:
  - WP0
  - WP3
  - WP4
datasets: []
analyses: []
manuscripts:
  - Paper-1
chapters:
  - Chapter-4
topics:
  - topic/ltsg/timing
  - topic/ltsg/statistics
tags:
  - topic/ltsg/timing
  - topic/ltsg/statistics
created: 2026-09-03
last_updated: 2026-09-03
dg-publish: true
---

# CL-02 - Delay and jitter response

## Claim

Within a reproducible operating window, measured laser/channel intensity initially reduces breakdown delay and dispersion relative to matched controls, with a bounded or saturating response at higher deposited energy or channel strength.

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

Support requires a predeclared trend or model comparison that remains after adjustment for $k$, session and electrode state. If saturation is not resolved, report the observed range and do not claim a plateau.

## Links

- [[Claim Ledger & Evidence Matrix]]
- [[Statistics - Breakdown Probability Delay and Jitter]]
- [[Minimum Dissertation Study & Research Discussion 2026]]
- [[Statistical and Formative Time Lags Are Different Processes]]
- [[Censored Breakdown Delays Require Survival Analysis]]
- [[Timing Jitter Must Be De-Embedded from the Measurement Chain]]
