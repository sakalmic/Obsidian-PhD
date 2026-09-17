---
title: "Arc Quenching Dynamics in Hybrid Breakers"
aliases:
  - "Zettel - Arc Quenching Dynamics in Hybrid Breakers"
  - "Arc Quenching Dynamics in Hybrid Breakers"
tags:
  - type/permanent
  - context/research
  - theme/arc-quenching
  - status/evergreen
date: 2026-09-01
last_updated: "2026-09-14"
dg-publish: true
dg-home-link: true
---

# Arc Quenching Dynamics in Hybrid Breakers

## Core concept
In a hybrid breaker, current is commutated away from the mechanical contact into another branch so that the contact can interrupt at a natural or deliberately created current zero. Semiconductor, resonant and auxiliary-switch branches are established concepts; a laser-triggered spark gap is a **candidate auxiliary switch**, not yet a demonstrated breaker architecture in this project.

---

## Recovery-voltage and quenching dynamics
Arc quenching is limited by the rate of rise of recovery voltage (RRRV):
$$
\text{RRRV} = \left.\frac{du_{TRV}}{dt}\right|_{t=0} \le \left(\frac{du_{diel}}{dt}\right)_{crit}
$$
An LTSG could contribute to the timing of an auxiliary commutation pulse, but the switch alone does not create an artificial current zero. That system-level outcome additionally requires a commutation circuit, sufficient opposing current, insulation recovery and acceptable recovery-voltage stress. The core PhD campaign measures atmospheric trigger probability, delay and channel descriptors, validates prediction and evaluates bounded laboratory TCO. Dedicated recovery, erosion and breaker studies remain Tier 3 follow-on; no breaker demonstration is required for dissertation submission.

The coupled thermal/electrical mechanism is developed in [[II Areas/01_Research/Concepts/202609031350 - Arc Conductance and Recovery Compete After Current Zero|Arc Conductance and Recovery Compete After Current Zero]]. Near current zero, a Mayr-type conductance model can be used as an identified black-box model, but its cooling power and time constant must be estimated from the specific interrupter; they are not transferable constants.

## Demonstrator evidence needed

- a complete equivalent circuit and energy balance;
- comparison with a defined incumbent auxiliary switch;
- current-zero timing and post-zero dielectric recovery;
- transient recovery voltage and RRRV margin;
- repetitive-shot lifetime, failure modes and laser-system overhead.

---

## Connections

- **Up:** [[High-Voltage Arc Quenching & Protection]]
- **Side:** [[II Areas/01_Research/Concepts/202609031350 - Arc Conductance and Recovery Compete After Current Zero|Arc Conductance and Recovery Compete After Current Zero]] · [[II Areas/01_Research/Concepts/202609031330 - Plasma and External Circuit Form One Dynamical System|Plasma and External Circuit Form One Dynamical System]]
- **Down:** [[Techno-Economic Modeling of Grid Switching]]

## Anchor sources

- Ramus et al., breaker arc models and TRV, [doi:10.2478/aee-2015-0034](https://doi.org/10.2478/aee-2015-0034).
- Bento, Bento and Cardoso, hybrid DC breaker architectures, [doi:10.1109/OJIES.2023.3320900](https://doi.org/10.1109/OJIES.2023.3320900).
- IEC 62271-100:2021+AMD1:2024, [official record](https://webstore.iec.ch/en/publication/62785).
