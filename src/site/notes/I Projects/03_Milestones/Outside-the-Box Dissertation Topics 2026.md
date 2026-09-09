---
title: "Outside-the-Box Dissertation Topics 2026"
aliases:
  - Emerging Dissertation Topics
  - Commercial Dissertation Opportunities
type: decision-support
status: proposal
context: thesis
topics:
  - topic/ltsg/application
  - topic/ltsg/breakdown
  - topic/ltsg/economics
tags:
  - topic/ltsg/application
  - topic/ltsg/breakdown
  - topic/ltsg/economics
date: 2026-09-09
last_updated: 2026-09-09
dg-publish: true
dg-home-link: true
permalink: /outside-the-box-dissertation-topics-2026/
---

# Outside-the-Box Dissertation Topics 2026

> [!info] Document status
> This is a public opportunity scan for supervisor discussion. It does not constitute an approved dissertation assignment, a laboratory reservation, a commercial forecast, or a patent-freedom opinion. The lower-risk continuation options are assessed in [[Variant Dissertation Topics 2026]].

## Why look beyond the original assignment

The master’s thesis established a useful experimental platform for laser-assisted high-voltage breakdown. A dissertation can remain close to that platform while addressing a market transition, a measurable engineering bottleneck, or a high-risk physical question. The best topic should combine a defensible scientific hypothesis with equipment that can realistically be obtained and a result that a manufacturer, laboratory, or infrastructure operator could evaluate.

The most immediate external driver is the European phase-down of fluorinated greenhouse gases. Regulation (EU) 2024/573 introduces staged restrictions on new switchgear using fluorinated gases. Relevant dates include 2026 for equipment up to 24 kV, 2028 for parts of the 52–145 kV range, 2030 for 24–52 kV, and 2032 for higher-voltage classes, subject to the regulation’s exact conditions and exceptions. From 2035, SF6 used for maintenance is also increasingly restricted to reclaimed or recycled gas. This creates demand for qualification, monitoring, and lifetime evidence for vacuum and alternative-gas equipment. [O1]

Commercial systems already use different technology paths. Siemens Energy markets vacuum interruption with clean-air insulation up to 145 kV, while Hitachi Energy’s 420 kV EconiQ GIS uses a fluoronitrile/CO2/O2 mixture. These examples show that “SF6 replacement” is not one material question: the research opportunity lies in diagnostics, breakdown control, recovery, by-products, ageing, and validation across competing architectures. [O2, O3]

## Opportunity comparison

| ID | Direction | Continuity with current work | Commercial potential | Scientific risk | Capital demand | Recommended role |
| --- | --- | :---: | :---: | :---: | :---: | --- |
| O1 | Optical condition diagnostics for SF6-free switchgear | High | Very high | Medium | Medium | Best commercial branch |
| O2 | Breakdown and dielectric recovery in fluorine-free media | Very high | High | Medium-high | Medium-high | Best physics/engineering branch |
| O3 | Probabilistic digital twin for eco-efficient switchgear | High | High | Medium | Medium | Strong data/model branch |
| O4 | Optically isolated hybrid crowbar | High | Medium-high | Medium | Medium | Fastest demonstrator |
| O5 | Photonic synchronisation of multiple spark gaps | High | Medium | Medium-high | Medium-high | Pulsed-power niche |
| O6 | Laser-guided lightning attachment | Medium | Potentially high | Very high | Very high | Collaboration-dependent |
| O7 | Long-lived luminous structures inspired by ball lightning | Medium | Uncertain | Extreme | Medium-high | Time-boxed moonshot |
| O8 | Laser-plasma ignition of hydrogen and ammonia | Medium | High | High | High | Energy-transition branch |

## O1 — Optical condition diagnostics for SF6-free switchgear

### Working title

**Optical and Electrical Precursors of Breakdown in Fluorine-Free High-Voltage Insulation Systems**

### Research question

Can non-contact optical signals detect changes in discharge mode, contamination, surface condition, or insulation margin before a fluorine-free switchgear compartment reaches unacceptable breakdown risk?

### Minimum doctoral contribution

- identify optical or combined optical/electrical descriptors that change before breakdown;
- distinguish useful precursors from environmental and sensor drift;
- build a probabilistic condition indicator with uncertainty and false-alarm analysis;
- validate it on operating conditions not used for model fitting;
- state clearly which gas, geometry, pressure, and voltage range the indicator covers.

### Equipment and demonstrator

A sealed, pressure-rated test chamber; dry-air/CO2/N2/O2 handling; representative electrode and spacer samples; high-voltage source; emission spectroscopy or selected optical bands; fast imaging or photodetection; current/voltage diagnostics; temperature, pressure, and humidity sensors; and controlled contamination or surface-conditioning protocols. A commercially legible demonstrator would classify healthy, conditioned, contaminated, and pre-breakdown states without galvanic contact to the high-voltage compartment.

### Commercial route

The most realistic product is a diagnostic module or qualification method for manufacturers, service organisations, and test laboratories. The value proposition is earlier fault detection, lower commissioning uncertainty, and condition-based maintenance. A partnership with a switchgear producer would greatly improve access to representative geometries and failure modes.

### Decision gate

Continue only if a repeatable optical descriptor separates at least two physically meaningful states after controlling for pressure, temperature, sensor alignment, and electrode history. Otherwise narrow the thesis to metrology and physics rather than predictive maintenance.

## O2 — Breakdown and dielectric recovery in fluorine-free media

### Working title

**Laser-Assisted Breakdown and Dielectric Recovery in Fluorine-Free Gas Mixtures for High-Voltage Switching**

### Research question

How do gas composition, density, laser-created channel state, and deposited discharge energy determine breakdown probability, delay, and post-discharge dielectric recovery in clean air, CO2, N2/O2, or another justified fluorine-free medium?

### Contribution and scope control

This is the strongest direct extension of the present spark-gap work. The dissertation should compare a small number of deliberately selected media rather than screen many mixtures. Its original contribution should be a reduced, validated relationship linking channel diagnostics, breakdown dynamics, and recovery. It must avoid implying direct replacement of an industrial circuit breaker unless current interruption and recovery under representative transient voltage are actually tested.

### Equipment and demonstrator

The setup needs a sealed pressure-capable chamber, certified gas handling and leak testing, interchangeable electrodes, high-voltage and fast timing diagnostics, optical channel measurements, and a two-pulse or controlled recovery test. The demonstrator could provide a comparative qualification protocol or a trigger/recovery map for a selected fluorine-free medium.

### Commercial route

Potential users include switchgear developers, high-voltage test houses, gas-mixture suppliers, and pulsed-power laboratories. The near-term deliverable is measurement methodology and design data; a production switching device would require substantial additional qualification.

### Decision gate

By the end of the pilot, the chamber must be leak-tight and safe, gas composition and density traceable, and at least one non-air medium must show a measurable and repeatable difference in breakdown or recovery. Otherwise retain air as the defensible baseline.

## O3 — Probabilistic digital twin for eco-efficient switchgear

### Working title

**A Physics-Informed Probabilistic Digital Twin for Breakdown Risk and Maintenance of SF6-Free Switchgear**

### Research question

Can a reduced physics model updated by sparse optical and electrical measurements predict insulation margin, failure probability, or maintenance need better than fixed thresholds?

### Doctoral contribution

The contribution would integrate a reduced breakdown/recovery model, uncertainty propagation, sensor evidence, and held-out validation. The term “digital twin” should be used only if the model is updated with observations from a physical asset or representative test object. A static COMSOL model alone is not a digital twin.

### Equipment and commercial route

The topic uses the O1/O2 test platform plus repeatable metadata and model infrastructure. It is attractive as a software and diagnostics layer that can be licensed or integrated into asset-management systems. It also allows progress when access to a large industrial prototype is intermittent, provided the experimental evidence remains sufficient.

### Decision gate

Continue only if the model improves calibrated probability or decision performance on held-out data and its uncertainty changes rationally with new evidence. If not, report a reduced engineering model without the digital-twin label.

## O4 — Optically isolated hybrid crowbar

### Working title

**An Optically Triggered Hybrid Crowbar for Fast Protection of High-Voltage Pulsed Systems**

### Research question

Can a laser-triggered gap provide galvanic isolation and robust fast activation while a complementary solid-state or passive branch limits energy, recovery stress, and component wear?

### Contribution, equipment, and demonstrator

The thesis would co-design the plasma switch and external circuit, measure delay/jitter and transferred energy, and compare the hybrid system with a purely electrical trigger for the same protection function. Required additions are a representative protected load, calibrated current/voltage measurements, energy-limiting components, and a safe fault-injection protocol. This is the fastest route to a visible functional demonstrator because it uses the spark gap as one component of a bounded protection problem.

### Commercial route and gate

Applications include capacitor-bank protection, pulsed lasers, accelerators, and specialised power supplies. Continue after the first year only if the hybrid system demonstrates a quantified advantage in isolation, timing, fault energy, or survivability. A visually successful discharge is insufficient.

## O5 — Photonic synchronisation of multiple spark gaps

### Working title

**Photonic Distribution and Relative-Jitter Control in Multi-Gap Pulsed-Power Switching**

### Research question

Can one optical source distribute a common trigger to several gaps with lower relative jitter and electromagnetic susceptibility than electrical triggering?

The contribution would separate optical-distribution imbalance, common-mode laser variation, and gap-specific stochastic delay. The demonstrator could operate two or more coordinated discharge channels or stages of a compact pulse generator. Required equipment includes optical splitting and energy monitoring, independently instrumented gaps, multi-channel acquisition, and a circuit in which synchronisation has a measurable functional consequence.

The commercial market is specialised but credible: pulsed-power systems, accelerators, intense radiation sources, and electromagnetic compatibility test equipment. Scalability beyond two gaps must be analysed rather than assumed.

## O6 — Laser control of lightning attachment

### Working title

**Laser-Induced Control of Leader Inception and Attachment to Protected Infrastructure**

### Current question

The 2023 Säntis experiment demonstrated that a high-repetition-rate laser filament could guide a lightning leader over approximately 50 m. The unresolved engineering questions concern repeatability, weather envelope, energy and alignment cost, attachment-point control, and integration with conventional protection. [O5]

### Realistic doctoral scope

A local thesis should not promise a full outdoor lightning-control system without an established collaboration and facility. A defensible contribution could investigate scaled leader inception, channel persistence, optical diagnostics, or attachment to a representative electrode geometry. Outdoor validation should be a partner-dependent extension.

### Commercial route and risk

Possible users include operators of launch sites, airports, wind farms, high structures, and sensitive industrial infrastructure. The capital and regulatory barriers are extreme, and conventional lightning rods are inexpensive. Commercial value therefore depends on a clearly defined case in which controlled attachment provides a benefit unavailable from passive protection.

## O7 — Long-lived luminous structures inspired by ball lightning

### Working title

**Reproducible Long-Lived Luminous Plasma–Aerosol Structures after Pulsed Electrical Discharge**

### Scientific formulation

The thesis should not be framed as “creating ball lightning”. Natural ball lightning lacks a settled mechanism, and laboratory reports often involve hot particles, combustion, surface ablation, or short-lived plasma chemistry rather than a unique phenomenon. A scientific topic should instead define measurable lifetime, spectrum, energy balance, motion, composition, and reproducibility.

Natural-event spectroscopy reported emission associated with soil elements, while a laboratory study produced luminous ball-like objects through discharges into silicon. These observations motivate hypotheses involving aerosol oxidation and stored chemical energy, but they do not establish a universal model of ball lightning. [O6, O7]

### Equipment and evidence

The pilot would require a shielded discharge chamber, fast and time-integrated spectroscopy, high-speed imaging, thermal diagnostics, aerosol/particle collection, mass or surface analysis, and a rigorous energy balance. Controls must distinguish afterglow, burning electrode material, camera saturation, and reflections.

### Commercial potential

Direct commercial demand for ball lightning is weak. Useful spillovers could include plasma ignition, nanoparticle synthesis, reactive-aerosol chemistry, decontamination, combustion diagnostics, or persistent optical markers. These applications should be treated as hypotheses until a controllable structure and transferable mechanism exist.

### Decision gate

Limit the initial study to three months. Continue only if the phenomenon is reproducible, lives substantially longer than the excitation pulse, has a measured spectrum and energy source, and can be controlled through at least one independent parameter. Otherwise archive it as a documented negative pilot without affecting the dissertation core.

## O8 — Laser-plasma ignition of hydrogen and ammonia

### Working title

**Laser-Plasma Ignition and Stability Control of Hydrogen–Ammonia Energy Mixtures**

### Current question and continuity

Hydrogen and ammonia can support low-carbon energy systems but present ignition, flame-speed, emissions, and safety challenges. Recent engine studies continue to examine how hydrogen enrichment improves ammonia combustion. The present expertise in laser-created channels, timing, breakdown probability, and optical diagnostics could transfer to non-contact ignition and ignition-stability measurements. [O8]

### Contribution and equipment

The thesis would quantify ignition probability, delay, energy threshold, kernel development, and operating stability for a tightly selected mixture range. It would require a certified combustion vessel, gas handling and detection, pressure measurement, optical access, high-speed imaging, emissions analysis, and a separate safety programme. This is a substantial infrastructure change from the current spark-gap apparatus.

### Commercial route and gate

Potential applications include engines, turbines, industrial burners, and research combustors. Continue only with a combustion partner, approved facility, and a demonstrated laser-ignition effect that is not reproduced by a simpler electrical igniter at equivalent function and cost.

## Recommended order for supervisor discussion

### 1. Best new commercial branch: O1

Optical condition diagnostics for SF6-free switchgear addresses an immediate regulatory and industrial transition. It preserves the project’s strengths in optical diagnostics and stochastic breakdown while producing a component or method that an industrial partner can evaluate.

### 2. Best physics and engineering branch: O2

Breakdown and recovery in fluorine-free media offers the strongest continuity with the present apparatus and can generate fundamental as well as application-oriented results. Its feasibility depends mainly on a suitable sealed chamber and gas-handling capability.

### 3. Fastest route to a demonstrator: O4

The hybrid crowbar turns the current spark gap into a bounded system function and allows fair before/after metrics. It is a strong choice if a visible demonstrator and power-engineering narrative are priorities.

### 4. Moonshot: O7

The ball-lightning-inspired topic is scientifically intriguing but commercially weak and highly uncertain. It should remain a short gated pilot or a side collaboration, not the default dissertation core.

## Recommended combined topic

**Laser-Assisted Diagnostics of Breakdown and Dielectric Recovery in Fluorine-Free Insulating Media for High-Voltage Equipment**

The combined topic would aim to deliver five contributions:

1. a traceable protocol for breakdown probability, delay, jitter, and recovery in selected fluorine-free media;
2. optical descriptors of the channel and pre-breakdown state;
3. a reduced probabilistic model validated on held-out conditions;
4. a diagnostic or qualification demonstrator relevant to SF6-free equipment;
5. design and monitoring rules with explicit pressure, geometry, voltage, and uncertainty limits.

The core should compare air with one industrially justified medium or mixture. If a pressure-rated chamber or industrial partner is unavailable by the first major gate, the fallback is the air-based channel-state topic in [[Variant Dissertation Topics 2026]], preserving the metrology and modelling work.

## Sources and assessment boundaries

**[O1] European Union.** [Regulation (EU) 2024/573 on fluorinated greenhouse gases](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A02024R0573-20240220), particularly Article 13 and Annex IV.

**[O2] Siemens Energy.** [Blue high-voltage products](https://www.siemens-energy.com/global/en/home/products-services/product-offerings/blue-high-voltage-products.html): vacuum interruption and clean-air insulation product information.

**[O3] Hitachi Energy.** [EconiQ GIS ELK-3, 420 kV](https://www.hitachienergy.com/us/en/products-and-solutions/high-voltage-switchgear-and-breakers/gas-insulated-switchgear/gis-for-72-5-1200-kv/econiq-gis-elk-3-420-kv): fluoronitrile/CO2/O2 product information.

**[O4] IEEE Xplore.** [2026 study of arc-decomposition characteristics of C4F7N/CO2 in a 12 kV ring-main unit](https://ieeexplore.ieee.org/abstract/document/11510496).

**[O5] Houard et al.** [Laser-guided lightning](https://www.nature.com/articles/s41566-022-01139-z). Nature Photonics 17, 231–235 (2023).

**[O6] Cen, Yuan, and Xue.** [Observation of the optical and spectral characteristics of ball lightning](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.112.035001). Physical Review Letters 112, 035001 (2014).

**[O7] Paiva et al.** [Production of ball-lightning-like luminous balls by electrical discharges in silicon](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.048501). Physical Review Letters 98, 048501 (2007).

**[O8] Recent hydrogen–ammonia engine study.** [International Journal of Hydrogen Energy (2024)](https://doi.org/10.1016/j.ijhydene.2024.03.035).

Regulatory dates and commercial product claims were checked on 9 September 2026. Final topic selection still requires a systematic literature review, patent search, equipment inventory, safety assessment, and confirmation of industrial access.
