---
{"dg-publish":true,"permalink":"/ii-areas/01-research/experiments/calibrations/hi-lase-trigger-to-optical-timing-verification-plan/","title":"HiLASE - verification of electrical-trigger to optical-arrival timing","noteIcon":"","updated":"2026-09-16","dg-note-properties":{"title":"HiLASE - verification of electrical-trigger to optical-arrival timing","aliases":["HiLASE electrical-trigger timing calibration","HiLASE trigger-to-optical timing"],"type":"calibration-plan","status":"verification-pending","evidence_state":"unverified","calibration_id":"HILASE-TIME-2024-2025-OPEN","created":"2026-09-16","last_updated":"2026-09-16","topics":["topic/ltsg/timing","topic/ltsg/metrology"]}}
---


# HiLASE: verifying electrical-trigger → optical-pulse → breakdown timing

## Status on 16 September 2026

The electrical triggering system **may have been calibrated** during the historical campaigns. The publications and working records reviewed so far do not document a numerical correction and uncertainty for the complete timing chain used with the high-voltage spark gap. This **does not mean that no calibration exists**. A record must be requested from the responsible laboratory and matched to the actual 2024/2025 configuration.

In APL 2025, February 2025 series 8–10 use an electrical laser-trigger edge as the time reference. The reported range of 0.164–8.124 µs therefore must not be relabelled as time from optical arrival at the gap without further evidence. The seven May 2024 series mainly address breakdown-voltage reduction; their provenance and unresolved attempt counts are recorded in [[II Areas/01_Research/Experiments/Dataset Manifests/Historical Measurements 2024-2025 - Provenance\|Historical Measurements 2024-2025 - Provenance]]. The general claim that greater irradiance always shortens delay remains unverified.

## Three distinct time events

| Symbol | Event | Present evidence |
| --- | --- | --- |
| $t_E$ | Chosen edge of the electrical laser-trigger signal at a defined measurement point | APL uses an electrical reference; the exact signal location and channel need confirmation. |
| $t_O$ | Actual arrival of the optical pulse in the spark-gap interaction region | The reviewed material does not provide an assigned, calibrated timestamp. |
| $t_B$ | Breakdown detected using a predefined voltage/current criterion | The event marker and probe response can introduce additional offset and uncertainty. |

After the relevant electrical-channel corrections, the electrically referenced interval is $D_E=t_B-t_E$. The desired physical interval is $D_O=t_B-t_O$. With consistent timestamp definitions, $D_O=D_E-(t_O-t_E)$. The term $(t_O-t_E)$ cannot be inferred from cable length alone: it can include laser electronics, pulse selection, the actual optical path and their variability. This equation accounts for the time marks; it is **not an already measured correction**.

For an optical pick-off at location $P$, the photodiode time must also be converted to pulse-arrival time at the gap. Corrections cover the difference in optical path, photodiode response, cable and oscilloscope channel, and the electrical breakdown marker. A fixed offset changes mean delay. Pulse-to-pulse variation and unstable event markers may also change the estimated jitter. Variance components must not be subtracted mechanically unless independence is justified.

## Evidence currently available

- The APL 2025 spark-gap paper reports electrically referenced delay, without a documented optical time zero at the gap. [DOI: 10.1109/APL65034.2025.11108944](https://doi.org/10.1109/APL65034.2025.11108944).
- A 2019 LIDT-laboratory paper describes PERLA B, an optical diagnostic pick-off, a photodiode in the station diagram and a **calibrated energy meter**. It does not give a timing calibration protocol for the spark gap. [Čech et al., 2019](https://www.mmscience.eu/journal/issues/december-2019/articles/laser-induced-damage-threshold-testing-at-hilase/download).
- A photodiode in an earlier LIDT study detects scattered light from optical damage. This does not establish an optical time reference for the spark gap. [Vanda et al., 2016](https://doi.org/10.1017/hpl.2016.11).
- The local February 2025 archive contains four-channel oscilloscope waveforms. CSV headers establish a shared recorded time axis but do not identify physical channel wiring, a calibration record or optical arrival at the gap. This is a file-format check, **not** a full audit of all waveforms.

Laboratory context: [[II Areas/01_Research/Experiments/HiLASE LIDT Laboratory\|LIDT laboratory]] · [[II Areas/01_Research/Experiments/HiLASE Research Hub\|HiLASE research hub]] · [[II Areas/01_Research/Concepts/202609031300 - Timing Jitter Must Be De-Embedded from the Measurement Chain\|Measurement-chain jitter]].

## Verification tasks

- [ ] **Contact Martin Mydlář**, co-author of the APL and LIDT papers. Ask him to identify the person responsible for the actual laser branch and to confirm whether and how electrical-trigger to optical-pulse timing at the gap was calibrated in 2025. This is a planned task; no message has been sent.
- [ ] Obtain written confirmation or the existing protocol: date, system/branch ID, wiring version, trigger and optical-path diagram, photodiode position, correction method, measured offset, uncertainty, pulse-to-pulse variation and applicability to May 2024 and February 2025. If there is no protocol, record explicit confirmation of which parts were and were not calibrated.
- [ ] Map the archived oscilloscope channels to physical signals using the laboratory log or schematic. Check whether any channel actually measured the optical pulse; do not confuse an electrical laser marker with a photodiode signal.
- [ ] Distinguish electrical cable-chain calibration, internal laser delay, photodiode response and the breakdown marker. Check whether corrections changed with laser branch, wavelength, repetition regime or optical delivery path.
- [ ] If the historical chain is adequately documented, reproducibly recalculate historical delays with shared and random uncertainties. If parts are missing, report bounds; do not claim that physical jitter has been recovered.
- [ ] For the new campaign, specify simultaneous acquisition of the electrical marker, optical pick-off and breakdown waveform. Recheck timing offsets after wiring changes, and archive configuration and calibration data.

## Closure criteria

**A — historical calibration confirmed:** a configuration-matched protocol supports a corrected interval and uncertainty. **B — partial calibration:** correct only documented components and state the remaining interpretive limit. **C — undocumented:** retain the explicitly electrically referenced historical result and establish optical time zero prospectively in the new campaign. None of these outcomes automatically overwrites published APL values.

## Metrology reference

JCGM, *Evaluation of measurement data — Guide to the expression of uncertainty in measurement*, JCGM 100:2008, [DOI: 10.59161/JCGM100-2008E](https://doi.org/10.59161/JCGM100-2008E). The analysis must retain correlations between shared timing offsets and distinguish uncertainty of the mean correction from pulse-to-pulse variability.
