# 🎧 Audio Deepfake Detection Using Deep Learning

## 📌 Overview
This project presents an AI-powered approach to detect **audio deepfakes** a synthetic voice recordings that mimic real individuals. Using deep learning techniques applied to spectrogram and MFCC representations, the system classifies real versus spoofed audio with high accuracy.

Deepfake audio can be maliciously used for impersonation, fraud, and misinformation. This model contributes toward building secure and trustworthy audio-based applications, especially in digital media and security contexts.

---

## 🧠 Methodology

### 🎼 Audio Processing
- **Preprocessing:** Conversion of audio files to Mel-Spectrogram and MFCC features
- **Noise reduction** and trimming for clean inputs

### 🧠 Deep Learning Model
- **Architecture:** CNN + LSTM hybrid
- **Input:** Time-frequency features (Spectrograms and MFCCs)
- **Framework:** TensorFlow / Keras
- **Dataset:** ASVspoof 2019 (Real & Fake audio clips)

### 🧪 Evaluation
- **Metrics:** Accuracy, Precision, Recall, AUC
- **Accuracy Achieved:** 91% – 94% depending on preprocessing strategy

---

## 🚀 Future Directions
- Real-time fake voice detection from microphone input
- Extend to multilingual and noisy environments
- Deploy as a web or mobile API

