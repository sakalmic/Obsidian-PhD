---
title: "Keldysh Parameter Separates Strong-Field Ionization Regimes"
aliases:
  - Keldysh parameter
  - Multiphoton versus tunnelling ionisation
type: concept
status: evergreen
context: research
claims: [H2, H4]
topics:
  - topic/ltsg/channel
  - topic/ltsg/model
tags:
  - type/permanent
  - context/research
  - topic/ltsg/channel
  - topic/ltsg/model
created: 2026-09-03
last_updated: "2026-09-14"
dg-publish: true
dg-home-link: true
---

# Keldysh Parameter Separates Strong-Field Ionization Regimes

## Core atomic concept

The Keldysh parameter compares the laser frequency with the characteristic tunnelling frequency and indicates whether strong-field seed ionisation is more multiphoton-like or tunnelling-like. It classifies the **initial optical ionisation mechanism**, not the complete gas-breakdown process.

## Mathematical formulation

$$
\gamma_K=\frac{\omega\sqrt{2m_eU_i}}{eE_L},
$$

where $U_i$ is ionisation potential and $E_L$ is optical electric-field amplitude. Since

$$I=\frac{1}{2}n\epsilon_0cE_L^2,$$

$\gamma_K$ can be estimated from measured intensity. The limits are approximately

- $\gamma_K\gg1$: perturbative multiphoton regime;
- $\gamma_K\ll1$: tunnelling regime;
- $\gamma_K\sim1$: crossover requiring a unified rate model.

The minimum photon count is

$$K=\left\lceil\frac{U_i}{h\nu}\right\rceil,$$

and a simplified multiphoton source behaves as $S_{MPI}\propto I^K$. Near threshold, small intensity fluctuations can therefore create large shot-to-shot changes.

## Validity boundary

For nanosecond air breakdown, impurities, aerosols, excited-state pathways and inverse-Bremsstrahlung-driven avalanche can dominate after the first seeds appear. $\gamma_K$ must not be used as a prediction of the electrical breakdown threshold or final electron density.

## Experimental consequences

- Calculate $\gamma_K$ with uncertainty from measured waist, pulse duration and energy.
- Use critically evaluated ionisation energies and state the molecular species/model.
- Compare wavelengths through both photon order and propagation/focusing effects.
- Treat the inferred ionisation regime as a mechanism hypothesis to be tested against channel measurements.

## Connections

- **Up:** [[II Areas/01_Research/Concepts/202609011000 - Optical Breakdown Mechanism in Air|Optical Breakdown Mechanism in Air]]
- **Side:** [[II Areas/01_Research/Concepts/202609031120 - Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions|Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions]] · [[II Areas/01_Research/Concepts/202609031110 - Avalanche Ionization Can Dominate Nanosecond Breakdown|Avalanche Ionization Can Dominate Nanosecond Breakdown]]
- **Down:** [[II Areas/03_Thesis/Claims/H2 - Channel state versus pulse energy]] · [[II Areas/03_Thesis/Claims/H4 - Reduced predictive model]]

## Anchor sources

- Keldysh, *Ionization in the field of a strong electromagnetic wave*, *Soviet Physics JETP* 20 (1965), [original full text](https://www.jetp.ras.ru/cgi-bin/index/e/20/5/p1307?a=list).
- NIST Atomic Spectra Database, critically evaluated ionisation energies, [doi:10.18434/T4W30F](https://doi.org/10.18434/T4W30F).

