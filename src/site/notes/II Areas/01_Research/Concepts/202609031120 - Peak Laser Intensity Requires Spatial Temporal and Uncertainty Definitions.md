---
title: "Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions"
aliases:
  - Peak laser intensity
  - Gaussian pulse intensity
type: concept
status: evergreen
context: research
claims: [H1, P1, H2]
topics:
  - topic/ltsg/channel
  - topic/ltsg/metrology
tags:
  - type/permanent
  - context/research
  - topic/ltsg/channel
  - topic/ltsg/metrology
created: 2026-09-03
last_updated: "2026-09-14"
dg-publish: true
dg-home-link: true
---

# Peak Laser Intensity Requires Spatial Temporal and Uncertainty Definitions

## Core atomic concept

Pulse energy is not peak intensity. Conversion requires a spatial profile, temporal profile, beam radius at the interaction region and explicit width conventions. Without them, an optical-breakdown “threshold” is not reproducible.

## Gaussian formulation

For

$$I(r,t)=I_0e^{-2r^2/w_0^2}e^{-4\ln2\,t^2/\tau_{FWHM}^2},$$

integration gives

$$
I_0=\frac{2E_L}{\pi w_0^2\tau_{FWHM}}
\sqrt{\frac{4\ln2}{\pi}}.
$$

The coefficient changes if $w_0$ is not the $1/e^2$ intensity radius or if pulse width is not intensity FWHM. For Gaussian propagation,

$$w(z)=w_0\sqrt{1+(z/z_R)^2},\qquad
z_R=\frac{\pi w_0^2}{M^2\lambda}.$$

This exposes the intensity-versus-interaction-length trade-off.

## Uncertainty model

For independent small relative uncertainties,

$$
\left(\frac{u(I_0)}{I_0}\right)^2\approx
\left(\frac{u(E_L)}{E_L}\right)^2+
4\left(\frac{u(w_0)}{w_0}\right)^2+
\left(\frac{u(\tau)}{\tau}\right)^2.
$$

The waist term is doubled in sensitivity and often dominates. Correlations require the full covariance form $u_y^2=\mathbf J\mathbf\Sigma\mathbf J^T$ or Monte Carlo propagation.

## Experimental consequences

- Record shot-resolved $E_L$ where possible and repeat waist/profile measurements after realignment.
- State whether the threshold is 10%, 50% or another breakdown probability.
- Include $M^2$, focus position and clipping; report intensity as model-derived with uncertainty.
- Use measured channel descriptors in H2 because aberration and nonlinear propagation can break the nominal Gaussian mapping.

## Connections

- **Up:** [[Laser-Induced Plasma Dynamics]]
- **Side:** [[II Areas/01_Research/Concepts/202609031100 - Keldysh Parameter Separates Strong-Field Ionization Regimes|Keldysh Parameter Separates Strong-Field Ionization Regimes]] · [[II Areas/01_Research/Concepts/202609031130 - Kerr Self-Focusing Creates Extended Filamentary Channels|Kerr Self-Focusing Creates Extended Filamentary Channels]]
- **Down:** [[H2 - Channel state versus pulse energy]] · [[II Areas/01_Research/Concepts/202609031250 - Measurement Uncertainty Must Propagate Through Derived Quantities|Measurement Uncertainty Must Propagate Through Derived Quantities]]

## Anchor source

- JCGM, *Guide to the Expression of Uncertainty in Measurement*, [doi:10.59161/JCGM100-2008E](https://doi.org/10.59161/JCGM100-2008E).

