---
title: "HiLASE LIDT Laboratory - relevance to PERLA timing"
aliases:
  - HiLASE LIDT laboratory
type: laboratory-context
status: evidence-review
context: research
topics:
  - topic/ltsg/metrology
created: 2026-09-16
last_updated: 2026-09-16
dg-publish: true
---

# HiLASE LIDT laboratory and its relevance to spark-gap timing

**LIDT** means *laser-induced damage threshold*. The laboratory studies damage to optical components, not high-voltage breakdown. It is relevant as a possible source of knowledge about the laser platform, diagnostic branches and internal calibration records. Its publications **do not establish** that the spark-gap experiment shared the same wiring or timing calibration.

## Direct connection to the doctoral work

Čech, Vanda, Mureșan, **Mydlář** and colleagues (2019) describe a HiLASE LIDT station using **PERLA B**: 1030 nm, 1 kHz, approximately 1.8 ps pulses and up to 10 mJ in the configuration described then. Mydlář also co-authored the APL 2025 spark-gap paper. This is a strong personnel and platform connection, but it does not prove that both experiments used the same optical branch. The APL paper reports a nominal 1.2 ps pulse duration and several wavelengths. Different reported values may reflect different configurations or periods of operation; the actual branch must be identified from laboratory records.

## What the LIDT publications establish

| Source | Documented information | What cannot be inferred |
| --- | --- | --- |
| Čech et al., 2019 | PERLA B as one LIDT laser source; an optical pick-off after attenuation (<1% of energy) for continuous beam-profile and energy monitoring; a calibrated energy meter; a photodiode in the station diagram. | A numerical timing correction between the electrical command, pulse arrival at the spark gap and breakdown; calibration of spark-gap jitter. |
| Vanda et al., 2016 | Online detection of scattered light with a photodiode and software control of the delivered pulse count in the tests described. The picosecond tests in this paper used a different Yb:KGW laser. | That this was the same PERLA B branch or that the photodiode provided the high-voltage experiment's optical time zero. |
| HiLASE LIDT station description | A 1030 nm / 1 kHz picosecond operating mode and optical inspection. | Identification of the historical 2024–2025 branch, its spark-gap wiring or a timing calibration sheet. |
| HiLASE PERLA 100/C descriptions | Several platform variants with pulse selection and control systems. | Substitution of current product specifications for measured properties of the particular experiment. |

**Metrology boundary:** calibrated pulse energy and beam-profile monitoring support the optical input measurements used for LIDT. They do not demonstrate calibration of electrical-trigger to optical-arrival time at the spark gap. A photodiode used to detect optical damage is not automatically a breakdown timing reference.

## Primary sources

1. P. Čech, J. Vanda, M.-G. Mureșan, M. Mydlář, K. Pilná and J. Brajer, “Laser Induced Damage Threshold Testing at HiLASE,” *MM Science Journal*, 2019. [Full text](https://www.mmscience.eu/journal/issues/december-2019/articles/laser-induced-damage-threshold-testing-at-hilase/download), [DOI: 10.17973/MMSJ.2019_12_2019118](https://doi.org/10.17973/MMSJ.2019_12_2019118).
2. J. Vanda et al., “Comparative LIDT measurements of optical components for high-energy HiLASE lasers,” *High Power Laser Science and Engineering* 4, e11 (2016). [DOI: 10.1017/hpl.2016.11](https://doi.org/10.1017/hpl.2016.11).
3. HiLASE, [Laser-induced damage threshold (LIDT) target area](https://www.hilase.cz/en/laser%E2%80%90induced-damage-threshold-lidt-target-area/) and [PERLA 100](https://www.hilase.cz/en/produkty/perla-100/) — institutional descriptions, not timing calibration protocols.
4. M. Sakala et al., “The Dynamics of Laser-Driven Ionisation in High-Voltage Circuit Switching,” APL 2025, [DOI: 10.1109/APL65034.2025.11108944](https://doi.org/10.1109/APL65034.2025.11108944) — the high-voltage experiment.

## Follow-up tasks

- [ ] Identify whether the 2024–2025 high-voltage experiment actually used PERLA B and how the pulse was delivered to the gap.
- [ ] Determine whether the LIDT and high-voltage campaigns shared only a laser source or also the optical pick-off, photodiode and trigger signal.
- [ ] Request the applicable calibration or service record for that branch; record its existence and applicability in the [[II Areas/01_Research/Experiments/Calibrations/HiLASE Trigger-to-Optical Timing - Verification Plan|timing verification note]].

Back to [[HiLASE Research Hub|HiLASE research hub]].
