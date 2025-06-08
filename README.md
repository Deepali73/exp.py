# 😃🎶 Emotion-Based AI Music Player (Facial Expression Detection + YouTube)

This project uses **Artificial Intelligence** to detect **facial expressions** in real-time via webcam and **play songs** from YouTube based on the detected emotion.

---

## 📌 Features

- 🎥 **Real-time facial emotion detection** using OpenCV and deep learning.
- 🧠 AI-based emotion classification (Happy, Sad, Angry, Neutral, etc.).
- 🎵 **YouTube integration** to play emotion-matched music.
- 🧠 Pre-trained models for emotion recognition (CNN or FER models).
- 🖥️ Simple GUI with live video preview and song status.

---

## 🎯 How It Works

1. **Capture webcam feed** using OpenCV.
2. **Detect face** using Haar cascades or DNN face detectors.
3. **Classify emotion** using a trained deep learning model.
4. **Play YouTube songs** based on the detected emotion using `pytube` or `pywhatkit`.
