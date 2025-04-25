# 🚗 Driver Drowsiness Detection System

This project detects driver drowsiness by monitoring the eye aspect ratio (EAR) in real-time using a webcam. When the system detects prolonged eye closure, it triggers an audio alarm to alert the user.

## 📌 Features

- Real-time detection of eye closure using facial landmarks
- Alerts driver with an alarm sound if drowsiness is detected
- Lightweight and effective, suitable for real-world deployment

## 🧠 How It Works

- The **eye aspect ratio (EAR)** is calculated using six eye landmarks.
- If the EAR falls below a defined threshold (`thresh = 0.25`) for a specified number of frames (`frame_check = 20`), an alarm is triggered.

## 🎯 Requirements

- Python 3.x
- OpenCV
- dlib
- imutils
- scipy
- pygame (for alarm sound)

## 📂 How to Run

1. Install the required packages:

```bash
pip install -r requirements.txt
