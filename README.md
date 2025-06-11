# EEG Consciousness Mode (ECM) – Alpha

Early-stage alpha prototype of the EEG Consciousness Mode (ECM) system, a real-time consciousness metric analyzer built on Covello Theory. This research tool maps EEG activity into dynamically evolving cognitive metrics — including integration, recursion, and perceptual clarity.

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

## 🎥 ECM Alpha Live Demo

![Watch the demo](./ecm_demo.mp4)

This video shows the ECM Alpha prototype processing real EEG data and visualizing Covello Theory metrics in real time.
⚠️ ECM Alpha has been tested on a limited set of EEG files (.edf) and may require format-specific adjustments. Broader compatibility and resilience across diverse EEG sources is under active development.
Note: ECM Alpha currently supports a subset of .edf files with consistent channel labeling and structure. For demonstration or testing purposes, please use the provided example file or contact us for compatibility guidance.

## EEG Data and Interpretation

ECM Alpha analyzes real EEG signals (EDF format) using spectral decomposition and live metric modeling.
- Band powers reflect **standard clinical frequency ranges** (Delta, Theta, Alpha, Beta, Gamma)  
- Custom metrics — **CIndex (Consciousness Integration Index)**, **PRI (Projection Recursion Index)**, and **QES (Quality of Experience Score)** — are derived from Covello Theory and normalized between 0 and 1.  
- All values are computed dynamically and updated continuously in a sliding time window.
- This system is under active development and will be optimized further for multi-channel support, signal normalization, and live metric responsiveness.

This system is designed to be readable and interpretable by neuroscientists, EEG technicians, and research professionals alike.

## Disclaimer
This is an early prototype for demonstration and research exploration. Not intended for clinical use or diagnosis at this stage.

## License
The ECM prototype is released under a limited-use license for research, demo, and educational purposes only. Commercial or clinical reuse is prohibited without written permission. All core intellectual property is © 2025 Covello Theory.

## Code Availability
Core prototype code is currently reserved for grant reviewers and research collaborators. Full access will be granted to backers post-launch and to institutions following NDA or validation agreements.

---

### 📚 Citation & Contact

For academic reference, licensing, or collaboration inquiries:

**Michael Covello**  
📧 legal@covellotheory.com  
🌐 [https://covellotheory.com] (In progress)


