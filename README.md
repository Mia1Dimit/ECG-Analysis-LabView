# ECG Analysis LabView

ECG signal analysis and HRV extraction toolkit built with LabView and hardware-assisted acquisition workflows.

## Overview

This project provides a practical environment for ECG preprocessing, QRS detection, RR interval extraction, and advanced Heart Rate Variability analysis. It is designed for education, prototyping, and research-oriented experimentation.

## Core Capabilities

- ECG signal visualization (raw and filtered)
- R-peak detection and QRS analysis
- RR interval extraction
- HRV analytics in multiple domains:
  - Time domain (e.g., SDNN, RMSSD, NN50, pNN50)
  - Frequency domain (e.g., LF, HF, LF/HF)
  - Nonlinear metrics (e.g., Poincare-based analysis)
- Signal conditioning and noise filtering support

## Why HRV Matters

HRV can provide meaningful insight into autonomic regulation, stress response, recovery state, and cardiovascular dynamics. This project helps transform ECG data into interpretable physiological indicators.

## Typical Workflow

1. Acquire ECG signal (direct source or imported data)
2. Apply filtering and preprocessing
3. Detect R-peaks and compute RR intervals
4. Run HRV metrics and visualize outputs
5. Export results for reporting or further analysis

## Requirements

- NI LabView installation compatible with project VIs
- ECG signal source (recorded dataset or live acquisition chain)
- Optional hardware integration (e.g., Arduino-based acquisition)

## Use Cases

- Biomedical signal processing education
- HRV analysis demonstrations in labs
- Rapid prototyping of ECG analytics workflows
- Research support for physiological monitoring studies

## Project Status

Active as a biomedical signal processing project with room for extension in metrics, UI, and validation datasets.

## Contribution

Contributions are welcome for:
- additional ECG/HRV metrics
- improved filtering pipelines
- better visualizations and reporting templates

Please review:
- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`

## License

This project is licensed under the MIT License. See `LICENSE` for details.
