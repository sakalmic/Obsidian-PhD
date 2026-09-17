---
title: "Laser-Induced Plasma Dynamics"
aliases:
  - Laser-Induced Plasma Dynamics
type: synthesis
status: evergreen
context: research
topics:
  - topic/ltsg/channel
tags:
  - topic/ltsg/channel
date: 2026-09-01
last_updated: "2026-09-14"
dg-publish: true
dg-home-link: true
---

# Laser-Induced Plasma Dynamics

## Overview
Laser-induced breakdown (LIB) is a nonlinear, probabilistic optical-plasma process. Depending on pulse duration, wavelength, focal geometry and gas state, seed electrons can arise through multiphoton/tunnelling processes, impurities or aerosols; subsequent impact ionisation, attachment, recombination, diffusion and heating determine whether a useful channel survives. A single universal intensity threshold is therefore inappropriate. Thresholds must be tied to a probability definition and a measured optical setup.

---

## Key stages of plasma evolution
1. **Optical excitation and seed formation** (fs-ns): strongly nonlinear ionisation and initial energy deposition.
2. **Electron kinetics** (ns-tens of ns): avalanche growth competes with attachment, recombination and diffusion.
3. **Gas response** (tens of ns-µs): acoustic/shock expansion and a reduced-density channel can persist after most free electrons disappear.
4. **Field-driven discharge formation** (ns-µs): space charge, streamer propagation and possibly leader-like heating bridge the gap.
5. **Arc/circuit phase** (µs and longer): plasma impedance and the external RLC circuit determine voltage collapse, current and deposited energy.

The times are regime-dependent and must be measured for the present apparatus. Rosenthal et al. showed experimentally that, for femtosecond excitation, the evolving density depression can dominate the path toward breakdown even when the initial plasma differs.

## Minimal governing equations

The working model combines electron balance, drift-diffusion, Poisson's equation and reduced gas heating/density evolution. See [[Theory - Laser-Triggered Breakdown and Switching#4. Electron balance and reduced electric field]] for equations, assumptions and model tiers.

The model chain is decomposed into permanent notes:

1. [[II Areas/01_Research/Concepts/202609031120 - Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions|Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions]]
2. [[II Areas/01_Research/Concepts/202609031100 - Keldysh Parameter Separates Strong-Field Ionization Regimes|Keldysh Parameter Separates Strong-Field Ionization Regimes]] and [[II Areas/01_Research/Concepts/202609031110 - Avalanche Ionization Can Dominate Nanosecond Breakdown|Avalanche Ionization Can Dominate Nanosecond Breakdown]]
3. [[II Areas/01_Research/Concepts/202609031000 - Reduced Electric Field Governs Electron Kinetics|Reduced Electric Field Governs Electron Kinetics]] and [[II Areas/01_Research/Concepts/202609031010 - Electron Energy Distribution Determines Transport Coefficients|Electron Energy Distribution Determines Transport Coefficients]]
4. [[II Areas/01_Research/Concepts/202609031050 - Electron Attachment Recombination and Diffusion Erase Plasma Memory|Electron Attachment Recombination and Diffusion Erase Plasma Memory]]
5. [[II Areas/01_Research/Concepts/202609031140 - Hydrodynamic Density Depression Creates Electrical Memory|Hydrodynamic Density Depression Creates Electrical Memory]]
6. [[II Areas/01_Research/Concepts/202609031030 - Space Charge Marks the Avalanche to Streamer Transition|Space Charge Marks the Avalanche to Streamer Transition]]

## Measurement consequences

- Measure pulse energy, duration and waist rather than relying on nominal intensity.
- Use $E/N$ and measured atmosphere variables when comparing runs.
- Distinguish visible emission, electrical conduction and a reduced-density channel.
- Treat failed triggers and long-delay events as physical data.
- Separate channel physics from the transfer response of the external circuit.

---

## Connections

- **Up:** [[Theory - Laser-Triggered Breakdown and Switching]]
- **Side:** [[Diagnostics - Timing EMP and Radiation]]
- **Down:** [[Laser-Triggered Spark Gaps (LTSG)]] · [[H2 - Channel state versus pulse energy]]
