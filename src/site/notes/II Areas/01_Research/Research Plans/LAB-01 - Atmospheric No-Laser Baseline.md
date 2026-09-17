---
title: LAB-01 - Atmospheric no-laser baseline
type: laboratory-ticket
status: planned
parent_ticket: RESEARCH-00
work_package: WP1
target_window: 2027-01/2027-02
created: 2026-09-16
last_updated: 2026-09-16
dg-publish: true
---

# LAB-01 — Atmospheric no-laser baseline

**Parent:** [[RESEARCH-00 - Atmospheric Tier 1 Workflow 2026-2028]]. **Depends on:** [[LAB-00 - Apparatus and Timing Readiness]]. **Next:** [[LAB-02 - Laser and Channel Diagnostic Pilot]].

## Purpose and fixed scope

Estimate the contemporary no-laser breakdown response of **one reference geometry and polarity in atmospheric air**, with uncertainty. This defines $U_{50}$ and the normalised working voltage $k=U/U_{50}$ for the later laser campaign. Historical minimum breakdown voltages are not interchangeable with this reference.

## Acquisition sequence

1. Record electrode dimensions/material, gap, polarity, circuit state, conditioning/cleaning history and the selected voltage protocol. Photograph or otherwise document electrode condition before and after blocks where feasible.
2. On each attempted no-laser trial, log voltage waveform, breakdown/no-breakdown within the declared observation window, ambient pressure/temperature/humidity, session and electrode-history IDs, and any invalid-acquisition reason.
3. Use a predeclared staircase or other justified adaptive/reference design to sample the transition region. The pilot determines the final attempt count and precision target; do not substitute a fixed historical repetition count.
4. Repeat the main comparison in independently started sessions so that day, alignment and electrode drift are visible. A new polarity or geometry requires its **own** reference rather than reusing the first $U_{50}$.
5. Apply the frozen QC rules without discarding valid no-breakdown attempts. Estimate the response curve and $U_{50}$ with session-aware uncertainty.

## Records and exit gate

Store a versioned protocol, attempt-level manifest, waveform links, electrode/environment log, QC record and analysis script. Connect the result to [[Historical Measurements 2024-2025 - Provenance]] without treating the old series as new repetitions.

**Done when:** $U_{50}$ and its uncertainty are reported for the defined geometry, polarity and observation time; session drift is quantified or bounded; the chosen laser operating region can be stated without extrapolating outside the measured reference. If the baseline is unstable, resolve the dominant apparatus/environment cause before widening the experiment.
