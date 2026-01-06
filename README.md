AI Avatar Pipeline – End-to-End Working Demo
Overview

The complete pipeline has been successfully executed locally, and a demo video is included in this repository.
Pipeline Steps Completed
1. Text to Speech (Audio Generation)
Converted input text into speech audio
Used neural Text-to-Speech with speaker conditioning
Generated clean speech audio from text input

2. Voice Cloning
Used my own recorded voice as a reference sample
Generated speech that matches my voice tone and style
Output audio file: voice_cloned.wav

3. Face Processing
Face detection and alignment from a single input image
Cropped and normalized face for animation
Prepared face input for downstream models


4. Lip Sync & Facial Expressions
Generated realistic facial movements and expressions
Synced lip movements accurately with the cloned audio
Supported head motion and expression scaling


5. Final Video Generation
Combined facial animation and cloned voice
Generated final talking avatar video (.mp4)
Output is smooth, expressive, and lip-synced



Models & Tools Used

**Audio / Voice**
Coqui TTS (XTTS – speaker-conditioned TTS)
Used for text-to-speech and voice cloning
Enabled cloning using a short reference voice sample

**Lip Sync**
Wav2Lip
Used for accurate lip synchronization between face and audio

**Facial Expressions & Animation**
SadTalker
Used for facial expressions, head motion, and realistic animation

**Link For Checkpoints**
https://drive.google.com/drive/folders/1kUqhplRd-54SRNwc00FNq0i7deBLpA6t?usp=sharing

**Core Frameworks & Utilities**
PyTorch
FFmpeg
OpenCV
NumPy

