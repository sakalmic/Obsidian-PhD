---
title: "LTSG Core Research Package 2026-2028"
aliases:
  - LTSG Core Package
  - Basic Experimental Package
project_id: LTSG-Core
type: project
context: research
priority: critical
status: active
due: 2028-04-30
definition_of_done: "Core claims tested with traceable evidence, independent repeat, held-out model validation and incorporation into manuscripts and thesis Chapters 2-4."
topics:
  - topic/ltsg/breakdown
  - topic/ltsg/channel
  - topic/ltsg/timing
  - topic/ltsg/model
tags:
  - topic/ltsg/breakdown
  - topic/ltsg/channel
  - topic/ltsg/timing
  - topic/ltsg/model
date: 2026-09-02
last_updated: 2026-09-03
dg-publish: false
---

# LTSG Core Research Package 2026-2028

## Decision statement

The minimum defensible dissertation package is a reproducible, time-resolved and predictive study of how the **measured state of a laser-created channel** changes probability, delay and jitter of high-voltage air-gap breakdown. The core package must stand on its own without EMP, ionising-radiation or techno-economic results. Those measurements are staged extensions activated only after the electrical and optical baseline is stable.

> [!abstract] Core dissertation question
> How does the measured time-dependent state of a laser-induced channel, rather than nominal pulse energy alone, determine breakdown probability, delay and jitter in an atmospheric-pressure high-voltage gap at a controlled working coefficient, and can a reduced model predict these outcomes under held-out conditions?

The immediate scope-freeze project is [[Minimum Dissertation Study & Research Discussion 2026]]. The canonical claim structure is [[Claim Ledger & Evidence Matrix]].

## Scope boundaries

### Included in the core package

- Atmospheric air at measured pressure, temperature and relative humidity.
- Existing nanosecond or picosecond laser capability, initially at 1064 nm and 532 nm if both are available.
- One reference electrode geometry and one deliberately non-uniform geometry.
- DC or a reproducible impulse source already available in the FEL laboratory.
- Synchronous measurement of laser timing, gap voltage, discharge current and optical emission.
- Statistical characterisation of self-breakdown and laser-triggered breakdown.
- A reduced-order physical model linking seed ionisation, gas-density evolution and discharge formation.

### Explicitly outside the minimum package

- Demonstrating a deployable power-grid circuit breaker.
- Claiming interruption of AC fault current or arc quenching without a current-zero experiment.
- Neutron-source development.
- Full 3D plasma chemistry before a reduced model has been validated.
- Techno-economic payback claims without validated component lifetime, reliability and cost data.

## Claim and contribution structure

| Contribution | Stable claims | Main response | Core status |
| --- | --- | --- | --- |
| C-A — Reproducible operating window | [[CL-01 - Laser-assisted breakdown probability]], [[CL-02 - Delay and jitter response]] | Probability and censored delay/jitter at controlled $k$ | Required |
| C-B — Channel-state mechanism | [[CL-03 - Channel state versus pulse energy]], [[CL-06 - Reproducible optical and electrical stages]] | Held-out predictive value of channel state and timing classes | Required |
| C-C — Predictive reduced model | [[CL-05 - Reduced predictive model]] | Probability or median delay under untouched conditions | Required |
| Supporting robustness | [[CL-04 - Polarity and field geometry]] | Polarity/geometry interaction or quantitative bound | Conditional |

The stable CL notes contain the acceptance and falsification rules. Do not maintain a second independent hypothesis definition here.

## Measurands and operational definitions

| Quantity | Operational definition | Required metadata |
| --- | --- | --- |
| $U_{50}$ | Voltage at 50% self-breakdown probability for the specified geometry and environment. | Gap, electrodes, polarity, pressure, temperature, humidity, conditioning state. |
| Working coefficient $k$ | $U_{app}/U_{50}$, determined separately for each geometry/polarity/session block. | $U_{50}$ estimate and uncertainty. |
| Trigger success | Main discharge occurs within a predeclared gate after the laser marker. | Gate width and censoring rule. |
| Delay $t_d$ | Time between a defined laser timing marker and a defined electrical breakdown marker. | Marker definitions, channel delays and bandwidth. |
| Jitter | Prefer standard deviation for comparison with literature; also report MAD-based robust sigma and confidence interval. | Sample count, rejected-shot rule and estimator. |
| Breakdown marker | Example: voltage collapses through 50% of pre-shot value, cross-checked by current threshold. | Threshold sensitivity analysis. |
| Laser intensity | Calculated from measured pulse energy, pulse duration and focal profile; never inferred from nominal laser settings alone. | Energy, temporal shape, beam waist, $M^2$, wavelength. |
| Channel geometry | Length, diameter, continuity and position relative to the electrodes. | Camera calibration, gate and exposure delay. |

## Minimum diagnostic stack

### Essential

- Fast photodiode sampling a safe fraction of the laser pulse for the time origin.
- Calibrated high-voltage divider/probe with documented transfer response.
- Current monitor appropriate to the expected rise time and peak current.
- Oscilloscope with a common time base, sufficient analogue bandwidth and a documented trigger path.
- Pulse-energy meter; beam-profile or knife-edge measurement at a safe low-power surrogate plane.
- Synchronized camera or fast photodetector monitoring optical emission.
- Environmental logging: pressure, temperature and relative humidity.
- A reproducible shot identifier linking raw files, settings, calibration and operator notes.

### Preferred

- ICCD or gated intensified imaging for streamer/channel development.
- Spectrometer with gateable detector.
- Second voltage/current measurement path for cross-checks.
- D-dot/B-dot sensors for a first non-quantitative EMP channel, physically separated from the switching diagnostics.

### Deferred

- Calibrated broadband EMP antennas and de-embedding.
- Shielded fast X-ray detector.
- Passive dosimetry arrays and neutron diagnostics.

## Calibration and timing budget

Create a timing budget before the first physics campaign:

$$t_{reported}=t_{physical}+t_{sensor}+t_{cable}+t_{scope}+t_{algorithm}.$$

For each channel record sensor delay, cable length/type, attenuator/filter, termination, bandwidth and polarity. Verify relative delays with a common calibration pulse where electrically safe. The uncertainty of a sub-nanosecond jitter claim must be smaller than the claimed jitter; otherwise report an upper bound limited by the measurement chain.

## Experimental sequence

### WP0 - Safety, metrology and frozen protocol

- [ ] Draw the complete equivalent circuit including stray inductance, return paths and grounding.
- [ ] Approve laser and high-voltage risk assessments, interlocks, exclusion zones and emergency procedure.
- [ ] Define waveform and measuring-system terminology against IEC 60060-1:2025 and IEC 60060-2:2025.
- [ ] Freeze raw-data naming, shot metadata and calibration records.
- [ ] Measure noise with laser off/HV off, laser on/HV off, HV on below discharge/laser off, and both armed without a commanded shot.
- [ ] Define exclusion and censoring rules before inspecting the main dataset.

**Exit criterion:** complete dry run produces a time-aligned record with known polarity and uncertainty on every essential channel.

### WP1 - Self-breakdown baseline

- [ ] Condition electrodes using a documented procedure and record shot count since cleaning/replacement.
- [ ] Determine $U_{50}$ using an up-and-down or staircase method for each geometry and polarity.
- [ ] Repeat a subset on at least three days to quantify day-to-day drift.
- [ ] Fit a probabilistic model of breakdown rather than reporting only a single breakdown voltage.
- [ ] Photograph and measure electrode condition before and after each block.

**Exit criterion:** $U_{50}$ and its uncertainty are stable enough to define $k$; environmental and conditioning effects are quantified.

### WP2 - Laser-only channel calibration

- [ ] Measure pulse energy distribution shot by shot or at a justified sampling interval.
- [ ] Measure pulse duration and beam waist/profile for every wavelength/configuration.
- [ ] Determine the 50% probability threshold for visible plasma under the laboratory atmosphere.
- [ ] Map focus position and channel continuity through the gap.
- [ ] Record optical emission/density proxy versus delay after the laser pulse.

**Exit criterion:** nominal laser settings can be converted into measured optical variables with uncertainty.

### WP3 - Screening experiment

Use a sequential design rather than a full grid. Suggested starting factors:

- $k$: four levels spanning a clearly subcritical condition to close below self-breakdown.
- Laser energy/intensity: off plus three measured levels around and above the plasma threshold.
- Focus position: cathode-side, centre and anode-side.
- Wavelength: 1064 nm and 532 nm when available.
- Geometry/polarity: begin with one geometry and one polarity; introduce the second only after repeatability is demonstrated.

Start with 20 shots per condition. Increase to at least 50-100 only for transition regions, jitter claims and final publication conditions. Randomise within safe blocks and treat day/electrode state as blocking variables.

**Exit criterion:** identify a compact operating window with high trigger probability, measurable sensitivity to factors and no uncontrolled drift.

### WP4 - High-statistics timing and mechanism campaign

- [ ] Acquire at least 100 valid shots at each selected operating point.
- [ ] Acquire synchronized electrical and optical records.
- [ ] Decompose the delay distribution into prompt, delayed and failed/censored populations.
- [ ] Test polarity and geometry interactions.
- [ ] Repeat the key result after electrode service and on another day.
- [ ] Compare a plasma-producing pulse with a non-ionising/heating control if feasible.

**Exit criterion:** one independently repeated result supports or falsifies H1-H6 with a complete uncertainty budget.

### WP5 - Reduced model and validation

- [ ] Implement a 0D/1D electron-balance model to identify dominant timescales.
- [ ] Add a reduced gas-density channel model or measured density proxy.
- [ ] Couple the model to local $E/N$ and a breakdown/streamer inception criterion.
- [ ] Calibrate only a declared subset of parameters; reserve other conditions for validation.
- [ ] Report prediction intervals and failure regions, not only best-fit curves.

**Exit criterion:** the model predicts at least one held-out observable such as triggering probability or median delay within declared uncertainty.

## Statistical plan

Detailed rationale and equations: [[Statistics - Breakdown Probability Delay and Jitter]].

- Trigger success is binomial: report probability with Wilson or exact confidence intervals.
- Failed shots are right-censored observations, not automatically discarded.
- Switching delay should be displayed as distributions and survival curves, not only mean ± standard deviation.
- Use a generalized linear mixed model for success and a survival or accelerated-failure-time model for delay; include run/day as a random effect where possible.
- Use bootstrap confidence intervals for jitter if the distribution is non-Gaussian.
- Correct for repeated testing or predeclare primary comparisons.
- Separate exploratory screening from confirmatory repetitions.
- Archive scripts and environment information with the dataset.

## Deliverables and acceptance criteria

| Deliverable | Acceptance criterion |
| --- | --- |
| D1 - Metrology dossier | Traceable channel list, transfer responses, timing offsets and uncertainty budget. |
| D2 - Baseline dataset | Self-breakdown distributions for reference geometry/polarity on ≥3 days. |
| D3 - Laser calibration dataset | Energy, duration, beam profile and plasma threshold linked to shot IDs. |
| D4 - Screening report | Ranked factor effects and selected operating window. |
| D5 - Confirmatory dataset | ≥100 valid shots per key condition plus an independent repeat. |
| D6 - Reduced model | Reproducible code, parameter table, calibration/validation split and sensitivity analysis. |
| D7 - Paper 1 | Methods and core switching dynamics manuscript. |
| D8 - Thesis chapters | Theory, methods and core results complete before the final writing phase. |

## Calendar and milestones

| Period | Main work | Gate / output |
| --- | --- | --- |
| Sep 2026 | [[Minimum Dissertation Study & Research Discussion 2026]]; freeze topic, question, contribution structure and scope. | G-1: topic fixed by the discussion. |
| Oct-Dec 2026 | WP0; standards, safety, metrology, protocol, data schema and pilot baseline. | G0: approved protocol and reproducible dry run. |
| Jan-Feb 2027 | WP1 self-breakdown on at least three sessions; minimum/SDZ preparation. | D1-D2 and stable definition of $k$. |
| Mar-Apr 2027 | WP2 laser/channel calibration and pilot laser-to-HV delay scan; submit SDZ application when eligible. | D3 and measurable channel descriptors. |
| May-Jun 2027 | WP3 sequential screening; precision/power design for WP4; take SDZ in the available term. | **June stop/go:** viable operating window or narrower fallback. |
| Jul-Oct 2027 | WP4 confirmatory campaign and independent repeat; prepare Paper 1 in parallel. | D4-D5; frozen dataset; Paper 1 ready. |
| Oct-Nov 2027 | Submit Paper 1; complete or document the required foreign stay where feasible. | Paper 1 submitted. |
| Nov 2027-Feb 2028 | WP5 reduced model and held-out validation; draft Paper 2 and thesis Chapters 3-4. | D6; model supported or bounded. |
| Mar-Apr 2028 | Submit Paper 2; activate at most one extension if all core gates have passed. | Core evidence package complete. |
| May-Jun 2028 | Full dissertation draft, internal review and any additional required publication output. | Full draft with compliance evidence. |
| Jul-Aug 2028 | Corrections, reproducibility package and submission; no new core experiment. | Final dissertation. |

## June 2027 stop/go decision

Continue to the confirmatory campaign only if all are true:

- A stable $U_{50}$ baseline can be reproduced across days.
- Laser energy, timing and focus are measured rather than nominal.
- Trigger probability changes measurably within the safe operating envelope.
- Timing resolution is adequate for the expected jitter.
- Raw data and metadata can be reconstructed from a shot ID.

If not, narrow the thesis to breakdown-voltage probability and channel physics, upgrade the limiting diagnostic, or change geometry before collecting a large dataset.

## Immediate next actions (next three weeks)

- [ ] Complete [[Minimum Dissertation Study & Research Discussion 2026]].
- [ ] Obtain a supervisor decision on the Czech/English title, central question and C-A to C-C.
- [ ] Confirm in writing the SDZ deadline, publication conditions and internationalisation requirement applicable to the 2024 cohort.
- [ ] Confirm the active generator, maximum safe voltage/current, waveform and repetition limit with the laboratory owner.
- [ ] Inventory available probes, oscilloscope bandwidths, cameras, laser diagnostics and calibration status.
- [ ] Freeze the reference electrode geometry and prepare spare electrode sets.
- [ ] Define $t_0$, breakdown marker, trigger gate and failed-shot rule.
- [ ] Create the shot-metadata table and one example dataset.
- [ ] Run the four-state EMI/noise test matrix from WP0.
- [ ] Schedule the first three baseline sessions on different days.
- [ ] Review this package with the supervisor and record scope changes in [[Claim Ledger & Evidence Matrix]] and the discussion minutes.

## Dependencies and related notes

- [[Theory - Laser-Triggered Breakdown and Switching]]
- [[Diagnostics - Timing EMP and Radiation]]
- [[Statistics - Breakdown Probability Delay and Jitter]]
- [[Research Extensions Roadmap]]
- [[Laser-Triggered Spark Gaps (LTSG)]]
- [[Laser-Induced Plasma Dynamics]]
- [[Experimental Diagnostics Campaign]]
- [[ISP & Milestone Tracking]]
- [[Claim Ledger & Evidence Matrix]]

## Standards and anchor sources

- [IEC 60060-1:2025 - High-voltage test techniques, Part 1](https://webstore.iec.ch/en/publication/65088)
- [IEC 60060-2:2025 - High-voltage measuring systems](https://webstore.iec.ch/en/publication/65089)
- [IEC 62475:2026 - High-current test techniques](https://webstore.iec.ch/en/publication/67634) for a future high-current demonstrator.
- B. M. Luther et al., *Appl. Phys. Lett.* 79 (2001), [doi:10.1063/1.1419036](https://doi.org/10.1063/1.1419036).
- L. Arantchouk et al., *Appl. Phys. Lett.* 102 (2013), [doi:10.1063/1.4802927](https://doi.org/10.1063/1.4802927).
- E. W. Rosenthal et al., *Optics Express* 28 (2020), [doi:10.1364/OE.398836](https://doi.org/10.1364/OE.398836).

> [!warning] 2025 terminology change
> IEC 60060-1:2025 introduced a front-time definition for the standard switching impulse and defines it as 170/2500 µs. Older work, including the reviewed Štěpánová dissertation, uses the earlier 250/2500 µs time-to-peak convention. Preserve the original convention when reporting historical experiments and state explicitly which edition/parameter definition is used in new measurements.
