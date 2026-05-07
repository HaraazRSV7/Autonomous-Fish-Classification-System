# Autonomous-Fish-Classification-System
AI-powered embedded system for real-time fish classification using computer vision, load cell weight measurement, and automated sorting mechanism.
# 🐟 Autonomous Fish Classification System

## 📌 Overview

This project presents an **AI-powered embedded system** for real-time fish classification, measurement, and automated sorting.
The system integrates **computer vision, embedded control, and sensor fusion** to create a fully autonomous pipeline.

---

## 🚀 Key Features

* 🎯 Real-time fish classification using deep learning
* 📏 Length & breadth measurement using calibrated vision system
* ⚖️ Weight measurement using load cell (HX711)
* 🔄 Automated sorting using rotating mechanism
* ⚙️ Conveyor belt control using ESP32

---

## 🧠 System Workflow

1. Fish moves on conveyor belt
2. System detects object and stops motor
3. Image is captured using camera
4. AI model classifies the fish
5. Length and breadth are calculated
6. Weight is received via serial communication
7. Sorting mechanism rotates to corresponding bin

---

## 🛠️ Technologies Used

* Python (OpenCV, NumPy, PySerial)
* Embedded C (Arduino / ESP32)
* Computer Vision
* Serial Communication
* Load Cell + HX711
* BTS7960 Motor Driver

---

## 📊 Classification Classes

| Index | Fish Type |
| ----- | --------- |
| 0     | Shrimp    |
| 1     | Pomfret   |
| 2     | Anchovy   |
| 3     | Squid     |

---

## 🔌 Hardware Components

* ESP32 DevKit V1
* BTS7960 Motor Driver
* Load Cell + HX711
* Camera Module
* Conveyor Belt System

---

## 📷 System Images

### 🔧 Components
![Components](images/Components.jpeg)

### ⚙️ Setup
![Setup](images/Setup.jpeg)

### 🖥️ Output Preview
![Preview](images/Preview.jpeg)

---

## 🎥 Demo Video

[Watch Full Working Demo](https://drive.google.com/file/d/1_0Y5c_GmgK2eiabp7oEDJx_V0vhfs0MH/view?usp=drive_link)
---

## 📂 Project Structure

autonomous-fish-classification-system/
│
├── python_code/
├── arduino_code/
├── model/
├── images/
├── videos/
└── docs/

---

## 📈 Future Improvements

* Improve classification accuracy
* Add real-time cloud monitoring
* Optimize processing speed for edge deployment

---

## 👤 Author

**Ravisankar V**
