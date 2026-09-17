---
title: "Core LTSG Research Programme (2026–2028)"
aliases:
  - "LTSG Core Research Package 2026-2028"
  - LTSG Core Package
  - Basic Experimental Package
project_id: LTSG-Core
type: project
context: research
priority: critical
status: active
due: 2028-04-30
definition_of_done: "Core claims tested with traceable evidence, independent repeat, held-out prediction, mandatory TCO and incorporation into manuscripts and thesis Chapters 3-6."
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
last_updated: "2026-09-14"
dg-publish: true
dg-home-link: true
permalink: /ltsg-core-research-package-2026-2028/
dg-permalink: /ltsg-core-research-package-2026-2028/
---

# Core LTSG Research Programme (2026–2028)

The long-term goal of the research programme is to contribute to technically and economically viable high-voltage equipment without SF₆. The selected dissertation is **Tier 1: atmospheric-air metrology, stochastic prediction and mandatory bounded TCO**, with **submission targeted for August 2028**. Tier 2 (CO₂/pressure transfer) and Tier 3 (applications) are separately resourced follow-on research, outside mandatory completion and its publication requirements. Full replacement of SF₆ is the programme's direction, not a demonstrated result or a dissertation completion condition.

Working authority: [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026|Doctoral Progress Review & Dissertation Plan (2024–2028)]], revised 14 September 2026. This records the candidate's planning choice; formal supervisor, committee and ISP/KOS approval remains separately evidenced.

> [!info] Public working baseline
> This package defines the minimum defensible experimental core. It remains a proposal until the dissertation scope is formally agreed. Alternative scopes are compared in [[Variant Dissertation Topics 2026]] and [[Outside-the-Box Dissertation Topics 2026]].

## Decision statement

Can measurements of a laser-created channel improve prediction of breakdown probability and timing in atmospheric air, and support selection of the least-cost operating conditions that satisfy a predefined technical requirement?

The mandatory core includes bounded TCO and operating-choice validation. EMP, radiation, CO₂ and product demonstrators remain outside mandatory completion.

## Scope boundaries

### Included in the core package

- Atmospheric air at measured pressure, temperature and relative humidity.
- One confirmed laser configuration, with measured wavelength, pulse duration and delivered energy. Historical PERLA specifications are documented in the reviewer report; the future configuration and booking remain unconfirmed until D6 is resolved.
- One reference electrode geometry and polarity form the primary condition; one second geometry or polarity is a controlled robustness check, conditional on repeatability, precision and the H3 gate.
- Confirm the current source and laboratory access in WP0. The historical HiLASE system used DC; a new impulse source is not assumed available.
- Synchronous measurement of laser timing, gap voltage, discharge current and optical emission.
- Statistical characterisation of self-breakdown and laser-triggered breakdown.
- A reduced model and independently scored M0/M1 comparison.
- Mandatory TCO, service definition and technically feasible operating choice, with cost collection from WP0.

### Explicitly outside the minimum package

- Demonstrating a deployable power-grid circuit breaker.
- Claiming interruption of AC fault current or arc quenching without a current-zero experiment.
- Neutron-source development.
- Full 3D plasma chemistry before a reduced model has been validated.
- Techno-economic payback claims without validated component lifetime, reliability and cost data.

## Claim and contribution structure

| Contribution | Evidence and role |
| --- | --- |
| C1 | Reproducible atmospheric operating domain; probability and calibrated timing; H1, P1 and supporting P2 |
| C2 | Independent comparison of M0 and channel-informed M1; H2 and H4 |
| C3 | Mandatory bounded TCO and technically feasible operating choice; P3 |
| C4 | Traceable data, calibrations, analysis, uncertainty and reproducibility across all claims |

H3 is supporting robustness within the frozen atmospheric configuration family. C5 and C6 belong only to follow-on Tier 2. A null result must be accompanied by adequate sensitivity and a quantitative limit; it does not automatically guarantee degree sufficiency.

Use [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix]] and the atomic H/P notes for evidence rules.

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

## Configuration and timing decision

[[II Areas/01_Research/Apparatus_and_Safety/LTSG Apparatus & Laboratory Safety]] defines the configuration evidence required before WP0. For a laser-to-HV scan, specify the independently controlled HV event and measure its waveform. A continuously applied DC voltage alone does not define an adjustable HV-onset delay; without an appropriate pulsed/gated configuration, narrow the experiment to laser-to-breakdown timing at fixed DC bias.

[[II Areas/06_Administration/Supervisor_Sync/Doctoral Scope & Decision Register|Dissertation Scope & Decision Log]] records the pending apparatus decision.

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
- [ ] Calibrate the selected channel descriptor; visible-plasma threshold mapping is conditional on the chosen configuration and diagnostic value.
- [ ] Map focus position and channel continuity through the gap.
- [ ] Record optical emission/density proxy versus delay after the laser pulse.

**Exit criterion:** nominal laser settings can be converted into measured optical variables with uncertainty.

### WP3 - Screening experiment

Use a sequential design rather than a full grid. Suggested starting factors:

- $k$: four levels spanning a clearly subcritical condition to close below self-breakdown.
- Laser energy/intensity: off plus three measured levels around and above the plasma threshold.
- Focus position: cathode-side, centre and anode-side.
- Wavelength: use the confirmed reference configuration; add a second wavelength only with measured optical calibration and justified comparison.
- Geometry/polarity: begin with one reference geometry and one polarity; introduce one second geometry or polarity only as a bounded robustness comparison after repeatability is demonstrated.

Pilot counts are provisional. Freeze confirmatory counts after WP3 using the required precision or power, observed failure rate and session effects. Count attempted shots and valid acquisition records separately from successful discharges. Randomise within safe blocks and treat day/electrode state as blocking variables.

**Exit criterion:** identify a compact operating window with high trigger probability, measurable sensitivity to factors and no uncontrolled drift.

### WP4 - High-statistics timing and mechanism campaign

- [ ] Acquire the predeclared number of valid acquisition records at each selected operating point, including misfires; use the WP3 precision/power calculation and stopping rule.
- [ ] Acquire synchronized electrical and optical records.
- [ ] Decompose the delay distribution into prompt, delayed and failed/censored populations.
- [ ] Test polarity/geometry interactions only if the supporting H3 gate is activated within the frozen configuration family.
- [ ] Repeat the key result after electrode service and on another day.
- [ ] Compare a plasma-producing pulse with a non-ionising/heating control if feasible.

**Exit criterion:** the required atmospheric claims are tested or bounded with an independent repeat and complete uncertainty budget.

### WP5 - Reduced model and validation

- [ ] Implement a 0D/1D electron-balance model to identify dominant timescales.
- [ ] Add a reduced gas-density channel model or measured density proxy.
- [ ] Couple the model to local $E/N$ and a breakdown/streamer inception criterion.
- [ ] Calibrate only a declared subset of parameters; reserve other conditions for validation.
- [ ] Report prediction intervals and failure regions, not only best-fit curves.

**Exit criterion:** score M0/M1 on the predeclared held-out observable with uncertainty, sensitivity and failure bounds. A lack of improvement is a reported result; academic sufficiency requires review rather than an automatic positive claim.

## WP6 - Mandatory TCO integration

The decision compares technically feasible configurations of the same atmospheric laboratory switching service at fixed demand and predefined timing/success requirements. Report shared-facility allocation separately from a dedicated-installation scenario.

Include investment, electricity and cooling, operator/alignment time, maintenance, replacement, incremental failure/reset costs and residual value. Record source, price year, currency, horizon, discounting convention and utilisation. Avoid double counting acquisition, access fees, depreciation and failure costs. Optical pulse energy is not wall-plug electricity.

Use the discounted TCO model in the reviewer report and report cost per expected compliant operation, TCO(x)/[A(x)q(x)], with demand/capacity constraints and uncertainty in q(x). Freeze service requirements and the operating-choice rule before independent validation. Report feasible domain, cost ranking, sensitivity and break-even boundaries; if no point qualifies or the ranking is unstable, state that result.

Data collection begins in WP0; WP6 integrates it by April 2028. Unsupported lifetime, avoided grid outages, avoided SF₆ costs and full product replacement are excluded from the base case. They belong only to separately evidenced follow-on applications.

## WP7 - Dissertation synthesis

Continuous drafting, complete draft by June 2028, eligibility review and August 2028 submission. Optional research cannot displace writing or publication obligations.

## Statistical plan

Detailed rationale and equations: [[II Areas/01_Research/Concepts/Statistics - Breakdown Probability Delay and Jitter]].

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
| D3 - Laser calibration dataset | Energy, duration, beam profile and selected channel descriptor linked to shot IDs. |
| D4 - Screening report | Ranked factor effects and selected operating window. |
| D5 - Confirmatory dataset | Predeclared precision/power-based acquisition count including failures, plus an independent repeat. |
| D6 - Reduced model | Reproducible code, parameter table, calibration/validation split and sensitivity analysis. |
| D7 - Paper 1 | Methods and core switching dynamics manuscript. |
| D8 - TCO and Paper 2 | Validated operating choice, cost model and sensitivity by April 2028; Paper 2 submission. |
| D9 - Thesis chapters | Core evidence, prediction and TCO chapters complete before final writing. |

## Calendar and milestones

| Period | Work package | Required result |
| --- | --- | --- |
| Sep–Dec 2026 | WP0: scope and metrology | Confirm apparatus, optical timing, protocol, service requirements and cost boundary |
| Jan–Feb 2027 | WP1: baseline | Reproducible no-laser/self-breakdown reference and session/environment blocks |
| Mar–Apr 2027 | WP2: channel pilot | Repeatable descriptor or documented diagnostic limit |
| May–Jun 2027 | WP3: screening | Compact confirmation matrix, sample size and frozen analysis; June stop/go |
| Jul–Oct 2027 | WP4: confirmation | Locked atmospheric dataset and independent repeat; prepare Paper 1 |
| Oct–Nov 2027 | Paper 1 | Submit metrology and stochastic operating-domain study |
| Nov 2027–Feb 2028 | WP5: prediction | Held-out M0/M1 comparison and independently tested operating rule |
| Mar–Apr 2028 | WP6: TCO integration | Cost synthesis, feasibility and sensitivity; submit Paper 2 |
| Through Jun 2028 | WP7: dissertation writing | Continuous drafting; complete reviewed draft by June |
| Jul–Aug 2028 | WP7: finalisation | Eligibility audit, corrections and August submission; no new core campaign |

Cost collection starts in WP0 and continues during acquisition. The prediction/evidence core closes by February 2028 and TCO synthesis by April. Tier 2/3 may continue from autumn 2028 into 2029 under separate resources; those dates do not extend the dissertation target. Submission is not acceptance of a paper and is not the defence date.

## June 2027 stop/go decision

Continue to the confirmatory campaign only if all are true:

- A stable $U_{50}$ baseline can be reproduced across days.
- Laser energy, timing and focus are measured rather than nominal.
- Trigger probability changes measurably within the safe operating envelope.
- Timing resolution is adequate for the expected jitter.
- Raw data and metadata can be reconstructed from a shot ID.

If not, review the limiting diagnostic and the minimum detectable effect with the supervisor. Narrow the physical claim if necessary while retaining the bounded economic comparison. A fallback requires explicit academic assessment; it is not an automatic guarantee of degree sufficiency.

## Immediate next actions (next three weeks)

- [ ] Complete [[I Projects/03_Milestones/20260925 Minimum/Minimum Dissertation Study & Research Discussion 2026|Professional Discussion: Dissertation Study & Research Plan (2026)]].
- [ ] Obtain a supervisor decision on the Czech/English title, central question and C1, C2, C3 and supporting C4.
- [ ] Confirm in writing the SDZ deadline, publication conditions and internationalisation requirement applicable to the 2024 cohort.
- [ ] Confirm the active generator, maximum safe voltage/current, waveform and repetition limit with the laboratory owner.
- [ ] Inventory available probes, oscilloscope bandwidths, cameras, laser diagnostics and calibration status.
- [ ] Freeze the reference electrode geometry and prepare spare electrode sets.
- [ ] Define $t_0$, breakdown marker, trigger gate and failed-shot rule.
- [ ] Create the shot-metadata table and one example dataset.
- [ ] Run the four-state EMI/noise test matrix from WP0.
- [ ] Schedule the first three baseline sessions on different days.
- [ ] Review this package with the supervisor and record scope changes in [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix|Dissertation Claims & Evidence Ledger]] and the discussion minutes.

## Dependencies and related notes

- [[II Areas/01_Research/Concepts/Theory - Laser-Triggered Breakdown and Switching]]
- [[II Areas/01_Research/Concepts/Diagnostics - Timing EMP and Radiation]]
- [[II Areas/01_Research/Concepts/Statistics - Breakdown Probability Delay and Jitter]]
- [[II Areas/01_Research/Concepts/Research Extensions Roadmap]]
- [[II Areas/01_Research/Concepts/Laser-Triggered Spark Gaps (LTSG)]]
- [[II Areas/01_Research/Concepts/Laser-Induced Plasma Dynamics]]
- [[Experimental Diagnostics Campaign]]
- [[ISP & Milestone Tracking|Doctoral Milestones & ISP Tracker]]
- [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix|Dissertation Claims & Evidence Ledger]]

## Standards and anchor sources

- [IEC 60060-1:2025 - High-voltage test techniques, Part 1](https://webstore.iec.ch/en/publication/65088)
- [IEC 60060-2:2025 - High-voltage measuring systems](https://webstore.iec.ch/en/publication/65089)
- [IEC 62475:2026 - High-current test techniques](https://webstore.iec.ch/en/publication/67634) for a future high-current demonstrator.
- B. M. Luther et al., *Appl. Phys. Lett.* 79 (2001), [doi:10.1063/1.1419036](https://doi.org/10.1063/1.1419036).
- L. Arantchouk et al., *Appl. Phys. Lett.* 102 (2013), [doi:10.1063/1.4802927](https://doi.org/10.1063/1.4802927).
- E. W. Rosenthal et al., *Optics Express* 28 (2020), [doi:10.1364/OE.398836](https://doi.org/10.1364/OE.398836).

> [!warning] 2025 terminology change
> IEC 60060-1:2025 introduced a front-time definition for the standard switching impulse and defines it as 170/2500 µs. Older work, including the reviewed Štěpánová dissertation, uses the earlier 250/2500 µs time-to-peak convention. Preserve the original convention when reporting historical experiments and state explicitly which edition/parameter definition is used in new measurements.
