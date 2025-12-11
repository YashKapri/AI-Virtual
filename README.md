# 🖱️ AI Virtual Mouse (Hand Gesture Controller)

> **"I threw away my mouse. I built my own using AI."**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange?style=for-the-badge&logo=google&logoColor=white)](https://developers.google.com/mediapipe)

## 📖 About The Project

This project explores **Human-Computer Interaction (HCI)** by creating a "Zero UI" environment. It allows users to control their computer's mouse cursor, perform clicks, and scroll pages using only hand gestures and a webcam. 

No physical hardware, sensors, or wearables are needed—just **Computer Vision**.

It uses **Google's MediaPipe** framework for high-speed hand tracking and **OpenCV** for image processing, mapping the physical coordinates of your hand to the digital pixels of your screen in real-time.

### ✨ Features
* **Cursor Control:** Move your index finger to move the mouse.
* **Left Click:** Pinch your thumb and index finger together to click.
* **Smoothing Algorithm:** Built-in jitter reduction for a smooth user experience.
* **Zero Latency:** Optimized for real-time performance on standard CPUs.

---

## 🛠️ Tech Stack

* **Python:** Core logic.
* **OpenCV (`cv2`):** Image processing and webcam feed access.
* **MediaPipe:** Machine Learning pipeline for hand landmark detection.
* **PyAutoGUI:** Interface to control the Operating System's mouse and keyboard.
* **NumPy:** Mathematical operations for coordinate mapping.

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites
Make sure you have Python installed. You will need the following libraries:

```bash
pip install opencv-python mediapipe pyautogui numpy
