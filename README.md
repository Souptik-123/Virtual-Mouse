# 🖱️ Virtual Mouse using Hand Gesture Recognition

Control your computer mouse using **hand gestures** in real-time — powered by Computer Vision and AI.

---

## 🚀 Overview

This project implements a **gesture-controlled virtual mouse** using a webcam. It leverages **MediaPipe Hand Tracking** and **OpenCV** to detect hand landmarks and map them to mouse actions such as movement and clicking.

---

## ✨ Features

* 🖐️ Real-time hand tracking (21 landmarks)
* 🖱️ Cursor movement using index finger
* 👆 Click action using finger gestures
* 🎯 Smooth cursor control (reduces jitter)
* ⚡ High performance (~25–30 FPS)
* 📦 Lightweight and easy to run

---

## 🧠 How It Works

1. Webcam captures live video feed
2. MediaPipe detects hand landmarks
3. Finger positions are analyzed
4. Gestures are mapped to mouse actions
5. PyAutoGUI controls the system cursor

---

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe
* PyAutoGUI
* NumPy

---

## 📂 Project Structure

```
VirtualMouse/
│
├── VirtualMouse.py          # Main application
├── HandTrackingModule.py    # Hand detection module
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/your-username/virtual-mouse.git
cd virtual-mouse
```

### 2. Create virtual environment (recommended)

```
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the main file:

```
python VirtualMouse.py
```

Press **'q'** to exit.

---

## 🎮 Controls

| Gesture               | Action      |
| --------------------- | ----------- |
| Index Finger Up       | Move Cursor |
| Index + Middle Finger | Click       |
| Hand Not Detected     | No Action   |

---

## 📸 Demo

👉 *(Add a GIF or screen recording here for better impact)*

---

## 📌 Future Improvements

* Scroll gesture support
* Drag & drop functionality
* Right-click gesture
* Multi-hand support
* GUI dashboard

---

## 🧑‍💻 Author

**Souptik Dey**

* Data Science & AI Enthusiast
* Skilled in Computer Vision & Machine Learning

---

## ⭐ Contribute

Feel free to fork this repo and improve it!

---

## 📜 License

This project is open-source and available under the MIT License.
