# Pose-Controlled Gesture Game 🎮🕺

This project uses **MediaPipe Pose Estimation** and **OpenCV** to allow real-time body gesture controls (like jump, crouch, left/right) to play games via webcam input. Built with Flask.

## 💡 Features
- Pose detection using MediaPipe
- Real-time gesture feedback (jump, crouch, move)
- Gesture-triggered keystrokes via PyAutoGUI
- Calorie tracking + FPS display

## 📦 Tech Stack
- Python
- Flask
- OpenCV
- MediaPipe
- PyAutoGUI

## 🚀 Run Locally
```bash
pip install -r requirements.txt
python webcam_server.py
