---
title: "Simulation Datasets & Models"
aliases:
  - Simulation Datasets
tags:
  - type/study
  - context/research
  - theme/comsol-simulation
  - status/in-progress
date: 2026-09-01
last_updated: "2026-09-14"
dg-publish: true
---

# Simulation Datasets and Models

The legacy catalogue rows below are **unverified draft entries**, not evidence of implemented or validated models. Geometry, modules and mesh counts must be checked against a versioned model file, convergence record and held-out comparison before reuse. The current mandatory target is a reduced atmospheric M0/M1 comparison; additional gases and application models are follow-on only.

A catalogue of numerical models, geometries, and computational datasets.

---

## Model overview

| Model ID | Geometry | COMSOL modules | Mesh size | Status |
| :--- | :--- | :--- | :--- | :---: |
| **MOD-2D-AXI-01** | 2D axisymmetric $10\text{ mm}$ gap with spherical electrodes | Plasma + ES + Heat | ~180,000 elements | Unverified draft; validation not evidenced |
| **MOD-3D-ASYM-01** | 3D asymmetric chamber with cross-flow gas quenching | Plasma + CFD | ~650,000 elements | Unverified draft; implementation not evidenced |
