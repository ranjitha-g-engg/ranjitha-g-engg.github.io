---
title: "AI Virtual Mouse - Hand Gesture Control"
excerpt: "Control your computer with hand gestures using computer vision and ML<br/><img src='https://images.unsplash.com/photo-1593376893114-1aed528d80cf?w=600&h=300&fit=crop'>"
collection: portfolio
---

<div style="margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe">
</div>

## Hands-Free Computer Control

**Year:** 2023 | **Type:** Computer Vision Application

[View on GitHub](https://github.com/ranjitha-g-engg/virtual-mouse){: .btn .btn--primary}

### Overview
Python-based virtual mouse system that enables computer control using hand gestures captured through webcam. Uses MediaPipe for hand tracking and machine learning for gesture recognition.

### Supported Gestures

| Gesture | Function | Status |
|---------|----------|--------|
| 👆 Index Finger | Cursor movement | ✅ Working |
| 🤏 Pinch | Mouse click | ✅ Working |
| ✌️ Peace Sign | Advanced actions | 🚧 In Development |

### Key Features

- **Real-time hand tracking** using MediaPipe (21 landmark points)
- **Gesture recognition** with scikit-learn ML classifier
- **Mouse control** via PyAutoGUI automation
- **Data collection tool** for training custom gestures
- **Low latency** response (<100ms)

### How It Works
Webcam → Hand Detection → Gesture Recognition → Mouse Action

1. **MediaPipe** detects hand and tracks 21 landmarks
2. **ML Classifier** identifies gesture (index finger, pinch, etc.)
3. **PyAutoGUI** executes corresponding mouse action

### Technologies

`Python` `OpenCV` `MediaPipe` `PyAutoGUI` `scikit-learn` `NumPy` `Pandas`

### Applications

✅ Touchless computer interaction  
✅ Accessibility tool for differently-abled users  
✅ Presentation control  
✅ Gaming interface

### Technical Implementation

- Hand landmark detection with MediaPipe Hands
- Feature extraction from 21 3D coordinates
- Gesture classification with trained ML model
- Smooth cursor tracking with filtering algorithms
- Distance-based pinch detection

---

**Status:** Working prototype with core gestures implemented

[View Code](https://github.com/ranjitha-g-engg/virtual-mouse){: .btn .btn--primary}
