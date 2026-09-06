---
title: "Plasma and External Circuit Form One Dynamical System"
aliases:
  - Plasma-circuit coupling
  - Spark-gap RLC dynamics
type: concept
status: evergreen
context: research
claims: [CL-02, CL-05, CL-06]
topics:
  - topic/ltsg/timing
  - topic/ltsg/model
tags:
  - type/permanent
  - context/research
  - topic/ltsg/timing
  - topic/ltsg/model
created: 2026-09-03
last_updated: 2026-09-03
dg-publish: true
dg-home-link: true
---

# Plasma and External Circuit Form One Dynamical System

## Core atomic concept

After breakdown, measured voltage collapse and current rise are joint outputs of time-varying plasma impedance and the complete external circuit. They cannot be interpreted as intrinsic plasma properties without an equivalent circuit and diagnostic transfer functions.

## Mathematical formulation

For a minimal series discharge loop,

$$L\frac{di}{dt}+[R_s+R_p(t)]i+u_C=0,
\qquad C\frac{du_C}{dt}=-i.$$

The initial energy is

$$W_0=\frac12CU_0^2.$$

Useful integrated quantities are

$$Q=\int i,dt,\qquad W_p=\int u_p i,dt,
\qquad A=\int i^2dt.$$

For constant $R$, the damping ratio is

$$\zeta=\frac{R}{2}\sqrt{\frac{C}{L}},$$

but a spark plasma is nonlinear and time-varying. Fitting one constant resistance may reproduce peak current while misrepresenting early channel formation.

The recorded waveform is also filtered:

$$y_m(t)=h_m(t)*y(t)+\epsilon(t).$$

## Experimental consequences

- Draw capacitance, inductance, return path, probe loading and grounding.
- Measure or bound stray $L$ and transfer responses before inferring plasma resistance.
- Distinguish trigger delay from current rise time and circuit ringing.
- Cross-check energy conservation within uncertainty.
- Fit plasma and circuit parameters only when structurally identifiable; otherwise report equivalent quantities.

## Connections

- **Up:** [[Laser-Triggered Spark Gaps (LTSG)]]
- **Side:** [[Timing Jitter Must Be De-Embedded from the Measurement Chain]] · [[Arc Conductance and Recovery Compete After Current Zero]]
- **Down:** [[CL-05 - Reduced predictive model]] · [[CL-06 - Reproducible optical and electrical stages]]

## Anchor sources

- Luther et al., electrical response of a laser-triggered gap, [doi:10.1063/1.1419036](https://doi.org/10.1063/1.1419036).
- Arantchouk et al., high-current filament-triggered gap, [doi:10.1063/1.4802927](https://doi.org/10.1063/1.4802927).

