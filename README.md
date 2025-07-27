
# Gesture-Controlled Game

A simple Flask web app that lets users control gameplay using hand gestures via webcam. Built using MediaPipe and TensorFlow Lite for real-time pose estimation and action recognition.

## Features

- Real-time webcam input through the browser
- Pose detection using MediaPipe
- Real-time gesture feedback (jump, crouch, move)
- Gesture classification using a TensorFlow Lite model
- Basic interaction logic to control game elements

## Tech Stack

- Python
- Flask
- OpenCV
- MediaPipe
- PyAutoGUI
- HTML/CSS/JavaScript
- MediaPipe
- TensorFlow Lite

## 📽️ Demo

*(Include a short GIF or video link here if available)*



##  Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/WATERMELONBOSS/gesture-control-game.git
cd gesture-control-game
````

### 2. Create and activate a virtual environment

```bash
python3 -m venv test-env
source test-env/bin/activate  # For Mac/Linux
# For Windows use: test-env\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

##  Running the App

Start the Flask development server:

```bash
flask --app webcam_server run
```

Then open your browser and navigate to:

```
http://127.0.0.1:5000
```

---

## 📁 Project Structure

```
gesture-control-game/
├── webcam_server.py         # Flask server
├── requirements.txt         # Python dependencies
├── .gitignore
├── templates/
│   ├── index.html
│   ├── script.js
│   ├── WarriorVideo.mp4
│   ├── warriorvid.mp4
│   └── warrior.jpg
└── test-env/                # Virtual environment (excluded from git)
```

---

## ⚠️ Notes

* ✅ Allow webcam access in your browser when prompted.
* 🌐 Best viewed in **Google Chrome** or **Firefox**.
* 🚫 This app is **not intended for production** — it's purely for learning, demos, and experimentation.

---




