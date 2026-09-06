---
title: "LTSG Apparatus & Laboratory Safety"
aliases:
  - LTSG Apparatus
  - Laboratory Safety
  - LTSG Setup
tags:
  - type/apparatus
  - context/research
  - topic/ltsg/breakdown
type: apparatus
status: active
context: research
topics:
  - topic/ltsg/breakdown
date: 2026-09-01
last_updated: 2026-09-06
dg-publish: true
dg-home-link: true
dg-render-dataview: true
---

# LTSG Apparatus & Laboratory Safety

This note documents the physical, optical, and electrical configuration of the Laser-Triggered Spark Gap (LTSG) test facility, alongside critical high-voltage and laser safety protocols.

---

## ⚡ 1. High-Voltage Discharge Geometry

- **Electrode Configuration:** Hemispherical and needle-plane electrode geometries with inter-electrode spacing adjustable from $d = 1.0\,\text{mm}$ to $15.0\,\text{mm}$.
- **Electrode Materials:** Copper-tungsten (CuW 80/20) and brass for minimum erosion and stable surface conditioning.
- **Gas Atmosphere:** Atmospheric-pressure synthetic air ($80\%\,\text{N}_2, 20\%\,\text{O}_2$), dry nitrogen ($	ext{N}_2$), and variable pressure chamber setup.
- **Charging Circuit:** High-voltage DC power supply ($0 - 40\,\text{kV}$), low-inductance capacitive storage bank ($C = 1 - 10\,\text{nF}$), and damping resistors.

---

## 🔬 2. Laser Diagnostics & Optical Delivery (HiLASE)

- **Laser Source:** Q-switched Nd:YAG laser system operating at fundamental wavelength $\lambda = 1064\,\text{nm}$ and frequency-doubled $\lambda = 532\,\text{nm}$.
- **Pulse Parameters:** Pulse duration $\tau_p \approx 5 - 10\,\text{ns}$, pulse energy variable from $E_p = 5\,\text{mJ}$ to $150\,\text{mJ}$.
- **Focal Optics:** Anti-reflection coated plano-convex quartz lenses with focal lengths $f = 75\,\text{mm}, 100\,\text{mm}, 150\,\text{mm}$.
- **Diagnostics:** High-speed photodiode synchronization, Rogowski coil current probes ($t_r < 1\,\text{ns}$), and calibrated capacitive voltage dividers.

---

## 🛡️ 3. Safety Protocols & Interlocks

- **Laser Safety:** Class 4 laser area designation. Mandatory certified safety goggles matched to $1064\,\text{nm} / 532\,\text{nm}$ OD > 6+. Optical shutter interlocks.
- **High-Voltage Safety:** Automatic ground discharge sticks, safety cage interlocks with dual-contact microswitches, and Faraday cage enclosure for EMP shielding.

---

## 🔗 Related Notes & Indexes

- [[01_MOC|Research MOC]]
- [[Evidence Index|Experimental Evidence Index]]
- [[COMSOL Multiphysics Setups|COMSOL Simulation Setup]]
