# Fire and Smoke Alert System

## Overview
Fire and Smoke Alert System is an IoT-based safety solution designed to detect fire hazards and smoke in real time using ESP32 and multiple sensors.

The system continuously monitors temperature and smoke levels and automatically triggers emergency alerts when dangerous conditions are detected.

---

## Features
- 🔥 Fire Detection
- 🌫 Smoke Detection
- 🚨 Automatic Alarm System
- 📱 Blynk Mobile Notifications
- 💧 Automatic Pump Activation
- 📟 LCD Live Monitoring
- ⚡ Real-Time Sensor Data

---

## Problem Statement
Fire accidents in homes, industries, and workplaces can cause severe damage and loss.

Manual monitoring is unreliable, so an automated detection and alert system is required.

---

## Solution
This system continuously monitors:

- Temperature level
- Smoke concentration

When critical values are reached, the system:

1. Activates buzzer alarm
2. Turns on warning LED
3. Starts water pump
4. Sends mobile notification
5. Displays emergency alert on LCD

---

## Hardware Components
- ESP32
- DHT22 Temperature Sensor
- Smoke Sensor
- LCD I2C Display
- Servo Motor
- Relay Module
- Buzzer
- LEDs

---

## Software & Tools
- Arduino IDE
- Blynk IoT Platform
- Embedded C / Arduino C++
- Wokwi Simulator

---

## Working Principle
1. Sensor reads temperature and smoke values
2. ESP32 processes sensor data
3. Threshold conditions are checked
4. If danger is detected:
   - Alarm turns ON
   - Pump activates
   - Notification sent
5. System returns to normal after safe readings

---

## Emergency Conditions
Emergency mode activates when:

- Temperature > 45°C
- Smoke Level > 50%

---

## Future Improvements
- GSM Emergency Calling
- AI-Based Fire Prediction
- Cloud Monitoring Dashboard
- Battery Backup
- Multi-Zone Fire Detection

---

## Author
**Yash Sharma**  
B.Tech ECE Student  
Rustamji Institute of Technology (RJIT)  
VLSI | AI | IoT Enthusiast
