---
{"dg-publish":true,"dg-permalink":"/direction-c-adaptive-control-and-operational-utility/","permalink":"/direction-c-adaptive-control-and-operational-utility/","title":"C · Adaptive Switching Control","noteIcon":"","created":"2026-09-10","updated":"2026-09-11","dg-note-properties":{"title":"C · Adaptive Switching Control","aliases":["Direction C - Adaptive Control and Operational Utility","Dissertation Direction C"],"ticket_id":"DIR-C","type":"project","status":"proposal","context":"thesis","priority":"high","parent_project":"MIN-2026","direction_family":"core","decision_state":"not-selected","date":"2026-09-10","last_updated":"2026-09-11","permalink":"/direction-c-adaptive-control-and-operational-utility/"}}
---


# C · Adaptive Switching Control

> [!summary] Direction decision
> **Current state:** not selected. Review and selection are coordinated in [[I Projects/03_Milestones/20260925 Minimum/Dissertation Direction Portfolio and Winning Variant W 2026-2029\|Dissertation Research Paths & Final Choice (2026–2028, 2029)]]. Formal approval is recorded once in the central decision log.

## Purpose

Use measured pre-shot or early-time information to choose a laser or voltage setting that reaches a target switching probability while minimizing energy or delay.

## Intended doctoral contribution

A validated decision rule or controller demonstrated offline first and, only if safe, in closed loop on a defined apparatus.

## Scope

### Included

- a frozen primary question and measurable response;
- controls, uncertainty, failed/censored outcomes and independent repetition;
- one traceable dataset and analysis package;
- a paper- and chapter-level deliverable;
- explicit limits on transfer to applications.

### Excluded unless separately activated

- performance claims outside the tested voltage, geometry, medium or repetition range;
- full product qualification or field deployment;
- economic or lifetime claims without measured inputs;
- additional diagnostics that lack calibration and a declared decision role.

## Required equipment and collaboration

Option A/B diagnostics; reliable low-latency feature extraction; control interface; safe bounds and an independent watchdog.

Before work begins, confirm named equipment owners, access dates, calibration state, safety approvals and a backup route. Historical apparatus values are not proof of current availability.

## Work packages

1. **Definition and metrology:** freeze the question, primary outcome, apparatus, calibration and data structure.
2. **Baseline:** quantify the relevant no-laser/reference condition and between-session drift.
3. **Screening:** identify a compact operating region without consuming the confirmatory dataset.
4. **Confirmation:** use a predeclared sample-size rule, preserve failures and repeat the principal result independently.
5. **Model and output:** validate on untouched data, document failure regions and prepare the manuscript/thesis chapter.

## Schedule and gates

| Period | Work | Deliverable / gate |
| --- | --- | --- |
| Sep–Dec 2026 | Define target utility, constraints, safe control variables and offline evaluation protocol. | G0: approved control envelope and fail-safe concept. |
| Jan–Jun 2027 | Collect baseline and screening data; build probability and delay predictor. | G1: predictor calibrated and stable across sessions. |
| Jul–Dec 2027 | Evaluate policies offline on held-out records; quantify benefit against fixed settings. | G2: policy improves a predeclared utility without violating constraints. |
| Jan–Apr 2028 | Optional supervised closed-loop demonstrator after safety review. | D1: bounded demonstrator or offline controller paper. |
| May–Aug 2028 | Document transfer limits, safety logic and application case. | Conditional thesis chapter; core remains Option B if gate fails. |

## Technical applications

Adaptive pulsed-power triggers, automated test systems and energy-aware plasma control.

Applications are hypotheses about use, not achieved system performance. Any commercial statement must identify the system boundary, comparison baseline and evidence still missing.

## Principal risks

- apparatus or partner access is not confirmed early enough;
- measurement resolution is insufficient for the claimed effect;
- a session or electrode-state effect is confused with the intervention;
- publication timing leaves too little margin before dissertation submission;
- attractive application work displaces the minimum defensible core.

## Selection position

Higher integration risk; activate only after a stable predictive baseline.

### Activation criteria

- [ ] Supervisor and committee accept the question and contribution.
- [ ] Required apparatus and responsible collaborators are confirmed in writing.
- [ ] The primary outcome, uncertainty target and falsification route are frozen.
- [ ] The schedule protects the State Doctoral Examination and publication path.
- [ ] A fallback produces a defensible thesis result if the main hypothesis fails.

## Definition of done

The direction is complete when its core claim is supported, falsified or quantitatively bounded by QC-passed evidence, an independent repeat and a reproducible analysis; the result is incorporated into a submitted manuscript and the corresponding dissertation chapter.

## Related research

- [[I Projects/03_Milestones/20260925 Minimum/Dissertation Direction Portfolio and Winning Variant W 2026-2029\|Dissertation Research Paths & Final Choice (2026–2028, 2029)]]
- [[II Areas/03_Thesis/Claims/CL-05 - Reduced predictive model\|CL-05 · Predictive model]]
- [[II Areas/01_Research/Concepts/Techno-Economic Modeling of Grid Switching\|Techno-economic grid-switching model]]
