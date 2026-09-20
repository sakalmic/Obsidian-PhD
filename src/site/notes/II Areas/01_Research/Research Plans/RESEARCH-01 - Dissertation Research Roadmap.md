---
title: RESEARCH-01 - Dissertation research roadmap
aliases:
  - Dissertation research roadmap at a glance
type: research-ticket
status: planned
parent_ticket: RESEARCH-00
scope: mandatory-tier-1
created: 2026-09-16
last_updated: 2026-09-16
dg-publish: true
---

# RESEARCH-01 — Dissertation research roadmap at a glance

## Research sequence at a glance

Read from top to bottom. Laboratory work and theory develop together; each output provides the input for the next phase. Dates are planning windows, not confirmed laboratory bookings. **WP0–WP5 cover the atmospheric-air study; WP6 integrates TCO and WP7 completes the dissertation. The experimental campaign has no separate numbered series.**

| Work package and period | Question to resolve | Practical steps | Theory and analysis | Output / decision gate |
| --- | --- | --- | --- | --- |
| **WP0 · Readiness**<br>Sep–Dec 2026 | Can the measurement chain distinguish laser arrival from breakdown reliably? | **1.** Confirm apparatus and access.<br>**2.** Verify trigger/optical timing and electrical markers.<br>**3.** Establish shot records, controls and cost logs. | Define observables, uncertainty sources, failure codes and the TCO service boundary. | Approved configuration and traceable measurement protocol.<br>[[II Areas/01_Research/Research Plans/LAB-00 - Apparatus and Timing Readiness|LAB-00]] |
| **WP1 · No-laser baseline**<br>Jan–Feb 2027 | How does the reference gap break down without the laser? | **1.** Fix geometry and polarity.<br>**2.** Record breakdown and no-breakdown trials across sessions.<br>**3.** Quantify environmental/electrode drift. | Calculate the static field; estimate $U_{50}$ and its uncertainty; define $k=U/U_{50}$. | Contemporary baseline supporting subsequent laser comparisons.<br>[[II Areas/01_Research/Research Plans/LAB-01 - Atmospheric No-Laser Baseline|LAB-01]] |
| **WP2 · Channel pilot**<br>Mar–Apr 2027 | Can a useful channel feature be measured before breakdown? | **1.** Measure delivered laser inputs.<br>**2.** Acquire synchronised optical/electrical pilot records.<br>**3.** Repeat after realignment. | Define one observable descriptor and a minimal time-evolving channel model; test identifiability. | Repeatable descriptor or documented diagnostic limit.<br>[[II Areas/01_Research/Research Plans/LAB-02 - Laser and Channel Diagnostic Pilot|LAB-02]] |
| **WP3 · Screening and design freeze**<br>May–Jun 2027 | Which small set of conditions will answer the research question? | **1.** Screen selected voltage/laser conditions.<br>**2.** Calculate attempt counts from pilot variability.<br>**3.** Freeze confirmation and validation rules. | Specify M0/M1, feature windows, primary contrasts and the stopping rule. | **June stop/go:** proceed, narrow the claim or resolve the measurement limitation.<br>[[II Areas/01_Research/Research Plans/LAB-03 - Screening and June Decision Gate|LAB-03]] |
| **WP4 · Confirmation**<br>Jul–Oct 2027 | Are the observed probability, delay and channel relationships repeatable? | **1.** Execute the frozen matrix.<br>**2.** Retain every attempt and its outcome.<br>**3.** Repeat independently and reserve whole validation sessions. | Analyse training data, uncertainty and channel timescales; prepare Paper 1. | QC-passed new atmospheric dataset; Paper 1 submission targeted for Oct–Nov 2027.<br>[[II Areas/01_Research/Research Plans/LAB-04 - Atmospheric Confirmatory Campaign|LAB-04]] |
| **WP5 · Independent validation**<br>Nov 2027–Feb 2028 | Does channel information improve prediction on unseen sessions? | **1.** Freeze models and scoring.<br>**2.** Open reserved sessions.<br>**3.** Independently check the preselected operating point. | Compare M0/M1 probability and time-to-event predictions; report uncertainty and failure regions. | Validated performance or an explicit negative result; technical feasibility of the chosen setting.<br>[[II Areas/01_Research/Research Plans/LAB-05 - Independent Prediction and Operating-Choice Check|LAB-05]] |
| **WP6 · TCO**<br>Mar–Apr 2028 | Which validated setting meets the defined service requirement at a defensible cost? | **1.** Consolidate costs logged since WP0.<br>**2.** Compare ownership scenarios.<br>**3.** Test sensitivity and feasibility. | Propagate performance uncertainty into TCO and cost per compliant operation; identify break-even boundaries. | Defensible operating choice, or no demonstrated feasible/stable choice; Paper 2 submission target.<br>[[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice|P3]] |
| **WP7 · Dissertation**<br>Continuous writing; Jun–Aug 2028 | Is the evidence coherent and sufficient for submission? | **1.** Write methods/results throughout research.<br>**2.** Complete the full draft by June.<br>**3.** Check eligibility and submit in August. | Synthesize contributions, limitations and follow-on questions. | **August 2028 submission target**; defence scheduled separately. |

**Goal:** by August 2028, submit a dissertation that explains and predicts laser-controlled breakdown in one bounded family of **atmospheric-air** high-voltage gaps and uses the validated performance to make a **bounded TCO operating choice**. This is a working schedule, subject to laboratory access and academic approval. CO₂/pressure transfer (Tier 2), an application demonstrator or online controller (Tier 3), and proof of complete SF₆ replacement are outside mandatory completion.

## WP0 — Make the experiment measurable (Sep–Dec 2026)

**What to establish:** the available apparatus can produce traceable, shot-linked optical and electrical records.

1. Confirm the actual laser branch, gap/circuit, sensor inventory, laboratory permissions and booking.
2. Verify electrical-trigger timing against optical pulse arrival at the gap; define the breakdown marker, failed-shot codes and uncertainty budget.
3. Freeze the shot record and begin logging equipment use, electrical consumption and operator/reset time for TCO.

**Output:** approved configuration and measurement protocol. Detail: [[II Areas/01_Research/Research Plans/LAB-00 - Apparatus and Timing Readiness|LAB-00 - Apparatus and Timing Readiness]] and [[II Areas/01_Research/Experiments/Calibrations/HiLASE Trigger-to-Optical Timing - Verification Plan|HiLASE Trigger-to-Optical Timing - Verification Plan]].

## WP1 — Establish the no-laser reference (Jan–Feb 2027)

**What to establish:** how the selected atmospheric gap behaves without laser assistance.

1. Fix one reference geometry and polarity; document electrode history and ambient conditions.
2. Record both breakdown and no-breakdown attempts under a declared voltage/observation procedure, repeated across independent sessions.
3. Estimate the contemporary $U_{50}$ curve and uncertainty; define $k=U/U_{50}$ for subsequent comparisons.

**Output:** reproducible baseline and its limits. Detail: [[II Areas/01_Research/Research Plans/LAB-01 - Atmospheric No-Laser Baseline|LAB-01 - Atmospheric No-Laser Baseline]]. **Theory in parallel:** calculate the static field in the actual geometry and test sensitivity to geometry, voltage and numerical mesh.

## WP2 — Test whether the laser channel is observable (Mar–Apr 2027)

**What to establish:** whether a pre-breakdown channel feature can be measured reliably for each relevant shot.

1. Measure actual pulse energy, beam/focus properties and optical arrival time in the confirmed laser configuration.
2. Run a small laser-only and combined laser/HV pilot with synchronised waveforms and one candidate optical descriptor.
3. Repeat after realignment; determine whether the descriptor is available before breakdown and is more than detector noise or the breakdown flash.

**Output:** an interpretable descriptor **or** a quantified diagnostic limit. Detail: [[II Areas/01_Research/Research Plans/LAB-02 - Laser and Channel Diagnostic Pilot|LAB-02 - Laser and Channel Diagnostic Pilot]]. **Theory in parallel:** specify a minimal channel-evolution model using only identifiable states; keep an optical proxy distinct from direct electron density.

## WP3 — Choose the decisive test (May–Jun 2027)

**What to establish:** a compact confirmatory design that can answer the dissertation question with available time.

1. Screen a small set of measured voltage/laser conditions; block by session and electrode history.
2. Use pilot event rates and session variation to determine attempt counts, primary contrasts and a stopping rule.
3. Freeze outcome definitions, M0/M1 inputs, channel-feature window and whole-session validation split. Hold a June supervisor stop/go review.

**Output:** dated decision and frozen confirmation protocol. Detail: [[II Areas/01_Research/Research Plans/LAB-03 - Screening and June Decision Gate|LAB-03 - Screening and June Decision Gate]]. If the apparatus or descriptor fails, narrow the claim explicitly; do not silently expand to another gas or a full plasma simulation.

## WP4 — Acquire new confirmatory evidence (Jul–Oct 2027)

**What to establish:** probability and delay distributions, with uncertainty, for the selected atmospheric conditions.

1. Execute the frozen matrix; retain every ready-state attempt, including no-breakdown and premature events.
2. Link optical timing, voltage/current, laser input, channel descriptor, environment and electrode history by shot ID.
3. Repeat principal contrasts in a separately initiated/realigned session and reserve complete sessions for later validation.

**Output:** QC-passed new dataset and Paper 1 evidence, clearly separated from the seven May 2024 and three February 2025 historical series. Detail: [[II Areas/01_Research/Research Plans/LAB-04 - Atmospheric Confirmatory Campaign|LAB-04 - Atmospheric Confirmatory Campaign]]. **Theory in parallel:** fit a baseline probability/delay model on training data and compare measured channel timescales with the reduced physical description.

## WP5 — Test prediction on unseen sessions (Nov 2027–Feb 2028)

**What to establish:** whether channel information improves prediction beyond voltage and measured laser input, and whether a chosen setting remains technically feasible.

1. Freeze M0 (settings/context), M1 (M0 plus a predeclared pre-breakdown channel feature), preprocessing and scoring before opening reserved sessions.
2. Compare predicted breakdown probability and time-to-event distributions with complete held-out sessions; retain censored attempts and show failure regions.
3. Select an operating point from training/calibration evidence, then test that **preselected** point independently. A feature measured after a pulse cannot retrospectively select that pulse's energy.

**Output:** validated prediction or a documented lack of improvement, plus an independent technical check. Detail: [[II Areas/01_Research/Research Plans/LAB-05 - Independent Prediction and Operating-Choice Check|LAB-05 - Independent Prediction and Operating-Choice Check]].

## WP6 — TCO synthesis (Mar–Apr 2028)

**What to establish:** whether any validated configuration meets a predefined laboratory switching requirement at a defensible cost.

1. Consolidate costs logged since WP0: equipment use, electricity, operator/reset time, servicing and replacement. Distinguish research diagnostics from diagnostics required for routine operation.
2. Combine independently validated performance from WP5 with these costs; compare shared-facility and dedicated-installation scenarios separately.
3. Report feasible choices, uncertainty, sensitivity and break-even boundaries, or no demonstrated feasible/stable choice. Prepare Paper 2.

**Output:** bounded TCO and a defensible operating-choice result. Detail: [[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice|P3 - Techno-economic operating choice]]. This stage uses WP0–WP5; it does not add a new mandatory laboratory campaign.

## WP7 — Dissertation and submission (continuous writing; Jun–Aug 2028)

**What to establish:** a coherent account of new contributions, historical evidence and limitations, suitable for submission.

1. Write methods, results and limitations throughout WP0–WP5 and WP6.
2. Complete the full dissertation draft by June 2028; obtain review and check publication/study eligibility.
3. Revise and target submission in August 2028. The defence date is a separate administrative milestone.

**Output:** reviewed dissertation and submission package. No new core campaign is planned for July–August 2028; Tier 2 and Tier 3 remain outside mandatory completion.

## One-line evidence chain

`approved apparatus → calibrated time and shot record → no-laser reference → observable channel → frozen confirmatory design → independent prediction → bounded TCO → dissertation`

**Detailed master plan:** [[II Areas/01_Research/Research Plans/RESEARCH-00 - Atmospheric Tier 1 Workflow 2026-2028|RESEARCH-00 - Atmospheric Tier 1 Workflow 2026-2028]]. **Controlling reviewer scope:** [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026|Doctoral Progress Review & Dissertation Plan (2024–2028)]].
