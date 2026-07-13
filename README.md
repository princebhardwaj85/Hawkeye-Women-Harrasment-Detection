# 🦅 Hawkeye – AI-Powered Women Harassment Detection System

<p align="center">
  <img src="assets/banner.png" alt="Hawkeye Banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green">
  <img src="https://img.shields.io/badge/YOLOv8-Object%20Detection-red">
  <img src="https://img.shields.io/badge/PyQt5-Desktop%20Application-orange">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

## 📌 Overview

**Hawkeye** is an AI-powered women safety application that detects potential harassment incidents in real-time using Computer Vision and Deep Learning.

The system continuously analyzes live camera feeds using **YOLOv8**, identifies suspicious interactions, and instantly alerts nearby users through sound notifications and desktop alerts. The goal is to provide an intelligent surveillance solution capable of assisting in public safety environments.

---

## ✨ Features

- 🎥 Real-time webcam/video surveillance
- 🤖 YOLOv8-based object detection
- 🚨 Automatic harassment event detection
- 🔔 Instant desktop notifications
- 🔊 Emergency sound alerts
- 🖥️ User-friendly PyQt5 interface
- ⚡ Fast inference with OpenCV
- 📊 Live detection visualization

---

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Deep Learning | YOLOv8 (Ultralytics) |
| Computer Vision | OpenCV |
| GUI | PyQt5 |
| Notifications | Plyer |
| Audio Alerts | Playsound / Pygame |
| Numerical Computing | NumPy |

---

## 📂 Project Structure

```
Hawkeye/
│
├── assets/
├── models/
├── detection/
├── ui/
├── utils/
├── main.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/princebhardwaj85/Hawkeye-Women-Harrasment-Detection.git

cd Hawkeye-Women-Harrasment-Detection
```

### Create Virtual Environment

```bash
python -m venv venv
```

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python main.py
```

---

## 🧠 How It Works

1. Captures live video from the webcam.
2. Each frame is processed using YOLOv8.
3. Human interactions are analyzed.
4. Suspicious harassment-related activities are detected.
5. The system triggers:
   - Desktop Notification
   - Sound Alarm
   - Visual Alert on Screen

---

## 📷 Demo

Add screenshots or GIFs here.

```
assets/demo.gif
```

or

```
assets/screenshot.png
```

---

## 🚀 Future Improvements

- SMS Emergency Alert
- Live GPS Tracking
- Cloud Dashboard
- Android Application
- CCTV Camera Support
- Multiple Camera Monitoring
- Face Recognition
- Incident Recording
- Automatic Evidence Storage

---

## 🎯 Applications

- Public Transport
- Railway Stations
- Bus Stops
- Colleges
- Offices
- Shopping Malls
- Smart Cities
- Parking Areas

---

## 📈 Project Objectives

- Improve women's public safety.
- Detect suspicious activities automatically.
- Reduce response time during emergencies.
- Assist security personnel using AI.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👨‍💻 Author

**Prince Bhardwaj**

- GitHub: https://github.com/princebhardwaj85
- LinkedIn: https://www.linkedin.com/in/princebhardwaj6785/

---

## ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐**.

It motivates future improvements and helps others discover the project.

---

> **Disclaimer:** This project is designed as an AI-assisted safety tool for educational and research purposes. It should not be considered a replacement for professional security systems or emergency services.
