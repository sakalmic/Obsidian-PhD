---
title: LAB-02 - Laser and channel diagnostic pilot
type: laboratory-ticket
status: planned
parent_ticket: RESEARCH-00
work_package: WP2
target_window: 2027-03/2027-04
created: 2026-09-16
last_updated: 2026-09-16
dg-publish: true
---

# LAB-02 — Laser and channel diagnostic pilot

**Parent:** [[II Areas/01_Research/Research Plans/RESEARCH-00 - Atmospheric Tier 1 Workflow 2026-2028|RESEARCH-00 - Atmospheric Tier 1 Workflow 2026-2028]]. **Depends on:** [[II Areas/01_Research/Research Plans/LAB-01 - Atmospheric No-Laser Baseline|LAB-01 - Atmospheric No-Laser Baseline]]. **Next:** [[II Areas/01_Research/Research Plans/LAB-03 - Screening and June Decision Gate|LAB-03 - Screening and June Decision Gate]].

## Purpose

Determine whether a laser-created channel feature can be measured **on a shot linked to its electrical outcome** before breakdown, with enough repeatability to test its predictive value. This is an identifiability check, not a commitment to image the full streamer or infer electron density from brightness.

## Acquisition sequence

1. Fix the reference laser branch and document actual wavelength, pulse duration, delivered energy distribution, beam profile/focus and the relationship between the optical pick-off and arrival at the gap. Do not copy historical PERLA or LIDT specifications into the new configuration record.
2. Run approved laser-only controls, then a small set of safe combined laser/HV conditions around informative baseline working points. Log every attempted shot, including missing pulses and no-breakdown outcomes.
3. Acquire one synchronised candidate descriptor: a calibrated optical waveform or image feature with a declared spatial and temporal window. Where available, compare more than one pre-breakdown time window; avoid features containing the breakdown flash.
4. If the feature is observable only after a fixed landmark time, record which shots already broke down by then. The later model must condition on survival to that landmark and report its coverage.
5. Repeat the candidate feature after independent realignment or on another session. Quantify extraction repeatability and sensitivity to detector settings, background and shot-to-shot energy variation.
6. Compare plausible charge-loss and gas-density timescales with the observations, labelling optical measures as proxies until independent calibration supports a physical-state conversion.

## Records and exit gate

Archive linked optical/electrical records, measured laser inputs, timing corrections, descriptor algorithm, calibration and uncertainty, failed-shot codes and a pilot analysis. Record what imaging or spectroscopy actually resolves; unavailable diagnostics are not assumed present.

**Done when:** at least one interpretable, repeatable, pre-breakdown shot-linked descriptor is defined **or** a quantified diagnostic limit is documented. The supervisor then decides whether M1 is testable, whether a simpler measured proxy is sufficient, or whether the scientific contribution must be narrowed. A full 3D plasma model is not a fallback requirement.
