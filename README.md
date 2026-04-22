# 🚗 SafeMove Detector  
### 🛑 AI System to Prevent Animal-Hit Before Ignition  

![Python](https://img.shields.io/badge/Python-3.x-blue)  
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)  
![YOLO](https://img.shields.io/badge/Model-YOLO-red)  
![Status](https://img.shields.io/badge/Status-Completed-success)  

---

## 📖 Overview  
SafeMove Detector is an AI-powered safety system that detects small animals under or near parked vehicles before ignition.  

Animals often take shelter under vehicles, which can lead to accidental injuries when the vehicle starts. This project uses **real-time object detection** to identify animals and alert the driver in advance.

---

## 🎯 Problem Statement  
Many small animals (such as cats and puppies) hide under parked vehicles for warmth or safety.  

👉 This project aims to **prevent such accidents using AI-based detection and alert systems**.

---

## ✨ Features  
- 🐾 Real-time animal detection  
- 🎥 Camera-based monitoring  
- ⚡ Instant alert system (buzzer/notification)  
- 🌙 Works in low-light & partial visibility  
- 💰 Low-cost and scalable solution  

---

## 🧠 Tech Stack  
- **Language:** Python  
- **Libraries:** OpenCV, NumPy  
- **Model:** YOLOv8 (Ultralytics)  
- **Concepts:** Machine Learning, Computer Vision  

---

## ⚙️ System Workflow  
```text
Camera Input → Frame Processing → AI Model (YOLOv8) → Animal Detection → Alert Trigger

---

## 📂 Project Structure  
```bash
safemove-detector/
│── safemove_detector.ipynb
│── README.md
│── requirements.txt
│
│── src/
│   ├── detect.py
│   ├── alert.py
│
│── assets/
│   ├── output1.png
│
│── models/
│   └── model_info.txt


