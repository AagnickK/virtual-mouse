
# 🖱️ Virtual Mouse Controller with Hand Gestures

A **touchless virtual mouse** tool that lets you control your system's mouse actions — such as **moving the cursor**, **left click**, **right click**, **double click**, and even **take screenshots** — using only your **finger gestures**, detected through your webcam.

Built using Python, OpenCV, MediaPipe, PyAutoGUI, and Pynput, this tool gives users an intuitive and hands-free way to interact with their computer.

---

## ✨ Features

- 🖱️ **Cursor Movement** – Move the mouse cursor with index finger gestures.
- 👈 **Left Click** – Trigger left click using a simple hand gesture.
- 👉 **Right Click** – Use another hand gesture to right-click.
- ✌️ **Double Click** – Double-click by combining finger angles.
- 📸 **Take Screenshot** – Perform a gesture to capture your screen instantly.
- 📷 **Live Camera Display** – Shows a real-time feed with visual gesture feedback.

---

## 🧠 How It Works

- Uses **MediaPipe** to track 21 hand landmarks.
- Uses **angles and distances between finger joints** to detect gestures.
- Performs mouse actions based on gesture recognition:
  - **Angle-based conditions** for gesture identification.
  - **Distance-based conditions** for context-sensitive controls (e.g. screenshot if fingers are close).
- Leverages **PyAutoGUI** and **Pynput** for seamless system control.

---

## 📦 Requirements

Install dependencies using `pip`:

```bash
pip install opencv-python mediapipe pyautogui pynput numpy
