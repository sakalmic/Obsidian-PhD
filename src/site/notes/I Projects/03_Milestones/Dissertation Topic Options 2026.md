---
{"dg-publish":true,"permalink":"/i-projects/03-milestones/dissertation-topic-options-2026/","title":"Dissertation Topic Options 2026","tags":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/application"],"dgHomeLink":true,"noteIcon":"","created":"2026-09-08","updated":"2026-09-09","dg-note-properties":{"title":"Dissertation Topic Options 2026","aliases":["Variant Dissertation Topics 2026","Dissertation Topic Options"],"type":"decision-support","status":"proposal","context":"thesis","topics":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/application"],"tags":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/application"],"date":"2026-09-08","last_updated":"2026-09-09","permalink":"/dissertation-topic-options-2026/"}}
---


# Dissertation Topic Options 2026

> [!info] Document status
> This is a public decision-support proposal for discussion. None of the options constitutes an approved dissertation assignment. Emerging directions responding to current technological and commercial questions are assessed in [[I Projects/03_Milestones/Outside-the-Box Dissertation Topics 2026\|Outside-the-Box Dissertation Topics 2026]].

## Continuity with laser-triggered high-voltage spark-gap research

**Decision support for Michal Sakala and supervisor discussion**  
Prepared 8 September 2026 · Proposal for discussion · Planning horizon: September 2026 to August 2028

## Recommendation

The recommended core is **Option B — Laser-created channel state and prediction of high-voltage spark-gap switching**. It offers the strongest continuity with the master’s thesis and subsequent timing measurements, asks a clear physical question, and matches the present core research package. Its original contribution should be a validated prediction based on measured channel state rather than another isolated reduction in breakdown voltage.

**Option A** is the best narrower fallback if advanced optical diagnostics cannot be secured. **Option C** is suitable when the programme requires a stronger control-engineering and commercial dimension. Beam shaping, multiple gaps, or dielectric recovery should be activated only after the necessary apparatus, staff capacity, and schedule have been secured. Combining all six options into one assignment would make the thesis unmanageable.

| Option | Main emphasis | Principal result |
| --- | --- | --- |
| A | Reliability and operating window | Statistically validated conditions for controlled switching |
| B | Channel state and switching mechanism | Reduced predictive model with independent validation |
| C | Adaptive control and operating utility | Control method benchmarked for an equivalent switching task |
| D | Spatial beam and channel shaping | Conditions under which channel shaping outperforms a Gaussian beam |
| E | Synchronisation of two spark gaps | Model and demonstrator of relative switching-time dispersion |
| F | Dielectric recovery and wear | Limits of repeatable post-discharge operation |

## How to read this document

The document first separates demonstrated results from assumptions. Each option then defines a working title, research question, contribution, equipment, difficulty, schedule, continuation gate, and possible application. Durations and laboratory-day estimates are planning assumptions. They are not confirmed HiLASE reservations, supplier quotations, binding study deadlines, or publication guarantees.

## Evidence inherited from the master’s thesis

The 2024 master’s thesis investigated laser triggering of a high-voltage spark gap. The apparatus used 20 mm stainless-steel spherical electrodes, 5 and 10 mm gaps, a Technix SR40kV-5kW source, and picosecond pulses from the PERLA platform. The examined wavelengths were 1030, 515, and 257.5 nm. The beam passed between the electrodes without deliberately striking their surfaces. [S1]

Selected results at the maximum power of each series were:

| Wavelength and regime | Gap | Baseline | With laser | Reduction calculated from voltages |
| --- | ---: | ---: | ---: | ---: |
| 1030 nm, pulse train | 5 mm | 16.9 kV | 13.5 kV | approximately 20% |
| 515 nm, pulse train | 10 mm | 29.5 kV | 20.3 kV | approximately 31% |
| 257.5 nm, pulse train | 10 mm | 29.5 kV | 21.8 kV | approximately 26% |
| 1030 nm, single pulse | 5 mm | 16.9 kV | 12.1 kV | approximately 28% |

The wavelength series did not use identical pulse energies or, in every case, identical focusing optics. They therefore do not establish a universal advantage of shorter wavelengths. The number 62 in the single-pulse series describes setting levels, not 62 repetitions at each operating point. A comparison of single pulses and pulse trains is also affected by different focusing conditions. [S1]

The thesis does not yet provide a validated jitter map, electrode-lifetime data, a current-interruption test, or an economic return calculation. Its recommendations explicitly identify timing, ionisation-wave dynamics, environmental conditions, energy efficiency, geometry, and voltage waveform as open directions. Repeating breakdown-voltage curves alone would therefore be an insufficient doctoral contribution. A transferable relationship, mechanism, validated model, or demonstrably better control method is required. [S1, S2]

## Consequences of subsequent timing work and apparatus review

The local APL 2025 conference manuscript reports three delay series ranging approximately from 0.164 to 8.124 µs, referenced to the electrical laser-trigger edge. That reference cannot be equated with the arrival of the optical pulse at the gap without calibration. At least five repetitions per configuration are reported, but the complete raw dataset was not audited for this assessment. The dissertation should therefore promise calibrated optical time zero, distributions of delay and failure, and between-day repeatability rather than the first timing measurement on the apparatus. [S5]

Two metrology questions must be closed before a confirmatory campaign:

- **Current monitor:** the reported Pearson 1423 has a specified usable rise time of about 0.5 µs and an upper bandwidth near 0.7 MHz. If this exact model was used, its waveform cannot directly demonstrate a nanosecond current rise. The device label, connection, and any separate breakdown-timing channel must be verified. [S5, S7]
- **Voltage probe:** the P6015A is specified at 75 MHz, while present documentation distinguishes 15 kV DC from a limited-duration 40 kV peak pulse. The exact probe version and rating must be checked for the planned waveform. [S8]

The public HiLASE specification lists PERLA B operation at 1030/515 nm, picosecond pulses, and 1 or 10 kHz. This demonstrates platform capability, not availability for this project. The UV branch and the exact pulse parameters remain to be confirmed. Intensity calculations should use one consistent definition of pulse energy, duration, and beam radius or diameter. [S1, S5, S6]

## Comparative feasibility

Difficulty is an expert score from 1 to 5, with 5 denoting the greatest demand. It is not a probability of successful defence.

| Option | Scientific difficulty | Technical difficulty | Estimated duration | Laboratory days | Outlook to August 2028 |
| --- | :---: | :---: | ---: | ---: | --- |
| A | 3/5 | 3/5 | 20–24 months | 35–50 | Most favourable if tightly scoped |
| B | 4/5 | 4/5 | 22–26 months | 45–65 | Feasible if diagnostics are secured early |
| C | 4/5 | 4/5 | 22–28 months | 40–60 | Conditional on automation and a benchmark setup |
| D | 5/5 | 4/5 | 26–32 months | 55–80 | Tight without ready beam-shaping optics |
| E | 4/5 | 5/5 | 26–34 months | 60–85 | Likely to extend into 2029 |
| F | 4/5 | 5/5 | 28–36 months | 65–95 | Likely to extend into 2029 |

A laboratory day means a reserved day with the apparatus and necessary operators, including setup and calibration. The estimates assume an inherited base spark gap, an available laser, and regular measurement blocks. Laser operation, electrical maintenance, fabrication, and specialist consultation require capacity beyond the doctoral researcher’s time.

## Option A — Reliability and robust operating window

**Working title:** *Probabilistic Characterisation and Robust Operating Window of a Laser-Triggered High-Voltage Spark Gap*

### Research question and contribution

How wide and stable is the parameter region in which the laser switches the gap with the required probability and timing precision while premature self-breakdowns remain acceptable? The new contribution would be a validated probability map with uncertainty, between-day transfer, and a quantified reliability–jitter trade-off.

### Proposed tasks

1. Audit the existing self-breakdown and laser-triggered breakdown measurements.
2. Develop a joint protocol for switching probability, delay, jitter, premature breakdowns, and failed triggers.
3. Determine dependencies on the working coefficient, pulse energy, and focal position while recording electrode and environmental state.
4. Build an operating-window model and validate it on independent days and one predefined change of conditions.
5. Derive operating-point rules for reproducible laboratory pulsed-power switching.

### Equipment and experimental design

Required equipment includes the verified laser and attenuation system, stable electrode holder, current-limited discharge circuit, suitable high-voltage divider, fast breakdown marker, photodiode defining optical time zero, common-time-base oscilloscope, pulse-energy and beam-profile diagnostics, and pressure/temperature/humidity logging. A controlled-humidity enclosure and simple channel-position camera are optional. ICCD imaging and full plasma chemistry are not prerequisites.

Begin with one wavelength, one polarity, and the 5 mm spherical gap. Determine $U_{50}$ using a fixed protocol and express applied voltage through $k=U_{app}/U_{50}$. Select points around the transition from unreliable to reliable switching. Treat the 10 mm gap or a controlled humidity change as an external validation case rather than another full factorial matrix.

### Schedule and gate

| Period | Verifiable output |
| --- | --- |
| Sep–Dec 2026 | Audit, calibrations, protocol, reproducible baseline |
| Jan–Apr 2027 | Pilot and main probability map |
| May–Aug 2027 | Between-day repetition and one controlled transfer test |
| Sep–Nov 2027 | Independent validation and Paper 1 |
| Dec 2027–Apr 2028 | Targeted completion and application rules |
| May–Aug 2028 | Synthesis, thesis writing, and review reserve |

By April 2027, the reference point must be repeatable and the transition region measurable. If every tested point always switches or always fails, redesign the operating points. The main applications are operating-point selection, diagnostic synchronisation, and qualification-shot planning for laboratory pulse generators.

## Option B — Channel state and prediction of switching

**Working title:** *Influence of the Laser-Created Channel State on the Probability and Timing of High-Voltage Spark-Gap Breakdown*

### Research question and contribution

Why can similar laser pulse energies produce different switching outcomes and delays? The hypothesis is that measured channel state and its evolution, together with the electric field, carry information that nominal pulse energy does not. The doctoral contribution would be a reproducible relationship between channel diagnostics and electrical response, supported by a reduced model and independent validation.

### Proposed tasks

1. Define measurable optical and electrical descriptors of channel formation.
2. Measure their temporal development and relationship to probability, delay, and jitter.
3. Test whether channel descriptors predict outcomes better than voltage and pulse energy alone.
4. Construct a reduced physically motivated model and analyse parameter identifiability.
5. Validate the model on conditions excluded from fitting and derive control rules with stated limits.

### Equipment and approach

Option B requires all Option A metrology plus at least one time-resolved channel diagnostic: gated imaging, fast photodetection, calibrated schlieren/interferometric density proxy, or another descriptor with sufficient sensitivity. Spectroscopy is useful only when it answers a defined parameter question. Light intensity by itself must not be described as electron density or temperature without calibration and a suitable model.

Start with electrostatic field modelling and a reduced time-domain channel model. Add spatial plasma chemistry only when a specific unexplained phenomenon and adequate validation data justify it. Compare a baseline predictor using $k$ and pulse energy with a model that adds measured channel length, continuity, position, or temporal response.

### Schedule and gate

| Period | Verifiable output |
| --- | --- |
| Sep–Dec 2026 | Metrology audit and optical-diagnostic pilot |
| Jan–Mar 2027 | Repeatable channel descriptor and baseline response |
| Apr–Jun 2027 | Mechanism pilot and three-day reproduction |
| Jul–Oct 2027 | Confirmatory dataset and Paper 1 |
| Nov 2027–Feb 2028 | Reduced model and held-out validation |
| Mar–Aug 2028 | Paper 2, synthesis, thesis, and reserve |

By March 2027, at least one descriptor must be repeatable and have useful dynamic range. If no available diagnostic resolves channel evolution, fall back to Option A and state the limitation. Applications include diagnostic design, geometry selection, model-based trigger optimisation, and transferable design rules for optically triggered pulsed-power devices.

## Option C — Adaptive control and operational utility

**Working title:** *Adaptive Control and Operational Optimisation of a Laser-Triggered High-Voltage Spark Gap*

### Research question and contribution

Can measured pre-shot and early-shot signals be used to maintain reliability and timing as electrodes, environment, and laser delivery drift? The contribution must be a validated control strategy compared with a fixed-setting baseline for the same switching function.

### Proposed tasks and equipment

1. Define the controlled output, admissible failures, and measurable disturbances.
2. Automate voltage, laser-energy, timing, and metadata capture with safety interlocks.
3. Develop an estimator of current operating condition and a constrained adaptation rule.
4. Benchmark fixed, scheduled, and adaptive control under matched conditions.
5. Quantify stability, latency, invalid-shot rate, maintenance burden, and energy use.

The setup requires Option A metrology, remotely controllable attenuation or timing, deterministic acquisition, interlocks, and robust experiment-control software. A simple constrained controller is preferable to an opaque machine-learning model unless data volume and explainability justify the latter.

### Schedule, gate, and application

Allow 40–60 laboratory days. Automation and baseline repeatability must be demonstrated by April 2027. If actuation latency or measurement quality prevents closed-loop operation, retain an advisory optimiser rather than claiming real-time control. The commercial route is automated setup, drift compensation, and lower invalid-shot rates in research pulsed-power systems.

## Option D — Spatial shaping of the laser-created channel

**Working title:** *Spatial Shaping of Laser-Created Plasma Channels for Controlled High-Voltage Discharge Guidance*

### Research question and contribution

Under what conditions does a deliberately shaped channel improve breakdown probability, timing, path control, or tolerance to misalignment relative to an equal-energy Gaussian reference? Originality must come from a quantified causal comparison, not from displaying a visually unusual discharge path.

### Proposed tasks and equipment

1. Select one shaping principle, such as an axicon/Bessel-like beam, multiple foci, or controlled curvature.
2. Measure delivered intensity distribution and channel geometry rather than relying on optical design values.
3. Compare shaped and reference beams at matched delivered energy and electric conditions.
4. Map attachment points, delay, jitter, and optical losses.
5. Model the field–channel interaction and determine the useful tolerance envelope.

Required additions include verified shaping optics or an SLM, beam profiling along the propagation path, imaging of the discharge trajectory, and a reproducible alignment reference. By May 2027, the shaped field and channel must be repeatable. Otherwise, the work should revert to the unshaped channel-state study. Applications include controlled discharge paths, relaxed alignment tolerances, and triggering across larger or obstructed gaps.

## Option E — Synchronisation of two spark gaps

**Working title:** *Optical Synchronisation and Relative Jitter of Coupled High-Voltage Spark Gaps*

### Research question and contribution

Can a common optical source reduce relative jitter between two switching channels, and which optical, electrical, and statistical mechanisms limit synchronisation? The contribution would be a two-channel timing model and a validated demonstrator.

### Proposed tasks and equipment

1. Establish a traceable common optical time reference.
2. Characterise each gap independently before coupling them.
3. Measure joint success probability and the full distribution of relative delay.
4. Separate common-mode laser variation from channel-specific breakdown variation.
5. Demonstrate a defined two-channel pulsed function and quantify scalability.

The experiment needs two independently instrumented gaps, two adequate voltage/current measurement channels, optical splitting with measured energy balance, synchronised acquisition, and safe coupled-circuit design. The gate is independent stable operation of both gaps by June 2027. Applications include simultaneous capacitor discharge, multi-stage pulse generators, and synchronised diagnostic sources.

## Option F — Dielectric recovery and component wear

**Working title:** *Dielectric Recovery, Memory Effects, and Electrode Wear in Repetitively Laser-Triggered Spark Gaps*

### Research question and contribution

How do residual channel state, deposited energy, electrode conditioning, and surface evolution determine hold-off recovery and the next switching event? The contribution would be a recovery model linked to measurable post-discharge state and lifetime indicators.

### Proposed tasks and equipment

1. Define a two-pulse or repeated-shot recovery protocol with controlled deposited energy.
2. Measure hold-off and trigger probability versus inter-shot delay.
3. Track electrode surface, attachment position, roughness, and shot history.
4. Relate electrical action and optical state proxies to recovery.
5. Develop maintenance and repetition-rate limits for a defined application envelope.

This option requires controlled-energy discharges, a true two-pulse test capability, interchangeable electrodes, surface metrology, gas/environment monitoring, and automated shot history. It carries the highest schedule risk. A measurable recovery curve and stable energy estimate must exist by July 2027; otherwise the scope should narrow to electrode conditioning within Option A or B. Applications include maximum repetition rate, maintenance intervals, and lifetime qualification.

## Common evidence requirements

All options require:

- a photodiode or equivalent measurement of the actual optical event at the experiment;
- a validated high-voltage measurement chain and an independently defined breakdown marker;
- a common time base with quantified timing uncertainty;
- pulse-energy and beam-profile measurements at a relevant plane;
- shot-level metadata, including unsuccessful and premature events;
- environmental and electrode-history records;
- raw, processed, and analysis data linked through immutable shot identifiers.

Sample counts must follow the precision needed for the stated conclusion. Five successful events are suitable for a pilot, not for a strong reliability claim. Confirmatory points should use a predefined stopping or sample-size rule, confidence or credible intervals, and explicit handling of censored or failed shots. At least one measurement block, day, geometry, or condition must be held out from model construction.

## Recommended common schedule

| Deadline | Main output | Decision rule |
| --- | --- | --- |
| September 2026 | Selected option, confirmed laser, responsibilities, and reservations | Narrow scope before ordering equipment |
| Oct–Dec 2026 | Audit, calibration, optical pilot, and data protocol | No full matrix without valid time references |
| Jan–Mar 2027 | Reference map and resolvable channel descriptor | Improve diagnostics or fall back to A |
| Apr–Jun 2027 | Mechanism pilot reproduced on at least three days | Freeze the core and defer side extensions |
| Jul–Oct 2027 | Confirmatory campaign and Paper 1 dataset | Add only decisive missing measurements |
| November 2027 | Paper 1 submitted and model identified | Separate review work from scope expansion |
| Dec 2027–Feb 2028 | Held-out validation and closed uncertainty budget | Prefer a narrower defensible model |
| Mar–Apr 2028 | Paper 2 and closed core evidence | Do not start a new independent experiment |
| May–Jun 2028 | Complete dissertation draft and internal review | Focus on synthesis and missing evidence |
| Jul–Aug 2028 | Final revision and submission preparation | Set defence timing from actual rules |

## Recommended assignment for supervisor discussion

### Working title

**Influence of the Laser-Created Channel State on the Probability and Timing of High-Voltage Spark-Gap Breakdown**

### Aim

The work will determine which measurable properties of a laser-created channel control the reliability and timing of breakdown in a high-voltage air gap. It will develop a reduced model capable of predicting selected switching quantities under conditions excluded from model fitting. The study will build on the master’s thesis and subsequent timing measurements, verify their metrological assumptions, and define the conditions under which controlled optical switching is technically useful.

### Assignment tasks

1. Critically analyse prior laser-triggered spark-gap results and the relevant literature on channel initiation, evolution, and stochastic breakdown.
2. Design, implement, and validate simultaneous optical and electrical measurements with a traceable time reference and records of successful and failed trials.
3. Determine switching probability, delay, and jitter as functions of applied voltage and measured channel descriptors in a defined geometry and environment.
4. Quantify the predictive value added by channel descriptors relative to a voltage-and-laser-energy baseline.
5. Construct a reduced physically justified model, quantify uncertainty, and validate predictions on independent measurement blocks.
6. Derive design rules for a laboratory optically triggered pulsed-power device and state their technical limits.

The core should use air, one confirmed laser configuration, one reference geometry, and one polarity. A second geometry or polarity should serve only as a validation test after the baseline map is complete. A narrow cost comparison may be added after technical performance is measured; a full adaptive controller constitutes a separate extension.

## Technical application boundaries

| Thesis result | Nearest technical use | Further evidence required |
| --- | --- | --- |
| Reliable switching map | Trigger settings for a laboratory pulse generator | Transfer to other voltages, gases, and loads |
| Channel-state model | Trigger geometry and diagnostic design | Parameter identification in a new device |
| Adaptive method | Automated setup and reduced invalid-shot rate | Latency, stability, maintenance, fair baseline |
| Shaped channel | Position tolerance and controlled discharge path | Optical loss and long-term alignment |
| Two-gap synchronisation | Coordinated pulsed-power channels | Power coupling and stage scaling |
| Recovery model | Repetition-rate and maintenance limits | Long-duration stress in the target application |

A meaningful economic metric is cost per valid laboratory pulse at equal amplitude, timing tolerance, and reliability. It should include preparation, operation, calibration, infrastructure, consumables, downtime, and invalid shots. Marginal use of an existing laser must be distinguished from the full cost of a dedicated system. Claims about HVDC interruption, grid circuit breakers, outdoor lightning control, EMP protection, plasmoids, neutron generation, or wireless power require separate apparatus and validation and should not be implied by short-gap triggering results.

## Sources and traceability

### Internal evidence

**[S1] Michal Sakala, 2024 master’s thesis and assignment.** *Advanced Triggering of a High-Voltage Spark Gap by a Laser Beam.* Chapters 5–7 and Tables 5.3–5.6 were used as the principal experimental baseline.

- `IV Archives/01_DP_Master_Thesis/thesis/DP_sakalmic.pdf`
- `IV Archives/01_DP_Master_Thesis/thesis/DP_zadani.pdf`

**[S2] Master’s thesis reviews.** Reviews by Eva Müllerová and Jan Mikeš, 2024, particularly the questions concerning the number of trials, applications, and gap-length extensions.

**[S3] [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028\|LTSG Core Research Package 2026-2028]].** Current internal core-research proposal, including contributions C-A to C-C, metrology, validation, and scope boundaries.

**[S4] [[II Areas/06_Administration/Supervisor_Sync/Doctoral Scope & Decision Register\|Doctoral Scope & Decision Register]].** Register used to distinguish proposals from confirmed assignments, equipment access, and study requirements.

**[S5] Sakala et al.** *The Dynamics of Laser-Driven Ionisation in High-Voltage Circuit Switching.* Local APL 2025 conference manuscript; method and Tables II–III were reviewed.

### Public technical sources

**[S6] HiLASE.** [High repetition rate picosecond PERLA B laser](https://www.hilase.cz/en/high-repetition-rate-picosecond-perla-b-laser/).

**[S7] Pearson Electronics.** [Current Monitor Model 1423 datasheet](https://pearsonelectronics.com/pdf/1423.pdf).

**[S8] Tektronix.** [Passive High Voltage Probes](https://www.tek.com/en/datasheet/passive-high-voltage-probes).

**[S9] Rosenthal et al.** *Air hydrodynamics of the ultrafast laser-triggered spark gap.* [Author preprint](https://arxiv.org/abs/2005.14198), related DOI 10.1364/OE.398836.

**[S10] Clerici et al.** *Laser-assisted guiding of electric discharges around objects.* Science Advances 1, e1400111 (2015), DOI 10.1126/sciadv.1400111.

**[S11] Houard et al.** [Laser-guided lightning](https://www.nature.com/articles/s41566-022-01139-z). Nature Photonics 17, 231–235 (2023).

**[S12] Savage and Stoltzfus.** *High reliability low jitter 80 kV pulse generator.* Physical Review ST Accel. Beams 12, 080401 (2009), DOI 10.1103/PhysRevSTAB.12.080401.

Public sources were checked on 8 September 2026. This was a targeted decision review, not a systematic literature or patent search. The originality of the final assignment must be checked against the precisely selected hypothesis and operating regime.


