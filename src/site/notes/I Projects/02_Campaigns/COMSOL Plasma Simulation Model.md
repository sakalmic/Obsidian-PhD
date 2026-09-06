---
aliases:
  - Project - COMSOL Plasma Simulation Model
project_id: LTSG-Model
type: project
context: research
parent_project: LTSG-Core
work_package: WP5
claims:
  - CL-05
priority: high
status: active
due: 2028-02-29
definition_of_done: "A reduced model predicts one predeclared held-out core observable within declared uncertainty or yields a documented quantitative failure bound."
topics:
  - topic/ltsg/model
  - topic/ltsg/channel
tags:
  - topic/ltsg/model
  - topic/ltsg/channel
date: 2026-09-01
last_updated: 2026-09-03
dg-publish: false
---

# 🚀 Project: COMSOL Plasma Simulation Model

## 🎯 Project objective
Develop the **smallest validated model** that predicts one held-out core observable of atmospheric-air laser-triggered breakdown. Begin with electrostatic field mapping and reduced electron/gas-density dynamics; activate detailed 2D/3D chemistry or additional gases only when they improve a predeclared prediction.

## ⚙️ Modelled physics
1. **Plasma Module:** Drift-diffusion equations for electrons and ions, Townsend coefficients $\alpha, \eta$, and photoionisation.
2. **Electrostatics:** Poisson's equation for the electric field modified by space charge.
3. **Heat Transfer & Fluid Dynamics:** Joule heating, shock-wave dynamics and plasma-channel expansion.

## 📋 Actionable Tasks
- [ ] Choose the primary predicted outcome for [[CL-05 - Reduced predictive model]].
- [ ] Separate measured, literature-derived and fitted parameters.
- [ ] Freeze calibration and validation conditions before model tuning.
- [ ] Implement electrostatic field mapping and a 0D/1D electron-balance baseline.
- [ ] Add a measured or parameterised density-channel term.
- [ ] Compare the reduced model with a simpler empirical baseline.
- [ ] Perform sensitivity, numerical-convergence and prediction-interval checks.
- [ ] Add 2D/3D physics only after documenting the predictive value of the added complexity.
