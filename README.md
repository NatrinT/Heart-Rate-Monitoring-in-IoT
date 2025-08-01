# 💓 HEARTSYNC - Real-Time Heart Rate Monitoring with IoT

HEARTSYNC is an IoT-based system designed to monitor heart rate in real-time. It aims to assist elderly individuals or patients with heart conditions by continuously tracking their heart rate and sending alerts when abnormalities are detected.

---

## 📌 Overview

Monitoring heart rate is crucial for tracking personal health, especially for the elderly or those with heart conditions. Traditional hospital-based checks can be inconvenient and infrequent.  
**HEARTSYNC** provides a portable, real-time solution using sensors and IoT technology, allowing users and caregivers to monitor vital signs anytime, anywhere.

---

## 🎯 Objectives

- Develop an IoT system capable of real-time heart rate monitoring
- Enable users to track and log heart rate data through a mobile app or web interface
- Implement an alert system to notify users when heart rate anomalies are detected

---

## ✅ Benefits

1. **24/7 Monitoring** – Continuous heart rate tracking without the need for hospital visits  
2. **Smart Alerts** – Instant notifications when abnormal heart rate is detected  
3. **Long-Term Data Logging** – Save heart rate history for medical consultation  
4. **Improved Emergency Response** – Early detection helps reduce the risk of serious cardiac events  

---

## ⚙️ How It Works

1. The **MAX30102 sensor** measures heart rate  
2. Data is processed by the **ESP32-C3 board**  
3. If the heart rate is abnormal, the system:
   - Sends real-time alerts (via Telegram)
   - Logs the data (to Google Sheets)
4. Users can view current and past data via a mobile app or web dashboard

---

## 🔧 Hardware Components

| Component | Description |
|----------|-------------|
| ESP32-C3 | Microcontroller with Wi-Fi & Bluetooth |
| MAX30102 | Heart rate & SpO2 sensor |
| OLED I2C | Display screen for real-time values |
| Li-Po Battery | Portable power source |
| TP4056 | Battery charging module |
| Jumper Wires | Connections between modules |

---

## 💻 Software Stack

| Tool/Platform | Purpose |
|---------------|--------|
| Arduino IDE | Firmware development |
| Blynk | Mobile app integration |
| Google Sheets | Cloud-based data logging |
| Telegram | Real-time alert notifications |

---

## 📊 Results

- Successfully monitors heart rate in real-time  
- Provides alerts for abnormal heart rate values  
- Enables remote and long-term tracking of user health data  
- Enhances convenience and health safety for at-risk users  

---
![Poster](https://github.com/NiraphatK/Heart-Rate-Monitoring-with-IoT/blob/main/Poster%20HeartSync.png)
