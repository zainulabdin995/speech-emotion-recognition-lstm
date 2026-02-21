# Real-Time Speech Emotion Recognition using Deep Learning

## Overview
This project presents a Speech Emotion Recognition (SER) system that utilizes a Long Short-Term Memory (LSTM) network to interpret human emotions from real-time audio streams. The model is trained on the Toronto Emotional Speech Set (TESS) and employs extensive data augmentation techniques (noise addition, time shifting) to ensure robustness in real-world environments.



## Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow / Keras
* **Audio Processing:** Librosa
* **Feature Extraction:** MFCC, Zero Crossing Rate (ZCR), Mel Spectrogram, RMS, and Chroma

## Methodology
The system captures live audio, extracts sequential acoustic features, and passes them through an LSTM-based sequential neural network to classify the emotion into predefined categories. Spectrograms and waveform plots are generated dynamically for visual analysis.

## How to Run
1. Clone the repository: `git clone https://github.com/zainulabdin995/speech-emotion-recognition-lstm.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the real-time detection script: `python src/realtime_predict.py`
