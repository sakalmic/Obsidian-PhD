---
title: RESEARCH-00 - Atmospheric Tier 1 workflow 2026-2028
aliases:
  - Atmospheric Tier 1 workflow
type: research-ticket
status: planned
parent_project: LTSG-Core
scope: mandatory-tier-1
created: 2026-09-16
last_updated: 2026-09-16
dg-publish: true
---

# RESEARCH-00 — Atmospheric Tier 1 workflow, 2026–2028

For the concise two-level schedule, start with [[II Areas/01_Research/Research Plans/RESEARCH-01 - Dissertation Research Roadmap|RESEARCH-01 - Dissertation Research Roadmap]]. This ticket retains the detailed experiment–theory handoffs and completion rules.

## Decision and boundary

**Objective:** produce a defensible atmospheric-air dissertation that links calibrated breakdown measurements, a constrained physical interpretation, independently validated stochastic prediction and a bounded techno-economic operating choice. The working target is **submission in August 2028**. Tier 2 (CO₂/pressure) and Tier 3 (applications or online control) are outside mandatory completion. The long-term SF₆ replacement objective motivates the programme but is not an achieved Tier 1 result.

**Authority:** [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026|Current reviewer report]]. This ticket translates that plan into tasks; laboratory access, equipment availability, formal study approval and numerical performance requirements still need confirmation.

## Linked laboratory tickets

| Order and target period | Ticket | Required handoff |
| --- | --- | --- |
| 0 · Sep–Dec 2026 | [[II Areas/01_Research/Research Plans/LAB-00 - Apparatus and Timing Readiness|Apparatus and timing readiness]] | Approved configuration, calibrated measurement chain, shot schema, safe operating procedure and cost-log boundary. |
| 1 · Jan–Feb 2027 | [[II Areas/01_Research/Research Plans/LAB-01 - Atmospheric No-Laser Baseline|No-laser baseline]] | Contemporary $U_{50}$ estimate, uncertainty and session/electrode history. |
| 2 · Mar–Apr 2027 | [[II Areas/01_Research/Research Plans/LAB-02 - Laser and Channel Diagnostic Pilot|Laser and channel pilot]] | Measured optical inputs and one interpretable shot-linked channel descriptor, or a documented diagnostic limit. |
| 3 · May–Jun 2027 | [[II Areas/01_Research/Research Plans/LAB-03 - Screening and June Decision Gate|Screening and June gate]] | Small confirmatory matrix, precision-based attempt count, frozen analysis and explicit stop/go decision. |
| 4 · Jul–Oct 2027 | [[II Areas/01_Research/Research Plans/LAB-04 - Atmospheric Confirmatory Campaign|Atmospheric confirmation]] | QC-passed, shot-level dataset including failures and an independent realignment/session repeat. |
| 5 · Nov 2027–Feb 2028 | [[II Areas/01_Research/Research Plans/LAB-05 - Independent Prediction and Operating-Choice Check|Independent prediction and choice check]] | Untouched-session test of frozen M0/M1 and technical feasibility of a preselected operating choice. |

Ticket dates are planning windows, not booked beam time. Each laboratory ticket must link its protocol version, calibration records, dataset manifest and QC/analysis record before being marked complete. Keep private apparatus details and raw storage locations in internal records, not public notes.

## Parallel theoretical and analytical work

| Period | Theory / analysis task | Output and decision |
| --- | --- | --- |
| WP0, Sep–Dec 2026 | Define physical observables, breakdown marker, optical time zero, observation window, failed-shot codes and the reference operating service. Audit historical provenance and timing calibration. | Measurement specification, uncertainty budget and frozen distinction between historical evidence and new data. See [[II Areas/01_Research/Experiments/Calibrations/HiLASE Trigger-to-Optical Timing - Verification Plan\|HiLASE Trigger-to-Optical Timing - Verification Plan]]. |
| WP1, Jan–Feb 2027 | Calculate the electrostatic field for the actual measured geometry and voltage; record boundary conditions and mesh sensitivity. Do not interpret a static field map as proof of breakdown. | Reproducible field map and local-field descriptors, with uncertainty in geometry and voltage. |
| WP2–WP3, Mar–Jun 2027 | Propose the smallest time-evolving channel state that optical/electrical diagnostics can constrain. Compare charge-loss and gas-density timescales without claiming an optical proxy is direct electron density. Define M0 using pre-shot settings and M1 adding a predeclared pre-breakdown channel descriptor. | Explicit reduced-model equations/assumptions, identifiable parameter list and June decision on whether the state is measurable. |
| WP4, Jul–Oct 2027 | Fit baseline probability/delay responses using training sessions only; include right-censored no-breakdown attempts and session effects. Prepare Paper 1 from the new confirmatory measurement question. | Reproducible analysis pipeline and a frozen validation plan. |
| WP5, Nov 2027–Feb 2028 | Compare M0 and M1 on complete held-out sessions. Assess calibration, proper scoring, predicted time probabilities/quantiles, sensitivity and failure regions. A post-laser channel descriptor cannot choose the energy of the same pulse. | Independent predictive result; report no improvement when M1 fails. |
| WP6, collect from WP0 and integrate Mar–Apr 2028 | Define technically admissible configurations using the validation result. For a pre-trigger choice, average over the configuration-dependent distribution of any post-laser descriptor. Compute bounded TCO, cost per compliant operation, scenario sensitivity and break-even boundaries. | Constrained operating choice or a documented lack of feasible/stable choice; Paper 2. See [[II Areas/03_Thesis/Claims/P3 - Techno-economic operating choice\|P3 - Techno-economic operating choice]]. |
| WP7, continuous to Aug 2028 | Write methods and limits during acquisition; complete a full draft by June 2028 and check publication/study eligibility. | Dissertation submission target: August 2028. |

## Model boundary and optional upgrade

The mandatory model is **field calculation → measurement-constrained channel description → stochastic probability/delay prediction → independent validation**. It describes how measured channel state changes breakdown risk over time, but does not promise a spatial movie of every streamer or the completed arc. Time-resolved imaging or interferometry may support a bounded 2D mechanism study only if available early, synchronised to the same shot and independently comparable with the simulation. Full 3D plasma chemistry is not a completion requirement. See [[II Areas/03_Thesis/Claims/H4 - Reduced predictive model|H4 - Reduced predictive model]] and [[II Areas/01_Research/Simulations/COMSOL Multiphysics Setups|COMSOL Multiphysics Setups]].

The model specification should make the following sequence testable:

1. Calculate $\mathbf E=-\nabla\phi$ for the measured electrode boundary, voltage and geometry; report mesh/boundary sensitivity. This gives a field input, not a simulated breakdown event.
2. Define an observed channel feature $y(t)$ and, only if identifiable, a reduced state $z(t)$ with $\dot z=f(z,\mathbf E,L;\theta)$ and an observation relation $y=h(z)+\epsilon$. Candidate processes such as charge loss or gas-density evolution must be compared against the actual time resolution. If $h$ cannot be calibrated, retain $y$ as an empirical proxy and do not label it electron density.
3. Link the measured inputs/state to a probability or time-to-event model: $S(t\mid x,z)=\exp[-\int_0^t\lambda(u\mid x,z(u))\,du]$, with no-breakdown attempts right-censored at the declared observation limit. M0 omits $z/y$; M1 includes the predeclared observed feature. This is one proposed reduced structure, to be accepted only if identifiable and independently predictive.
4. Compare simulated or inferred time courses with **separate** optical/electrical observables, then score M0/M1 on complete held-out sessions. Sensitivity to fitted parameters and failure regions are deliverables. A visual resemblance to an image is not sufficient validation.

If the project aims to resolve the location and propagation of a streamer front rather than the time-varying breakdown risk, it requires a separate diagnostic and numerical subproject with spatially and temporally resolved observables. Do not add it to the mandatory calendar at the expense of confirmation, TCO or writing. Physical background: [Nijdam, Teunissen and Ebert, 2020](https://doi.org/10.1088/1361-6595/abaa05); an example of experimental/model comparison is [Li et al., 2021](https://doi.org/10.1088/1361-6595/ac1b36), in a different geometry and pressure regime.

## Shared evidence rules

- One attempted shot is a declared trigger request in the ready state. Record it even if no optical pulse or no electrical breakdown follows; classify causes with frozen codes.
- Use calibrated optical arrival at the gap as physical time zero and a predeclared electrical breakdown criterion. Record the old electrical trigger too, so its relationship to optical arrival can be checked.
- Hold out complete measurement sessions, not randomly selected adjacent shots. Freeze preprocessing, model selection, sample-size rule and operating-choice rule before independent validation.
- The number of attempts follows pilot precision/power and session variability. Do not promote the historical count of series or an unsupported fixed shot target into a sample-size justification.
- Separate measured inputs, literature parameters and fitted quantities. Report uncertainty and non-identifiability; avoid post-breakdown information leakage into predictors.
- TCO is for a defined laboratory switching service and explicit ownership scenarios. Do not count avoided grid outages, asset-life extension or SF₆ replacement as observed savings.

## Completion check

- [ ] LAB-00 through LAB-05 have documented outputs or explicit limits and supervisor-reviewed scope decisions.
- [ ] Field map, reduced-model specification, parameter/uncertainty table and held-out M0/M1 comparison are reproducible.
- [ ] Paper 1 and Paper 2 questions, data reuse and submission/acceptance status are reported accurately.
- [ ] Bounded TCO and the operating-choice rule use independent performance evidence.
- [ ] Full draft and official study/publication eligibility are checked before the August 2028 submission target.
