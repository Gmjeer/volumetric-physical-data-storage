# Volumetric Physical Data Storage

**Color, structure, depth, and scan-readable internal patterns**

An independent research concept by **Shane A. Fortner** exploring how digital data might be encoded at registered positions within durable physical objects and recovered as exact source bytes.

## Read the paper

[**Download or read the concept paper (PDF)**](papers/Volumetric_Physical_Data_Storage_Shane_A_Fortner_v1.1.pdf)

**Version 1.1 | October 11, 2026 | 6 pages**

The paper includes the main proposal, candidate transparent hosts, and an appendix on combined optical properties and scan-readable internal patterns. The PDF is the author's original uploaded document.

## What this proposal investigates

- **Optical storage:** calibrated color or spectral response together with laser-written structure inside transparent materials.
- **Depth:** separately readable internal layers, with measurements of attenuation, focus tolerance, and interference.
- **Scan-readable objects:** cavities, solid regions, or composition patterns inside manufactured objects, investigated through tomography.
- **Reliable recovery:** reference marks, calibration, a self-describing format, error correction, and hashes that verify reconstructed bytes.

Candidate hosts discussed in the paper include glass, engineered polymers, synthetic sapphire, and diamond. The appropriate material, writing process, and reader remain experimental questions.

## First practical experiment

Begin with a small, reproducible decoder and printed control before attempting a material sample:

1. Encode known binary payloads using small symbol palettes, reference marks, and calibration patches.
2. Capture them under changes in rotation, scale, illumination, and blur.
3. Measure exact byte recovery, raw symbol errors, correction overhead, and failed blocks.
4. Work with a suitable laboratory to measure achievable material states, then investigate a few separated layers.

Advance only when additional states or layers improve verified usable capacity after overhead. This repository currently contains the concept paper; it does not contain a working encoder, decoder, or physical prototype.

## Current status

This is a **concept proposal and feasibility test plan**. The paper reports no demonstrated 32-bit voxel, verified capacity or energy advantage, or proven archival lifetime. Its capacity examples are conditional arithmetic.

Volumetric glass storage and embedded scan-readable codes have substantial prior work. The paper cites relevant research and does not claim first invention, institutional affiliation, or endorsement. Any novelty or practical advantage needs a fuller literature review and controlled comparison.

## Technical feedback and collaboration

Feedback is welcome through [GitHub Issues](https://github.com/Gmjeer/volumetric-physical-data-storage/issues), especially on:

- Stable optical channels that can be written and independently read in the same voxel.
- Calibration, joint symbol classification, and error-correction methods.
- Suitable host materials and accessible writing or reading equipment.
- A small experiment that can recover previously unseen payloads exactly.
- Fair comparisons of usable capacity, reliability, and whole-system energy.

The immediate goal is to identify and test a feasible small experiment.

## Citation

Shane A. Fortner. *Volumetric Physical Data Storage: Color, structure, depth, and scan-readable internal patterns*. Independent concept proposal, version 1.1, October 11, 2026.

## Document integrity

The PDF is uploaded without changes. Its SHA-256 is:

```text
26045db1eebb9356b53926196db53cdf229a45b736c5335af643d8245781159d
```

