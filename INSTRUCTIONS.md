# Voice Biometric Profiling Engine - Usage Guide

## Overview

Use the templates in `references/profile-template.md` to document and calibrate voice biometric signatures prior to neural TTS fine-tuning or zero-shot cloning.

## Example Profiling Flow

1. Capture a clean 30–60 second vocal reference sample.
2. Measure pitch and formant contours using Praat or Librosa.
3. Populate the 10-section schema in `references/profile-template.md`.
4. Supply the resulting biometric profile to your TTS synthesis engine to lock pronunciation, formant dispersion, and prosodic cadence.
