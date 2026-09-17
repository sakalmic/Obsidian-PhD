---
title: LAB-00 - Apparatus and timing readiness
type: laboratory-ticket
status: planned
parent_ticket: RESEARCH-00
work_package: WP0
target_window: 2026-09/2026-12
created: 2026-09-16
last_updated: 2026-09-16
dg-publish: true
---

# LAB-00 — Apparatus and timing readiness

**Parent:** [[RESEARCH-00 - Atmospheric Tier 1 Workflow 2026-2028]]. **Next:** [[LAB-01 - Atmospheric No-Laser Baseline]]. No future laser branch, sensor, bandwidth or session booking is assumed confirmed by this ticket.

## Before acquisition

- [ ] Obtain the laboratory owner's approved configuration and procedure for the laser/HV combination, including circuit, geometry, polarity, stored-energy boundaries, optical path, responsible people and available sessions.
- [ ] Inventory each instrument by ID and current calibration/response evidence: HV and current probes, oscilloscope channels, optical pick-off/photodiode, pulse-energy and beam measurements, channel diagnostic and ambient sensors.
- [ ] Resolve the historical trigger question in [[HiLASE Trigger-to-Optical Timing - Verification Plan]] where possible. Preserve the electrical trigger and add a measured optical reference for the new campaign.

## Method-development runs

1. Draw a channel-to-physical-signal map and specify the optical arrival reference, the breakdown criterion, the observation window and early-event/failure codes **before** calculating delays.
2. Characterise relative channel and cable offsets, detector/probe response, saturation, timebase behaviour and marker sensitivity in the approved configuration. Record fixed offsets and pulse-to-pulse variation separately.
3. Acquire no-laser, laser-only, HV-only and combined controls to identify electrical pickup, optical background, false breakdown markers and unavailable pulses.
4. Define one immutable attempted-shot ID connecting settings, waveforms, optical feature, ambient conditions, electrode history, calibration version and outcome code. Verify that failed attempts remain linkable.
5. Start time and energy/cost logs for shared-facility and possible dedicated-installation TCO scenarios; keep optical pulse energy distinct from wall-plug energy.

## Records and exit gate

Create an apparatus configuration record, timing/uncertainty budget, channel map, control-run QC note, draft shot schema and a cost-input register. Link them through [[Calibrations Index]] and [[Evidence Index]].

**Done when:** the laboratory owner has approved the configuration, all essential signals can be recorded without ambiguity, optical-to-electrical timing uncertainty is stated, and acquisition plus data-retention rules are frozen. If a channel cannot be calibrated, record the limitation and either change the measurement claim or resolve the hardware before LAB-01.
