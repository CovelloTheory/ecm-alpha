# EEG Consciousness Mode (ECM) – Alpha

Early-stage alpha prototype of the EEG Consciousness Mode system based on Covello Theory.

## Core Features
- Real-time EEG waveform visualization
- Dynamic Covello Metrics:
  - **CIndex** (Consciousness Integration Index)
  - **PRI** (Projection Recursion Index)
  - **QES** (Quality of Experience Score)
- Collapse Event Prediction Engine (CEPE)
- Band power plots across standard frequency ranges
- Fully adaptive metric logic for real EEG data

## Usage
Run `ecm_main.py` with an `.edf` EEG file (e.g. `real_eeg_2.edf`) to see metrics and band powers in real time.

## EEG Data and Interpretation

This demo processes **real EEG data** (EDF format) using live spectral analysis and adaptive metric computation.  
- Band powers reflect **standard clinical frequency ranges** (Delta, Theta, Alpha, Beta, Gamma)  
- Custom metrics — **CIndex (Consciousness Integration Index)**, **PRI (Projection Recursion Index)**, and **QES (Quality of Experience Score)** — are derived from Covello Theory and normalized between 0 and 1.  
- All values are updated in real time and mapped over a sliding time window.

This system is designed to be readable and interpretable by neuroscientists, EEG technicians, and research professionals alike.

## Disclaimer
This is an alpha release for demonstration and Kickstarter launch purposes. Not for clinical use (yet).

## License
The ECM prototype is released under a limited-use license for research, demo, and educational purposes only. Commercial or clinical reuse is prohibited without written permission. All core intellectual property is © 2025 Covello Theory.

## Code Availability
Prototype code will be made available to backers and grant reviewers post-validation. Current results shown are based on internal testing.

