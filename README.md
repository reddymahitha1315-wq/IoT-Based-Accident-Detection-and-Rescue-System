# IoT Based Automatic Vehicle Accident Detection and Rescue System

Capstone Project - Audisankara Institute of Technology (2022-2026) | ECE

### 📋 Abstract
This system automatically detects vehicle accidents using vibration/impact sensors and sends real-time GPS location to emergency contacts via GSM/Wi-Fi. It reduces rescue time and can save lives by avoiding manual reporting delays.

### 🛠️ Hardware Used
- Arduino Uno (ATmega328)
- Vibration Sensor / Accelerometer (ADXL335)
- GPS Module (NEO-6M)
- GSM Module (SIM800L) / WiFi Module
- LCD Display 16x2
- Buzzer / Alarm

### ⚙️ How It Works
1. Vibration sensor continuously monitors impact threshold
2. When threshold exceeds (accident detected), microcontroller triggers
3. GPS fetches exact latitude/longitude
4. GSM sends SMS alert: "Accident detected at Location: https://maps.google.com/?q=lat,long" to guardian/rescue team
5. Buzzer + LCD displays alert status

### 💻 Tech Stack
Arduino C, Embedded Systems, IoT, GPS, GSM

### 🎯 Key Features
- Real-time accident detection
- Automatic SMS with Google Maps link
- Low-cost, scalable, fast response
- Tested prototype with accurate location tracking

### 🚀 Future Scope
- Mobile App for live tracking
- AI/ML to reduce false alarms
- Direct integration with hospitals & police

### 📄 Project Report
Full report PDF is available in this repository.
