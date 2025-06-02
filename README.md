# HCI
# Facial Gesture Controlled Mouse System

This project enables hands-free control of the mouse using facial gestures captured from a webcam. By using **dlib**, **OpenCV**, and **pyautogui**, the system detects facial landmarks and maps specific gestures (like eye blinks, winks, and mouth opening) to mouse actions such as cursor movement, clicks, and scrolling.

---

## Features

- Move the mouse cursor using nose direction.
- Blink both eyes to toggle scroll mode.
- Wink left eye for left click.
- Wink right eye for right click.
- Real-time visual feedback with landmark overlays and action labels.

---

## Requirements

Install the required Python libraries:

```bash
pip install opencv-python dlib imutils pyautogui numpy

## 📁 Project Structure

```text
facial-mouse-control/
├── mouse-cursor.py                    # Main Python script
├── utils.py                           # Utility functions (EAR, MAR, direction)
├── model/
│   └── shape_predictor_68_face_landmarks.dat   # Pre-trained dlib model
