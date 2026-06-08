# Non-Invasive BPM and Glucose Estimator

## 🩺 Overview

The Non-Invasive BPM and Glucose Estimator is an ESP32-based smart healthcare monitoring system designed to measure heart rate (BPM) and estimate glucose trends without invasive blood sampling. The system combines biomedical sensors, embedded processing, machine learning, and an OLED-based user interface to provide real-time health monitoring and disease prediction. :contentReference[oaicite:0]{index=0}

This project demonstrates the integration of IoT, biomedical engineering, and artificial intelligence to develop an affordable and portable healthcare monitoring solution for educational and research applications.

---

## 🚀 Key Features

- Real-time Heart Rate (BPM) Monitoring
- Non-Invasive Glucose Trend Estimation
- OLED Display Interface
- 4×3 Keypad User Interaction
- ESP32 Embedded Processing
- Machine Learning Disease Prediction
- Portable and Low-Cost Design
- Real-Time Sensor Monitoring
- Menu-Based Navigation System
- Health Status Classification

---

## 🛠 Hardware Components

| Component | Function |
|------------|------------|
| ESP32 | Main Controller |
| MAX30102/MAX30105 Sensor | Heart Rate Monitoring |
| IR Sensor | Glucose Trend Estimation |
| OLED Display (0.96") | User Interface |
| 4×3 Keypad | User Input |
| Li-ion Battery | Portable Power Source |
| TP4056 Charging Module | Battery Charging |
| Custom PCB/Perfboard | Hardware Integration |

The hardware includes an ESP32 board, OLED display, MAX30102 pulse oximeter sensor, IR sensor module, and keypad interface integrated into a portable embedded platform. :contentReference[oaicite:1]{index=1}

---

## ⚙ System Architecture

Sensor Acquisition

↓

Signal Processing

↓

Heart Rate Calculation

↓

Glucose Trend Estimation

↓

Machine Learning Prediction

↓

OLED Display Output

---

## 🤖 Machine Learning Integration

A Decision Tree Machine Learning model is integrated into the ESP32 firmware to classify health conditions based on physiological parameters. The model uses:

- Age
- Weight
- Height
- Estimated Glucose Level
- Heart Rate (BPM)

The system predicts:

- Hypoglycemia
- Normal Condition
- Hyperglycemia
- Tachycardia
- Bradycardia

The embedded decision tree model performs threshold-based classification directly on the ESP32 microcontroller. :contentReference[oaicite:2]{index=2}

---

## 📊 User Interface

The OLED display provides:

- Main Menu
- BPM Monitoring
- Glucose Estimation
- Combined Monitoring Mode
- Disease Prediction Results
- System Status Messages

The keypad allows users to:

- Select monitoring modes
- Enter personal information
- Navigate menus
- View prediction results

---

## 💻 Software Stack

- Arduino IDE
- ESP32 Framework
- C++
- Embedded Machine Learning
- SSD1306 OLED Library
- Wire Library
- MAX30102 Sensor Library
- Decision Tree Classification

---

## 📂 Repository Structure

```text
Non-Invasive-BPM-Glucose-Estimator
│
├── README.md
├── heart_rate_glocose_AI.ino
├── disease_model.h
├── non_invasive_model.ipynb
├── Non-Invasive BPM and Glucose Trend Estimator.pdf
├── Circuit_Diagram.png
├── Hardware_Image_01.jpeg
├── Hardware_Image_02.jpeg
├── Hardware_Image_03.jpeg
├── Hardware_Image_04.jpeg
├── Hardware_Image_05.jpeg
└── LICENSE
```

---

## 🎯 Applications

- Smart Healthcare Monitoring
- Biomedical Engineering Research
- Embedded AI Systems
- IoT Healthcare Devices
- Educational Medical Projects
- Remote Health Monitoring
- Health Screening Systems

---

## 🔬 Future Improvements

- Mobile Application Integration
- Cloud-Based Data Storage
- Bluetooth Connectivity
- Advanced Deep Learning Models
- Improved Glucose Estimation Accuracy
- Wearable Device Implementation
- Telemedicine Support

---

## 📸 Project Demonstration

The system successfully:

- Measures heart rate in real time.
- Estimates glucose trends using sensor data.
- Processes physiological information using ESP32.
- Predicts health conditions through machine learning.
- Displays results through a compact OLED interface.
- Provides an easy-to-use keypad-driven menu system.

---

## 👨‍💻 Author

### Muhammad Abdullah

BS Software Engineering  
The Islamia University of Bahawalpur (IUB), Pakistan

Research Interests:

- Artificial Intelligence
- Biomedical Engineering
- Embedded Systems
- Internet of Things (IoT)
- Machine Learning
- Healthcare Technology

---

## 👨‍🏫 Research Mentor

### Dr. Engr. Dileep Kumar

Faculty of Engineering  
Department of Electronic Engineering  
The Islamia University of Bahawalpur (IUB)

---

## 📜 License

This project is released under the MIT License.

---

## ⭐ Acknowledgment

This project was developed to explore the integration of biomedical sensing, embedded systems, and machine learning for affordable, portable, and non-invasive healthcare monitoring applications.
