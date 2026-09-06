---
title: "COMSOL Multiphysics Setups"
aliases:
  - COMSOL Multiphysics Setups
tags:
  - type/study
  - context/research
  - theme/comsol-simulation
  - status/in-progress
date: 2026-09-01
last_updated: 2026-09-01
dg-publish: true
---

# COMSOL Multiphysics Setups

Documentation of physics interfaces, material properties, solver settings, and model coupling in COMSOL Multiphysics.

---

## Multiphysics coupling

- **Plasma Module — drift–diffusion:** Uses cross-section data for air ($N_2$, $O_2$) from the LXCat database.
- **Electrostatics:** Coupled to plasma charge density through $\rho = q(n_i - n_e)$.
- **Time-dependent solver:** BDF method of order 1–5 with adaptive time stepping and $\Delta t_{\min} = 10^{-13}\text{ s}$.
