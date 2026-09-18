---
{"dg-publish":true,"permalink":"/system/research-methodology-and-workflows/","title":"Research Methodology & Workflows","tags":["topic/system/workflow","topic/ltsg/metrology"],"dgHomeLink":true,"noteIcon":"","created":"2026-09-01","updated":"2026-09-14","dg-note-properties":{"title":"Research Methodology & Workflows","aliases":["Scientific Workflow","Research Operating Manual"],"type":"guide","status":"evergreen","context":"phd","topics":["topic/system/workflow","topic/ltsg/metrology"],"tags":["topic/system/workflow","topic/ltsg/metrology"],"date":"2026-09-01","last_updated":"2026-09-14"}}
---


# Research Methodology & Workflows

Cost evidence follows the same traceability chain: record service requirements and cost inputs from WP0, freeze the operating-choice rule before testing, and distinguish measured costs from assumptions. The current scope authority is [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026\|Doctoral Progress Review & Dissertation Plan (2024–2028)]].

This is the canonical operating manual for converting literature, models and laboratory work into defensible dissertation claims. The active scientific programme is [[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028\|Core LTSG Research Programme (2026–2028)]] and the immediate priority is [[I Projects/03_Milestones/20260925 Minimum/Minimum Dissertation Study & Research Discussion 2026\|Professional Discussion: Dissertation Study & Research Plan (2026)]].

## 1. Research spine

> [!abstract] Fáze I · Rešerše a Zettelkasten (Vstup)
> 1. **[[III Resources/03_Literature/Literature Index\|Verified source]]**  
>    *Primární vědecký zdroj, bibliografické ověření DOI a archivace originálu.*  
>    📂 `III Resources/03_Literature`
> 2. **[[III Resources/03_Literature/Literature Index\|Literature note]]**  
>    *Strukturovaný výtah metody, výsledků, mezí platnosti a experimentálních nejistot.*  
>    📂 `III Resources/03_Literature (LN - ...)`
> 3. **[[II Areas/01_Research/01_MOC#Concepts\|Atomic concept or synthesis]]**  
>    *Trvalá atomická poznámka v Zettelkasten formulovaná vlastními slovy.*  
>    📂 `II Areas/01_Research/Concepts`

> [!tip] Fáze II · Formulace hypotéz a plánu (Protokol)
> 4. **[[II Areas/03_Thesis/03_MOC#Claims\|Research question and CL]]**  
>    *Formulace výzkumné otázky a provázání na claimy disertace.*  
>    📂 `II Areas/03_Thesis/Claims (CL-01 až CL-06)`
> 5. **[[I Projects/02_Campaigns/LTSG Core Research Package 2026-2028\|Frozen protocol and analysis plan]]**  
>    *Předem zmrazený experimentální protokol a predeklarovaná pravidla vyhodnocení.*  
>    📂 `I Projects/02_Campaigns`

> [!example] Fáze III · Laboratorní verifikace a QC (Měření)
> 6. **[[II Areas/01_Research/Experiments/Evidence Index\|Calibration and experiment]]**  
>    *Měřicí kampaň na LTSG aparatuře s ověřenou kalibrací a bezpečnostními zámky.*  
>    📂 `II Areas/01_Research/Experiments`
> 7. **[[II Areas/01_Research/Experiments/Evidence Index#Dataset Manifests\|Immutable dataset manifest]]**  
>    *Neměnná laboratorní data, časové značky a kryptografické kontrolní součty.*  
>    📂 `II Areas/01_Research/Experiments/Dataset Manifests`
> 8. **[[II Areas/01_Research/Experiments/Evidence Index#Analysis Records\|QC and analysis record]]**  
>    *Strukturální kontrola kvality dat a reprodukovatelné analytické skripty.*  
>    📂 `II Areas/01_Research/Experiments/Analysis Records`
> 9. **[[II Areas/01_Research/Experiments/Evidence Index\|Independent repetition]]**  
>    *Nezávislá replikace v jiné měřicí sérii nebo po výměně/servisu elektrod.*  
>    📂 `II Areas/01_Research/Experiments`

> [!check] Fáze IV · Syntéza a obhajoba (Výstup)
> 10. **[[II Areas/03_Thesis/Claim_Ledger/Claim Ledger & Evidence Matrix\|Claim decision]]**  
>     *Vyhodnocení stavu hypotézy v Claim Ledgeru (Supported / Falsified / Bounded).*  
>     📂 `II Areas/03_Thesis/Claim_Ledger`
> 11. **[[I Projects/01_Manuscripts/Dissertation Manuscript\|Manuscript and thesis chapter]]**  
>     *Začlenění podloženého výsledku do recenzovaného článku a kapitol disertace.*  
>     📂 `I Projects/01_Manuscripts`

No arrow may be skipped for a principal dissertation claim.

## 2. Canonical research question

The long-term goal of the research programme is to contribute to technically and economically viable high-voltage equipment without SF₆. The selected dissertation is **Tier 1: atmospheric-air metrology, stochastic prediction and mandatory bounded TCO**, with **submission targeted for August 2028**. Tier 2 (CO₂/pressure transfer) and Tier 3 (applications) are separately resourced follow-on research, outside mandatory completion and its publication requirements. Full replacement of SF₆ is the programme's direction, not a demonstrated result or a dissertation completion condition.

Working authority: [[I Projects/03_Milestones/20260925 Minimum/Doctoral Progress Review and Research Plan for Professional Discussion 2026\|Doctoral Progress Review & Dissertation Plan (2024–2028)]], revised 14 September 2026. This records the candidate's planning choice; formal supervisor, committee and ISP/KOS approval remains separately evidenced.

Can measurements of a laser-created channel improve prediction of breakdown probability and timing in atmospheric air, and support selection of the least-cost operating conditions that satisfy a predefined technical requirement?

| Contribution | Evidence and role |
| --- | --- |
| C1 | Reproducible atmospheric operating domain; probability and calibrated timing; H1, P1 and supporting P2 |
| C2 | Independent comparison of M0 and channel-informed M1; H2 and H4 |
| C3 | Mandatory bounded TCO and technically feasible operating choice; P3 |
| C4 | Traceable data, calibrations, analysis, uncertainty and reproducibility across all claims |

H3 is supporting robustness within the frozen atmospheric configuration family. C5 and C6 belong only to follow-on Tier 2. A null result must be accompanied by adequate sensitivity and a quantitative limit; it does not automatically guarantee degree sufficiency.

## 3. Literature workflow

1. Verify bibliographic metadata and attach or locate the primary source.
2. Create one literature note containing methods, sample size, findings, assumptions and limits of transfer.
3. Extract an atomic concept only when it is written in the researcher's own words and linked to its sources.
4. Link the source to every CL it supports or constrains.
5. Never copy an external numerical result into a claim without its experimental conditions and uncertainty.

## 4. Protocol workflow

Before confirmatory data collection:

- assign a stable protocol ID and version;
- define primary and secondary outcomes;
- define the laser time origin, breakdown marker and trigger gate;
- predeclare failed-shot and censoring rules;
- define the practically relevant effect and uncertainty requirement;
- freeze factor ranges, randomisation, blocking and stopping rules;
- link the protocol to CL, calibration records and safety approval.

A post-freeze change creates a new protocol version and a decision record. Existing data retain the original protocol reference.

## 5. Experimental workflow

### Before a session

- verify safety, interlocks and equipment availability;
- confirm active protocol and calibration validity;
- allocate experiment and dataset IDs;
- record geometry, polarity, pressure, temperature, humidity and electrode history;
- run the four-state noise/pickup control where relevant.

### During a session

- generate an immutable shot ID for every commanded shot, including failures;
- preserve raw waveforms before filtering;
- record measured laser variables rather than nominal settings;
- flag saturation, missing channels and operator deviations immediately;
- do not delete failed or inconvenient shots.

### Within 24 hours

- complete the experiment note and dataset manifest;
- copy data to controlled storage and record checksum/version;
- run structural QC and create a QC report;
- record deviations without changing the protocol retroactively;
- update the linked project task, but do not promote the CL yet.

## 6. Analysis workflow

1. Freeze the dataset and record its identifier.
2. Execute the predeclared primary analysis first.
3. Treat non-breakdowns as censored outcomes where appropriate.
4. Report effect sizes, intervals and predictive calibration, not only p-values.
5. Separate exploratory plots from confirmatory results.
6. Link figures and tables to an analysis ID, code commit and dataset freeze.
7. Repeat the main result in another session or after an electrode-service boundary.

For model claims, keep calibration and validation conditions physically separated. Report prediction intervals and failure regions rather than only best-fit curves.

## 7. Claim promotion rules

| Claim state | Required evidence |
| --- | --- |
| Hypothesis | Testable statement, outcome and falsification rule |
| In progress | Frozen protocol and active evidence collection |
| Supported | QC-passed primary data, uncertainty criterion and independent repetition |
| Falsified/bounded | Null or contradictory result reported with a quantitative bound |
| Published | Claim appears in an accepted/published output with traceable evidence |

A literature-supported statement is not evidence that the same effect occurs on the present apparatus.

## 8. Writing and publication workflow

- Write methods while the protocol is being built.
- Create empty figure shells before confirmatory acquisition.
- Update the dissertation continuously; do not postpone Chapters 1-3 until the end.
- Every manuscript result links back to a CL and analysis record.
- Every thesis claim links forward to a manuscript or is explicitly identified as unpublished evidence.
- Journal selection follows the final contribution and audience; quartile and scope are rechecked at submission.

## 9. Operating cadence

### Daily

- identify one principal research outcome;
- record decisions and deviations in the daily note;
- process experiment metadata before leaving the session.

### Weekly — 45 minutes

- empty or defer Inbox items;
- update next actions and blockers for every active project;
- inspect evidence states and unresolved QC;
- write at least one dissertation subsection or figure narrative;
- check the next 30-day deadlines.

### Monthly — supervisor evidence review

- review the CL dashboard;
- approve or reject scope changes;
- review the publication critical path;
- record decisions in a supervisor meeting note;
- confirm laboratory access and administrative milestones.

### At every gate

- decide continue, redesign or narrow;
- preserve negative results;
- prevent optional extensions from delaying the core package.

## 10. Definition of done

The core evidence package is complete when:

- a reproducible self-breakdown baseline defines the working coefficient;
- laser/channel variables are measured with uncertainty;
- one compact confirmatory experiment is completed with censored outcomes retained;
- the principal result is independently repeated;
- the reduced model is evaluated on untouched conditions;
- H1, P1, H2, H4 and P2 are supported or quantitatively bounded;
- P3 provides a bounded TCO/feasibility decision with traceable assumptions and sensitivity;
- the evidence is incorporated into the two planned core manuscripts and thesis Chapters 3–6;
- no Tier 2/3 outcome is needed to close this evidence package.

## Related system notes

- [[_System/PhD Vault Architecture Guide\|PhD Vault Architecture Guide]]
- [[_System/Tags and Linking Convention\|Tags and Linking Convention]]
- [[_System/Digital Garden & Vercel Deployment Guide\|Digital Garden & Vercel Deployment Guide]]

