# 🏥 IoT Healthcare Multi-Sensor Dataset (Real-Time Collected)

## 📌 Overview

This dataset consists of real-time physiological data collected from an IoT-based healthcare monitoring system. The data is acquired using multiple sensors attached to the human body and transmitted continuously to a cloud platform.

The dataset is used for evaluating secure data transmission and encryption mechanisms in IoT healthcare environments.

---

## ⚙️ Data Collection Setup

The real-time data acquisition system includes:

- Healthcare sensors (ECG, Temperature, BP, SpO₂, etc.)
- Analog sensors connected via Arduino ADC pins
- Two Arduino-based microcontroller units
- ESP8266 Wi-Fi module for cloud connectivity
- MQTT protocol for real-time data transmission

Sensors are physically connected and attached to the subject, enabling continuous monitoring.

---

## 📊 Dataset Details

| Feature       | Description                   |
| ------------- | ----------------------------- |
| Data Type     | Real-time collected           |
| Duration      | 7 Days Continuous Monitoring  |
| Sampling Rate | 1 reading per minute          |
| Total Sensors | 15 (10 healthcare + 5 analog) |

---

## 🧠 Sensor Features

### 🏥 Healthcare Sensors

- ECG
- Temperature (°C)
- Blood Pressure (Systolic & Diastolic)
- Pulse Rate
- SpO₂
- BMI
- Respiration Rate
- Heart Rate
- Body Motion

### ⚡ Analog Sensors

- Analog_1 to Analog_5

These represent raw voltage signals acquired from sensors through the Arduino analog input pins.

---

## 🔍 Data Characteristics

- Continuous real-time streaming data
- Natural physiological variations
- Sensor noise and fluctuations
- Includes normal and abnormal conditions
- Reflects real-world IoT healthcare monitoring behavior

---

## 📁 File Structure

```
iot_healthcare_dataset.csv
README.md
```

---

## 🚀 Usage

This dataset can be used for:

- IoT healthcare system research
- Encryption and secure communication analysis
- Real-time data processing
- Machine learning applications

---

## ⚠️ Ethical Note

The dataset does not include personally identifiable information (PII). All data is collected and used strictly for research purposes.

---

## 📜 License

For academic and research use only.

---

## 👤 Author

Somireddy Pavani
Department of Information Technology
Teegala Krishna Reddy Engineering College
Hyderabad, Telangana-500097, India

---

## 📬 Contact

Corresponding Author: Somireddy Pavani
Email: pavani.somireddy@tkrec.ac.in

For further information regarding the dataset and research work, please contact the corresponding author.