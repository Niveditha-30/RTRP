📌 Project Overview

This project presents an IoT-based Home Security System developed using the ESP32-CAM module and a PIR/IR motion sensor.
The system detects human movement, captures images in real-time, and sends alerts to the user via Telegram.

It is a cost-effective, smart, and automated security solution designed for modern homes.

🎯 Objectives
Detect human motion using PIR/IR sensors
Capture images using ESP32-CAM
Send real-time alerts to users via Telegram
Enable remote monitoring through IoT
Provide a low-cost and easy-to-install security system
⚙️ Features
📡 Real-time motion detection
📷 Automatic image capture
📲 Instant Telegram notifications
🔔 Buzzer alert for intrusion
🌐 Wi-Fi enabled communication
🔄 Continuous monitoring system
🧰 Technologies Used
Hardware: ESP32-CAM, PIR Sensor, Buzzer, LED
Software: Arduino IDE
Programming Language: Embedded C (Arduino)
Communication: Wi-Fi, Telegram Bot API
🔌 Hardware Components
ESP32-CAM Module
PIR Motion Sensor
Buzzer
LED
Power Supply (5V)
💻 Software Requirements
Arduino IDE
ESP32 Board Package
Required Libraries:
esp_camera.h
WiFi.h
WiFiClientSecure.h
UniversalTelegramBot.h
🏗️ System Architecture

The system consists of the following modules:

Sensing Unit: Detects motion (PIR Sensor)
Processing Unit: ESP32-CAM processes data
Communication Unit: Sends alerts via Wi-Fi
Alert Unit: Buzzer for local alerts
🔄 Working Process
System initializes and connects to Wi-Fi
PIR sensor continuously monitors motion
Motion detected → ESP32-CAM activated
Image captured
Image sent to user via Telegram
Buzzer alert triggered
System returns to monitoring mode
📷 Output
Motion detection alerts
Captured image sent via Telegram
Real-time notifications on smartphone
Limitations
Depends on internet connectivity
Limited camera resolution
No live streaming (current version)
🔮 Future Scope
Face recognition system
Live video streaming
Cloud storage integration
Mobile app development
AI-based object detection
Multi-sensor integration
