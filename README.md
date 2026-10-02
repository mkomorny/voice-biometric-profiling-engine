# Voice Biometric Profiling Engine

[![Automated Release](https://img.shields.io/badge/release-automated_batch_pipeline-blue.svg)](https://github.com/mkomorny)
[![Pipeline Execution](https://img.shields.io/badge/dispatched_by-background_script-informational.svg)](https://github.com/mkomorny)

> [!NOTE]
> **Automated Distribution**: This repository was automatically sanitized, packaged, and published via a scheduled background batch staging pipeline. All file bundling, licensing, and repository synchronization were dispatched automatically by an automated release runner.

A forensic-grade acoustic and voice biometric specification engine for speech science, voice cloning, and neural TTS synthesis (Cartesia, ElevenLabs, Kokoro, VALL-E).

## Scientific Scope & Analytical Schema

The engine defines a standardized 10-dimension acoustic specification framework:
1. **Fundamental Frequency (F0) & Glottal Source**: Mean F0, semitone excursion range, glottal closed/open quotient (CQ/OQ), cycle duration, pulse skewness.
2. **Time-Domain Waveform Dynamics**: RMS dynamic energy, peak-to-peak modulation, shimmer perturbation, transglottal turbulent leakage.
3. **Frequency-Domain & Spectral Characteristics**: H1-H2 difference, Hammarberg index, Alpha ratio, F1-F4 formants, Euclidean Vowel Space Area (VSA).
4. **Vocal Tract & Resonance Modeling**: Pharyngeal volume, velopharyngeal port coupling, oral tract length, formantic bandwidths (B1-B4).
5. **Prosody & Temporal Architecture**: Speaking rate (syllables/sec), pause distribution, declination slope, stress-timed vs. syllable-timed cadence.
6. **Wells 24 Lexical Sets Realization**: Complete phonetic dialect mapping for regional accent accuracy.

## Contents

- `SKILL.md`: Operational prompt engine and forensic reporting rules.
- `references/profile-template.md`: Full multi-page production biometric acoustic profile schema template.

## Dependencies

- Universal Markdown and prompt specification (Zero dependencies).

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0) - see the [LICENSE](./LICENSE) file for details.
