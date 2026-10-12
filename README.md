# Volumetric Physical Data Storage

**Color, structure, depth, growth, and scan-readable patterns**

An independent research concept by **Shane A. Fortner** exploring how digital data might be encoded at registered positions within durable physical objects and recovered as exact source bytes.

## Read the paper

[**Download or read the concept paper (PDF)**](papers/Volumetric_Physical_Data_Storage_Shane_A_Fortner_v1.2.pdf)

**Version 1.2 | October 12, 2026 | 8 pages**

The paper includes the main proposal, candidate transparent hosts, combined optical properties, scan-readable internal patterns, and a new appendix on encoding data during crystal growth.

[Previous version 1.1 (PDF)](papers/Volumetric_Physical_Data_Storage_Shane_A_Fortner_v1.1.pdf)

### Changes in version 1.2

- Adds **Appendix C: Encoding data during crystal growth**, including related research and a proposed recovery experiment.
- Explains when growth-defined material properties could carry additional data alongside color and written structure.
- Distinguishes a shared growth-band value from an independently controlled value at every optical location.
- Updates the cover, abstract, date, references, and capacity-table typography while preserving the original numerical examples.

## What this proposal investigates

- **Optical storage:** calibrated color or spectral response together with laser-written structure inside transparent materials.
- **Encoding during growth:** a source payload would determine controlled changes during fabrication; the resulting material pattern must be independently read and verified. Combining it with other properties requires measuring the full joint alphabet.
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

Appendix C proposes a separate growth experiment: fabricate a short message as material regions, recover it with a fixed decoder, test covering growth, and compare growth-only, optical-only, and combined designs.

Advance only when additional states or layers improve verified usable capacity after overhead. This repository currently contains the concept paper; it does not contain a working encoder, decoder, or physical prototype.

## Current status

This is a **concept proposal and feasibility test plan**. The paper reports no physical storage prototype, demonstrated 32-bit voxel, fabrication-encoded archive, verified capacity or energy advantage, or proven archival lifetime. Its capacity examples are conditional arithmetic.

Volumetric glass storage and embedded scan-readable codes have substantial prior work. The paper cites relevant research and does not claim first invention, institutional affiliation, or endorsement. Any novelty or practical advantage needs a fuller literature review and controlled comparison.

## Technical feedback and collaboration

Feedback is welcome through [GitHub Issues](https://github.com/Gmjeer/volumetric-physical-data-storage/issues), especially on:

- Stable optical channels that can be written and independently read in the same voxel.
- Calibration, joint symbol classification, and error-correction methods.
- Encoding during crystal growth and the granularity of independently controllable material regions.
- Suitable host materials and accessible writing or reading equipment.
- A small experiment that can recover previously unseen payloads exactly.
- Fair comparisons of usable capacity, reliability, and whole-system energy.

The immediate goal is to identify and test a feasible small experiment.

## Citation

Shane A. Fortner. *Volumetric Physical Data Storage: Color, structure, depth, growth, and scan-readable patterns*. Independent concept proposal, version 1.2, October 12, 2026.

## Document integrity

SHA-256 of the current version 1.2 PDF:

```text
c986aff9078d7c344b34e8e6917d8ed53dad38b3735cf778035fefbefcb47810
```

