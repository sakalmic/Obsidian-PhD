---
title: "Streak Fiducial Enables Sub-30 Picosecond Timing Metrology"
aliases:
  - Streak fiducial metrology
  - Optical fiducial t0
  - Picosecond breakdown delay measurement
type: concept
status: evergreen
context: research
claims: [P1, P2]
topics:
  - topic/ltsg/timing
  - topic/ltsg/metrology
  - topic/ltsg/diagnostics
tags:
  - type/permanent
  - context/research
  - topic/ltsg/timing
  - topic/ltsg/metrology
  - topic/ltsg/diagnostics
date: 2026-09-23
created: 2026-09-23
last_updated: "2026-09-23"
dg-publish: true
dg-home-link: true
---

# Streak Fiducial Enables Sub-30 Picosecond Timing Metrology

## Core atomic concept

Precise measurement of breakdown delay and jitter in laser-triggered spark gaps (LTSG) requires an **optical timing reference ($t_0$)** that is physically decoupled from electrical switching transients and laser-control electronics. 

Coupling a small fraction (1–4%) of the laser pulse via an optical pick-off into a single-mode optical fiber routed directly to the entrance slit of a streak camera (**Streak Fiducial**) establishes an absolute, jitter-free optical time marker on the detection plane. This approach provides sub-5 ps intrinsic timing resolution, completely eliminates electromagnetic pulse (EMP) interference, and bounds the total physical delay uncertainty to **$\sigma_{t0} < 30\text{ ps}$**.

---

## Optical architecture and 2D Streakgram

![Streak Camera Fiducial Timing Measurement and 2D Streakgram](assets/streak_fiducial_setup.jpg)

### 1. Optical Pick-off and Beam Splitting
* **Main beam ($96\text{--}99\%$ energy):** Directed and focused into the high-voltage electrode gap (spherical electrodes, $40\text{ kV DC}$) to initiate laser-driven photoionisation and pre-form a conductive plasma seed.
* **Pick-off beam ($1\text{--}4\%$ energy):** Sampled via an uncoated quartz wedge or beam sampler before chamber entry. This low-energy fraction is coupled via a microscope objective into a single-mode optical fiber without damaging sensitive photodetector surfaces.

### 2. Entrance slit dual-channel coupling
The streak camera entrance slit is optically divided into two spatial sections:
1. **Fiducial reference channel:** Directly illuminates the edge of the slit from the optical fiber termination.
2. **Discharge imaging channel:** An imaging objective projects the inter-electrode gap ($z = 0\text{ to }d$) onto the central part of the slit.

### 3. Spatial-temporal electron sweep (The Streakgram)
Inside the streak tube:
* Photons striking the photocathode emit electrons via the photoelectric effect.
* A high-voltage ramp generator applies an ultrafast electrostatic sweep field, deflecting electrons along the vertical axis proportionally to their arrival time.
* **Horizontal axis ($x$):** Spatial coordinate along the slit (fiber on the left, inter-electrode gap in the center).
* **Vertical axis ($y$):** Absolute time ($t$) running downwards in picoseconds.

The resulting 2D streak image displays:
* A sharp, diffraction-limited optical fiducial spot at exactly $t = 0\text{ ps}$.
* The subsequent emergence of streamer fronts and the final bright plasma spark breakdown channel at $t = t_{\text{breakdown}}$.
* The physical breakdown delay is extracted directly:
  $$\Delta t_{\text{delay}} = t_{\text{breakdown}} - t_{\text{fiducial}}$$
  without intervening oscilloscopes, coaxial cables, or electronic digitiser jitter.

---

## Metrological audit: Electronic trigger vs. Optical Streak Fiducial

The necessity of optical fiducial metrology is underscored by comparing past and planned doctoral experimental campaigns:

| Parameter | Series 8–10 (APL 2025 Campaign) | Series 11+ (Doctoral Thesis Core) |
| :--- | :--- | :--- |
| **Reference marker $t_0$** | Electrical TTL sync signal from laser control unit ($1\,\mu\text{s}$ negative square pulse) | Real laser photons on streak photocathode (1.2 ps optical pulse) |
| **Signal transmission** | Coaxial cable (BNC/SMA) to Tektronix MDO4054B oscilloscope | Single-mode optical fiber |
| **EMP susceptibility** | High; ground loops and displacement currents induce probe ringing | **Zero; fully dielectric optical path** |
| **Systematic offset** | Uncalibrated; includes Pockels cell driver and internal cable propagation delays | Deterministic; defined by optical path length ($\Delta L / c$) and fiber group index ($n_g$) |
| **Resulting uncertainty** | Nanosecond-scale ($> 1\text{ ns}$ systematic shift; observed delays $0.16\text{--}8.1\,\mu\text{s}$) | **Picosecond-scale ($\sigma_{t0} < 30\text{ ps}$; intrinsic resolution $< 5\text{ ps}$)** |

---

## Two-Tier Metrology for Series 11+

To balance ultimate physical resolution with statistical sample size for techno-economic models (TCO), doctoral research WP0–WP3 employs a **hybrid two-tier metrology framework**:

1. **Tier A — Canonical Physical Etalon (Streak Camera with Fiducial):**
   * Dedicated measurement runs at the HiLASE Centre.
   * Directly resolves spatial streamer propagation velocity $v(z,t)$ and formative lag $\tau_f$ with sub-10 ps resolution.
   * Serves as the primary traceable standard to measure and de-embed the hardware time delays ($\Delta t_{\text{hardware}}$) of electrical current/voltage probes.
2. **Tier B — High-Throughput Statistical DAQ (Picosecond Photodiode Pick-off):**
   * Routine multi-thousand shot acquisition for survival models (Weibull right-censoring of misfires) and TCO switching risk quantification.
   * Utilises an ultrafast InGaAs PIN photodiode ($< 25\text{ ps}$ rise time, $> 25\text{ GHz}$ bandwidth) mounted directly at the pick-off wedge, feeding a 4–8 GHz digitiser channel with pre-calibrated cable lengths.

---

## Experimental consequences and best practices

- **Fiber dispersion management:** Keep the fiducial fiber length as short as possible to avoid group velocity dispersion ($\text{GVD}$) broadening of the 1.2 ps pulse:
  $$\Delta \tau = D_{\lambda} \cdot \Delta \lambda \cdot L_{\text{fiber}}$$
- **Optical length matching:** Accurately measure the geometric distance from the pick-off wedge to the electrode gap center ($L_{\text{gap}}$) and to the streak slit ($L_{\text{fiber}}$). In vacuum/air, light travels $3\text{ mm}$ in $10\text{ ps}$.
- **Spectral bandpass filtering:** Place a narrow-band dielectric filter ($1030\text{ nm} \pm 5\text{ nm}$) on the fiducial fiber input to prevent ambient plasma luminescence from contaminating the fiducial channel.

---

## Connections

- **Up:** [[II Areas/01_Research/Concepts/Diagnostics - Timing EMP and Radiation|Diagnostics - Timing EMP and Radiation]]
- **Side:** [[II Areas/01_Research/Concepts/202609031300 - Timing Jitter Must Be De-Embedded from the Measurement Chain|Timing Jitter Must Be De-Embedded from the Measurement Chain]] · [[II Areas/01_Research/Concepts/202609031200 - Competing Timescales Determine the Triggering Regime|Competing Timescales Determine the Triggering Regime]] · [[II Areas/01_Research/Concepts/202609031210 - Statistical and Formative Time Lags Are Different Processes|Statistical and Formative Time Lags Are Different Processes]]
- **Down:** [[II Areas/03_Thesis/Claims/P1 - Delay and jitter response|P1 - Delay and jitter response]] · [[II Areas/03_Thesis/Claims/P2 - Reproducible optical and electrical stages|P2 - Reproducible optical and electrical stages]]

---

## Anchor sources

- Hamamatsu Photonics, *Guide to Streak Cameras: Principles, Measurement Methods, and Applications*, Hamamatsu City (2021).
- Huston, A. E., *High-speed photography and photonics*, *Journal of Physics E: Scientific Instruments*, 11(7), 601–609 (1978).
- Sakala, M., Mikeš, J., Hanuš, O., Efmertová, M., Mydlář, M., *The Dynamics of Laser-Driven Ionisation in High-Voltage Circuit Switching*, Manuscript for Applied Physics Letters / IEEE Trans. (2025).
- Rosenthal et al., *Time-resolved diagnostics of laser-guided electrical discharges*, *Optics Express*, 28(26), 398836 (2020), [doi:10.1364/OE.398836](https://doi.org/10.1364/OE.398836).
