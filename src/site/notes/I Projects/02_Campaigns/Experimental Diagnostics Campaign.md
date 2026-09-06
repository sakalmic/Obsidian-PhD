---
aliases:
  - Project - Experimental Diagnostics Campaign
project_id: LTSG-Experiment
type: project
context: research
parent_project: LTSG-Core
work_package:
  - WP0
  - WP1
  - WP2
  - WP3
  - WP4
claims:
  - CL-01
  - CL-02
  - CL-03
  - CL-06
priority: high
status: active
due: 2027-10-31
definition_of_done: "WP0-WP4 produce a QC-passed confirmatory dataset and independent repeat linked to CL-01, CL-02, CL-03 and CL-06."
topics:
  - topic/ltsg/metrology
  - topic/ltsg/timing
  - topic/ltsg/channel
tags:
  - topic/ltsg/metrology
  - topic/ltsg/timing
  - topic/ltsg/channel
date: 2026-09-01
last_updated: 2026-09-03
dg-publish: false
---

# Project: Experimental Diagnostics Campaign

## Project objective

Deliver WP0-WP4 of [[LTSG Core Research Package 2026-2028]]: a calibrated, synchronized and statistically reproducible measurement of self-breakdown and laser-triggered breakdown probability, delay, jitter and channel evolution.

## Diagnostic tiers

### Essential core

- **Laser:** available Nd:YAG source at 1064 nm and/or 532 nm; measured energy, duration and focal profile.
- **Time origin:** fast photodiode with calibrated cable delay.
- **Electrical:** calibrated high-voltage measurement and an appropriate current monitor on a common oscilloscope time base.
- **Optical:** fast gap-emission channel; synchronized imaging when available.
- **Context:** pressure, temperature, humidity, geometry and electrode shot history.

### Preferred

- ICCD/gated imaging and time-resolved spectroscopy.
- Redundant voltage/current channel for validation.
- Fibre links or remote acquisition to reduce common-mode/EMP coupling.

### Extensions

- D-dot/B-dot probes and calibrated antennas.
- Passive dosimetry and shielded fast photon detector.
- Neutron diagnostics only after the radiation extension gate.

## Current action board

### WP0 - September-October 2026

- [ ] Confirm generator limits, waveform, circuit and safe repetition rate.
- [ ] Inventory every sensor and its calibration/bandwidth status.
- [ ] Define $t_0$, voltage-collapse marker, current marker and trigger-success gate.
- [ ] Measure cable/channel delays with a common event.
- [ ] Run all-off, laser-only, HV-only and combined noise/pickup controls.
- [ ] Create the machine-readable shot metadata schema.
- [ ] Approve HV, laser and radiation-screening risk assessments.

### WP1 - November 2026-January 2027

- [ ] Freeze reference electrode geometry and conditioning procedure.
- [ ] Measure $U_{50}$ for each initial polarity/geometry with uncertainty.
- [ ] Repeat the baseline on at least three days.
- [ ] Quantify humidity, pressure, temperature and electrode-age drift.

### WP2 - February-April 2027

- [ ] Measure laser pulse-energy distributions, duration and beam waist.
- [ ] Determine the 50% optical-plasma threshold for each wavelength.
- [ ] Map focus position/channel continuity through the gap.
- [ ] Establish the useful laser-HV delay range.

### WP3 - May-June 2027

- [ ] Run the sequential factor-screening design.
- [ ] Estimate factor effects on trigger probability and delay.
- [ ] Select the confirmatory operating window.
- [ ] Hold June stop/go review with the supervisor.

### WP4 - July-October 2027

- [ ] Record ≥100 valid shots per selected confirmatory condition.
- [ ] Repeat the key result after electrode service and on another day.
- [ ] Process gated images with spatial/calibration uncertainty.
- [ ] Freeze a publication-quality core dataset.

## Quality gates

- No jitter claim below the demonstrated timing resolution.
- No discarded failed shot without a predeclared quality/censoring code.
- No comparison across polarity/geometry using a shared $U_{50}$ unless equivalence is demonstrated.
- No spectral or rise-time claim outside calibrated system bandwidth.
- No radiation event claim until EMP false-signal controls pass.

## Outputs

- [[Experimental Measurements Archive]]
- [[Claim Ledger & Evidence Matrix]]
- [[Diagnostics - Timing EMP and Radiation]]
- Paper 1 methods/results package.
