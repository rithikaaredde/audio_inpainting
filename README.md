# Audio Inpainting Project

### Problem Statement
Develop a deep learning model that detects and reconstructs missing or degraded segments in audio recordings while preserving content and perceptual quality.

### Architecture Overview
<img src="architecture _ diagram.png" width="700">

### Dataset Sources
- LibriSpeech (train-clean-100)
- VCTK (speaker diversity)
- ESC-50 (for non-speech sounds)

### Modeling Plan
1. Degradation detector (CNN/Conformer)
2. Inpainting autoencoder or transformer
3. Vocoder reconstruction (Griffin-Lim / HiFi-GAN)

### Tools
- Python, PyTorch, torchaudio, librosa, Hydra, W&B
- Training: Google Colab GPU (T4/P100)

### Contributors
- Prisha Vohra
- Rithikaa Redde
- Sharvari Godbole
- Eesha Barad
