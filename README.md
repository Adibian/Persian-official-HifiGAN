# Persian-official-HiFiGAN

**Persian-official-HiFiGAN** is a high-fidelity GAN-based vocoder, adapted to generate realistic speech waveforms from mel-spectrograms in the Persian language using [official repository](https://github.com/jik876/hifi-gan). This model builds on HiFiGAN's architecture, providing high-quality audio output and enhanced performance for Persian TTS applications.

## Overview
HiFiGAN is a powerful vocoder known for its high-fidelity audio generation capabilities. By training on Persian language data, **Persian-HiFiGAN** produces natural-sounding speech with the nuanced intonation and phonemes unique to Persian.

The main code is based on [this repository](https://github.com/jik876/hifi-gan), which we used as a foundation. We adapted and trained the HiFiGAN model using this recipe, specifically tuning it to achieve optimal results for Persian TTS.

## Features
- **High-fidelity audio output**: Generates high-quality audio suitable for a variety of TTS applications.
- **Optimized for Persian**: Handles unique Persian phonemes and intonation for natural speech synthesis.
- **Fast Inference**: Capable of real-time audio generation, making it suitable for interactive applications.

## Training Details
The model was trained on a large corpus of Persian speech data, using a mel-spectrogram input to produce realistic audio. Training followed the ParallelWaveGAN HiFiGAN recipe, adapted with custom settings and parameters suited for Persian phonetics.

## How to start
Please refer to [original repository]([https://github.com/kan-bayashi/ParallelWaveGAN](https://github.com/jik876/hifi-gan)) for more details.

## Acknowledgements
We thank the authors of the [HifiGAN repository]([https://github.com/kan-bayashi/ParallelWaveGAN](https://github.com/jik876/hifi-gan)) for their well-structured codebase and recipe, which served as the basis for this Persian adaptation.

## License  
This project is based on [HiFi-GAN](https://github.com/jik876/hifi-gan),  
which is licensed under the MIT License.  
The modifications for [your purpose, e.g., Persian speech synthesis, improvements] are © 2025 Majid Adibian.  
