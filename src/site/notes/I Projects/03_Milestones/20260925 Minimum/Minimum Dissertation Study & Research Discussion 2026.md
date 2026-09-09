---
{"dg-publish":true,"permalink":"/i-projects/03-milestones/20260925-minimum/minimum-dissertation-study-and-research-discussion-2026/","title":"Minimum Dissertation Study & Research Discussion 2026","tags":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/timing","topic/ltsg/model"],"dgHomeLink":true,"noteIcon":"","updated":"2026-09-09","dg-note-properties":{"title":"Minimum Dissertation Study & Research Discussion 2026","aliases":["Dissertation Minimum 2026","Professional Discussion 2026","Rozprava k minimu 2026"],"project_id":"MIN-2026","type":"project","status":"active","context":"thesis","priority":"critical","due":"2026-09-24","due_note":"Working date three weeks from 2026-09-03; replace with the confirmed discussion date.","definition_of_done":"Approved fixed dissertation topic, reviewed minimum-study document, final presentation, defensible claims and recorded committee feedback.","parent_project":"PhD-Dissertation","topics":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/timing","topic/ltsg/model"],"tags":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/timing","topic/ltsg/model"],"created":"2026-09-03","last_updated":"2026-09-09","permalink":"/minimum-dissertation-study-2026/"}}
---


# Minimum Dissertation Study & Research Discussion 2026

> [!info] Public planning status
> This is a working scope proposal for discussion. It does not record approval by the supervisor, committee or KOS. See [[Variant Dissertation Topics 2026\|the comparison of six executable variants]] and [[I Projects/03_Milestones/20260925 Minimum/Outside-the-Box Dissertation Topics 2026\|the technology-opportunity scan]].

## Planning status

The `due` date is provisional. No completed discussion or approved title is asserted. Record confirmation in [[II Areas/06_Administration/Supervisor_Sync/Doctoral Scope & Decision Register\|Doctoral Scope & Decision Register]]. The document hierarchy is [[II Areas/03_Thesis/LaTeX_Thesis/Doctoral Document Map\|Doctoral Document Map]].

## Mission

During the next three weeks, prepare and defend a **fixed, scientifically coherent and executable dissertation topic**. The discussion must demonstrate that the proposed work:

1. addresses a specific gap beyond the 2025 APL conference paper;
2. can be completed with available equipment and time;
3. has explicit research questions, hypotheses and falsification rules;
4. produces original contributions supported by traceable evidence;
5. fits the doctoral programme and leads to timely publications and the State Doctoral Examination.

> [!danger] Immediate priority
> Until the discussion is completed, this project takes priority over optional EMP, radiation, techno-economic and broad COMSOL extensions.

## Decision requested from the discussion

The committee and supervisor should be asked to confirm or refine:

- the final English dissertation title and any formally required Czech translation;
- the central research question;
- the three intended scientific contributions C-A to C-C;
- the boundary between the core thesis and optional extensions;
- the adequacy of the experimental and statistical plan;
- the fit with the Economics of Energy and Electrical Engineering programme;
- the publication route and timetable to the State Doctoral Examination.

Record every required change in the discussion minutes. Do not silently reinterpret the outcome later.

## Proposed fixed topic

### Working title

**Laser-Controlled Breakdown in Atmospheric-Pressure High-Voltage Gaps: Plasma-Channel Diagnostics, Stochastic Switching Dynamics, and Predictive Modelling**

### Short spoken formulation

The dissertation will determine how the **measured state and position of a laser-induced channel**, rather than nominal laser energy alone, control the probability, delay and jitter of high-voltage breakdown, and whether a reduced physical model can predict these outcomes under conditions not used for calibration.

## Why the topic is meaningful

The 2025 APL work established the author's research context in laser-driven high-voltage switching and investigated laser wavelength, pulse energy, irradiance, breakdown voltage and discharge delay. A dissertation must go beyond repeating that parameter scan.

The proposed novelty is the causal and predictive chain:

$$
\text{measured laser input}
\rightarrow
\text{time-dependent channel state}
\rightarrow
\text{breakdown probability and delay distribution}
\rightarrow
\text{electrical waveform}
\rightarrow
\text{validated reduced model}.
$$

Current literature indicates that short-lived charged species and longer-lived hydrodynamic density depletion can both influence discharge initiation. The experiment is therefore organised around a laser-to-HV timing scan and measured channel descriptors rather than energy alone.

## Scientific gap

The minimum should demonstrate that prior work leaves at least four connected gaps:

1. nominal pulse energy is often used as a proxy for the physical channel, although focus, continuity and deposited energy can vary;
2. successful shots are often emphasised while failed or delayed shots are incompletely represented;
3. source jitter, diagnostic uncertainty and discharge stochasticity are not always separated;
4. models are frequently fitted retrospectively without a held-out predictive test.

The thesis addresses these gaps on one controlled atmospheric-pressure apparatus. It does not claim to solve lightning control or grid fault-current interruption.

## Central research question

How does the measured time-dependent state of a laser-induced channel, rather than nominal pulse energy alone, determine breakdown probability, delay and jitter in an atmospheric-pressure high-voltage gap at a controlled working coefficient, and can a reduced model predict these outcomes under held-out conditions?

## Subquestions

### RQ1 — Reproducible operating window

At fixed $k=U_{app}/U_{50}$, how much does laser excitation change breakdown probability and the full delay distribution after accounting for environment, day and electrode history?

### RQ2 — Channel state and mechanism

Do measured focus position, channel continuity and laser-to-HV delay explain trigger success and electrical evolution better than pulse energy alone? Can the experiment distinguish a prompt charge-dominated regime from a later density-channel regime?

### RQ3 — Prediction

Can a reduced model based on local $E/N$, electron balance and a measured or parameterised density channel predict probability or median delay under a session, geometry or operating condition not used for calibration?

### RQ4 — Supporting robustness question

How strongly do polarity and field geometry modify the identified relationships? This is supporting scope and may be bounded rather than exhaustively mapped.

## Intended original contributions

| Contribution | Claims | Minimum successful output |
| --- | --- | --- |
| **C-A — Reproducible operating window** | [[II Areas/03_Thesis/Claims/CL-01 - Laser-assisted breakdown probability\|CL-01 - Laser-assisted breakdown probability]], [[II Areas/03_Thesis/Claims/CL-02 - Delay and jitter response\|CL-02 - Delay and jitter response]] | Normalised probability and delay model with uncertainty and independent repeat |
| **C-B — Channel-state mechanism** | [[II Areas/03_Thesis/Claims/CL-03 - Channel state versus pulse energy\|CL-03 - Channel state versus pulse energy]], [[II Areas/03_Thesis/Claims/CL-06 - Reproducible optical and electrical stages\|CL-06 - Reproducible optical and electrical stages]] | Held-out comparison showing what channel measurements add beyond nominal energy |
| **C-C — Predictive reduced model** | [[II Areas/03_Thesis/Claims/CL-05 - Reduced predictive model\|CL-05 - Reduced predictive model]] | Prediction of at least one untouched outcome with declared tolerance |
| Supporting robustness | [[II Areas/03_Thesis/Claims/CL-04 - Polarity and field geometry\|CL-04 - Polarity and field geometry]] | Interaction estimate or defensible quantitative bound |

Negative or bounded results remain valid if the protocol, metrology and statistical power are defensible.

## Core scope

### Included

- atmospheric air with measured pressure, temperature and humidity;
- one reference geometry and one polarity until repeatability is established;
- measured laser energy, pulse duration/profile, focus position and channel continuity;
- self-breakdown baseline and normalisation by $U_{50}$;
- synchronized voltage, current, laser marker and optical-emission measurement;
- probability, censored delay and jitter analysis;
- a compact reduced model with calibration/validation separation;
- one independent repeat across day or electrode-service boundary.

### Conditional

- second polarity or geometry;
- detailed ICCD/spectroscopic mechanism study;
- EMP pilot;
- limited radiation survey;
- electrode erosion or repetition-rate study;
- pulsed-power demonstrator and reliability/economic assessment.

### Explicitly excluded from the minimum thesis promise

- deployable grid circuit breaker;
- AC fault-current interruption without a current-zero experiment;
- neutron-source development;
- full 3D plasma chemistry before a reduced model is predictive;
- deterministic payback or outage-cost claims without measured reliability and lifetime data.

## Proposed methodology

### WP0 — Metrology and frozen protocol

- complete equivalent circuit, grounding and signal paths;
- safety and interlock documentation;
- channel transfer functions and timing-offset budget;
- operational definitions of $t_0$, success, delay, jitter and censoring;
- machine-readable shot metadata and immutable IDs;
- four-state noise/pickup control matrix;
- predeclared primary outcomes and stopping rules.

### WP1 — Self-breakdown baseline

- determine $U_{50}$ separately for the reference configuration;
- quantify day, environment and electrode-conditioning effects;
- repeat over at least three sessions;
- photograph and record electrode state.

### WP2 — Laser/channel characterisation

- measure pulse energy distribution and temporal/spatial profile;
- determine the visible-plasma threshold probabilistically;
- map focus position, length and continuity;
- scan laser-to-HV delay over physically motivated time ranges.

### WP3 — Sequential screening

- vary only a compact set of factors: $k$, measured channel state, focus and relative delay;
- randomise within safe blocks;
- use pilot data to estimate information and required confirmatory sample size;
- avoid a full combinatorial grid.

### WP4 — Confirmatory experiment

- predeclare a small set of operating points and contrasts;
- retain failed/censored shots;
- acquire sufficient observations based on simulation-based power/precision analysis;
- repeat the principal condition on another day or after electrode service;
- compare energy-only and channel-informed models on held-out data.

### WP5 — Reduced model and validation

- begin with 0D/1D electron and gas-density timescales;
- couple to local $E/N$ and a defensible inception criterion;
- calibrate only on declared conditions;
- evaluate probability or median delay on untouched data;
- report prediction intervals and regions where the model fails.

## Statistical plan to defend

- Breakdown success is binomial and reported with interval estimates.
- Failed shots are retained and treated as censored where appropriate.
- Delay is analysed as a distribution, not only mean ± standard deviation.
- Day/session and electrode state are blocking or random effects.
- Primary comparisons and practically relevant effects are declared before WP4.
- Predictive claims use held-out log loss/Brier score, calibration and interval coverage rather than only statistical significance.
- Exploration and confirmation are visibly separated.

## Role of the FEL theses added to the evidence base

### Cikhardt 2026

Use as methodological support for EMP immunity, complementary sensors, bandwidth awareness, fibre isolation and cautious source attribution. Quantitative HED-plasma results are not transferred to the atmospheric LTSG.

### Štěpánová 2026

Use as support for passive radiation surveying, spatial mapping, background controls and the distinction between detector response and source mechanism. Radiation remains an extension after the core timing and electrical measurements are stable.

## Programme fit

The scientific core is high-voltage switching and plasma diagnostics. Fit with the Economics of Energy and Electrical Engineering programme should be expressed through a **bounded reliability-based feasibility assessment**, using measured distributions of success, timing, recovery, energy and lifetime.

Do not promise a broad techno-economic model in the fixed title unless a named demonstrator and defensible technical inputs are available. The final economic result may be a sensitivity/break-even envelope or a clearly labelled outlook.

## Structure of the minimum-study document

Recommended length and local formal requirements must be confirmed. The content should follow this order:

1. **Title page and formal declarations**
2. **Abstract and keywords** in Czech and English if required
3. **Motivation and engineering context**
4. **Verified state of the art**
5. **Existing author results**, especially APL 2025, with exact limitations
6. **Scientific gap**
7. **Central question, RQ1-RQ4 and hypotheses**
8. **Intended original contributions C-A to C-C**
9. **Experimental apparatus and metrology plan**
10. **Statistical and uncertainty plan**
11. **Reduced modelling strategy**
12. **Feasibility, risks and fallback scope**
13. **Publication and dissertation plan**
14. **Schedule to August 2028**
15. **References**, using verified primary sources

## Minimum figure set

- [ ] Research gap and causal chain diagram
- [ ] Apparatus/equivalent-circuit diagram
- [ ] Diagnostic timing chain and uncertainty budget
- [ ] Example geometry and laser-channel descriptors
- [ ] Experimental sequence WP0-WP5
- [ ] Claim-to-evidence-to-publication map
- [ ] Gantt chart with gates and fallback decisions
- [ ] At least one verified preliminary-result figure, clearly labelled as preliminary

## Presentation structure for the discussion

Target 15-20 minutes unless the committee specifies otherwise.

1. **Problem and relevance** — 1 slide
2. **What has already been done / APL 2025** — 1 slide
3. **State of the art and unresolved gap** — 2 slides
4. **Fixed topic and central question** — 1 slide
5. **Three original contributions** — 1 slide
6. **Experimental design and diagnostics** — 2 slides
7. **Statistics, uncertainty and falsification** — 1 slide
8. **Reduced predictive model** — 1 slide
9. **Scope boundaries and fallback** — 1 slide
10. **Publications, SDZ and schedule** — 1 slide
11. **Decision requested from the committee** — 1 slide

Keep backup slides for equations, detector specifications, sample-size logic, COMSOL complexity, radiation and techno-economics.

## Expected questions and answer preparation

### Where is the novelty beyond APL 2025?

Answer with channel-state measurement, censored statistics, mechanism-sensitive delay scan, independent repetition and held-out prediction.

### Is this plasma physics, power engineering or economics?

The core is a high-voltage switching problem investigated through plasma diagnostics and predictive modelling. Economic relevance is assessed only through measured reliability and feasibility inputs.

### How will statistical and formative delay be separated?

State the operational model, censoring treatment, optical/electrical markers and limitations. Do not claim a unique decomposition without diagnostic evidence.

### Why is pulse energy insufficient?

Because deposited energy, focal geometry, channel continuity and time evolution can vary at the same nominal setting. The thesis tests whether measured channel descriptors improve held-out prediction.

### What happens if the laser effect is weak?

Report a quantitative upper bound and narrow the thesis to the operating envelope, metrology and channel-conditioned breakdown model. Do not expand into unrelated extensions.

### Is COMSOL feasible?

Only a reduced, validated model is mandatory. Full chemistry and 3D coupling are activated only if they improve a predeclared observable.

### Why are EMP and radiation not central?

They require specialised calibration and can be confounded by the measurement chain. They are scientifically valuable extensions after the core causal chain is stable.

## Three-week execution plan

### Week 1 — Freeze the argument

**Goal:** a complete zero draft and supervisor decision on scope.

- [ ] Confirm exact discussion date, required format, language, length and submission route.
- [ ] Confirm the registered topic and procedure for changing/fixing its title.
- [ ] Confirm SDZ deadline, eligibility, publication requirements and foreign-stay status.
- [ ] Obtain and inspect the full APL 2025 paper and any ICOLSE source.
- [ ] Build a verified bibliography of 25-40 core sources; identify 10 anchor papers.
- [ ] Freeze the central question, RQ1-RQ4 and C-A to C-C with the supervisor.
- [ ] Draft sections 1-8 of the minimum.
- [ ] Create the research-gap, causal-chain and apparatus figures.
- [ ] Record all unresolved assumptions in an issue list.

**End-of-week gate:** supervisor agrees that the topic is narrow enough, novel and feasible.

### Week 2 — Make it defensible

**Goal:** complete methods, evidence logic and first full presentation.

- [ ] Draft WP0-WP5, variables, diagnostics and uncertainty budget.
- [ ] Create the shot metadata schema and example dataset manifest.
- [ ] Complete the statistical plan, including censoring and held-out validation.
- [ ] Create one-page risk register with fallback decisions.
- [ ] Map every CL to its experiment, dataset, paper and chapter.
- [ ] Draft publication and SDZ schedule.
- [ ] Complete the minimum zero draft and run a source/claim audit.
- [ ] Build presentation version 1 and backup slides.
- [ ] Hold one 60-minute mock discussion with a technically critical colleague.

**End-of-week gate:** every principal claim has an evidence route and every numerical statement has a source.

### Week 3 — Review and rehearse

**Goal:** final document, final slides and robust oral defence.

- [ ] Incorporate supervisor and mock-discussion comments.
- [ ] Remove unsupported performance, grid and economic claims.
- [ ] Check terminology, notation, references, figure readability and language.
- [ ] Conduct at least two timed rehearsals and one adversarial Q&A rehearsal.
- [ ] Prepare a one-page handout with title, question, contributions and timeline.
- [ ] Freeze PDF and presentation versions at least 48 hours before the discussion.
- [ ] Back up all source files and submit through the confirmed channel.
- [ ] Prepare a discussion-minutes template for immediate recording of decisions.

**Final gate:** the topic, contributions, methods, risks and schedule can each be explained in under one minute without relying on vague application claims.

## Daily working cadence for the sprint

- **Block A — 90 min:** minimum text or literature synthesis.
- **Block B — 90 min:** figure, methods or evidence mapping.
- **Block C — 60 min:** presentation and spoken explanation.
- **Close — 20 min:** update project board, decisions and next action.

Reserve at least one half-day per week for supervisor/colleague feedback and one half-day as schedule buffer.

## Definition of done

- [ ] Exact administrative requirements and discussion date are confirmed.
- [ ] Czech and English titles are approved for presentation.
- [ ] Central question, RQ1-RQ4 and C-A to C-C are internally consistent.
- [ ] Core and conditional scope are explicitly separated.
- [ ] Minimum document has been reviewed by the supervisor.
- [ ] All factual and quantitative claims have inspectable sources.
- [ ] APL 2025 is accurately represented as prior work.
- [ ] Experimental, statistical and modelling plans contain falsification criteria.
- [ ] CL notes link to evidence routes, papers and chapters.
- [ ] Schedule includes SDZ in 2027, publication lead time and foreign stay.
- [ ] Slides fit the allotted time and have backup material.
- [ ] At least three rehearsals have been completed.
- [ ] Committee decisions and required changes are recorded after the discussion.

## Immediate next actions

- [ ] Send the proposed title, central question and C-A to C-C to the supervisor for a binary approve/change decision.
- [ ] Ask OVV/KOS for written confirmation of SDZ and publication requirements applicable to the 2024 cohort.
- [ ] Confirm the exact discussion date and backward-plan the 48-hour freeze.
- [ ] Attach the APL 2025 full text and verified ICOLSE material to the literature workflow.
- [ ] Create the minimum document and presentation source files.

## Dependencies

- [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028\|LTSG Core Research Package 2026-2028]]
- [[II Areas/03_Thesis/LaTeX_Thesis/Thesis Structure & Chapter Outline\|Thesis Structure & Chapter Outline]]
- [[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix\|Claim Ledger & Evidence Matrix]]
- [[_System/Research Methodology & Workflows\|Research Methodology & Workflows]]
- [[I Projects/03_Milestones/20260925 Minimum/ISP & Milestone Tracking\|ISP & Milestone Tracking]]
- [[III Resources/03_Literature/LN - Sakala2025 - APL Lightning Protection\|LN - Sakala2025 - APL Lightning Protection]]
- [[III Resources/03_Literature/LN - Cikhardt2026 - Electromagnetic and Particle Pulses\|LN - Cikhardt2026 - Electromagnetic and Particle Pulses]]
- [[III Resources/03_Literature/LN - Stepanova2026 - Ionising Radiation from Impulse Generators\|LN - Stepanova2026 - Ionising Radiation from Impulse Generators]]
