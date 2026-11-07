# WavFry: Noise-Robust Phonation Detection Demonstrations

Interactive demonstration website for the research paper:  
**"WavFry: Towards Robust Acoustic Phonation and Vocal Fry Detection Under Severe Environmental Degradations"**

🌐 **Live Demonstration**: [https://mumu233desu.github.io/wavfry-demo/](https://mumu233desu.github.io/wavfry-demo/)

---

## 📖 Overview

This repository hosts the static, responsive demonstration page designed for conference presentation, poster sessions, and peer review.

### Features
1. **Phonation Typology Archetypes**:
   - Audio references for **Modal**, **Creaky (Vocal Fry)**, and **Breathy** voice qualities.
   - Minimal semantic pairs demonstrating acoustic contrast.
2. **2D Acoustic Degradation & Model Inspection Matrix**:
   - 18 real-world environmental degradation conditions derived from the QUT-NOISE corpus and spatial Room Impulse Responses (RIRs).
   - SNR ladder spanning **15 dB (Mild)**, **5 dB (Moderate)**, and **0 dB (Severe Challenge)** across 5 acoustic environments (*Cafeteria*, *Urban Street*, *Vehicle Cabin*, *Domestic Home*, *Reverberant Space*), plus compound noise + RIR environments.
   - Synchronized **0–4 kHz narrowband spectrograms**, **TextGrid word alignment**, and **split-track continuous posterior probability curves** comparing:
     - **WavFry (Ours)**
     - **DeepFry** (Daggett et al., 2020)
     - **Kane et al.** (COVAREP ANN baseline, 2013)
     - **Praat Pitch Perturbation** (Styler, 2017)

---

## 🛠️ Repository Structure

```text
├── index.html        # Interactive single-page application (HTML5)
├── style.css         # Academic booktabs typography & dual light/dark themes
├── qr_code_demo.png  # 300 DPI QR code for poster & paper inclusion
├── audio/            # 16 kHz mono normalized audio samples (MP3)
└── img/              # Synchronized narrowband spectrograms & multi-model probability curves (WebP)
```

---

## 📱 Mobile & Conference Accessibility
- Fully responsive layout optimized for mobile screens (iOS Safari, Android Chrome, WeChat browser).
- Zero external CDN dependencies for instant offline/weak-network playback during poster sessions.
