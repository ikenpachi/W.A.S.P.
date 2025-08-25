# W.A.S.P. – Wireless Autonomous Surveillance Platform

> A modular, mobile and autonomous surveillance platform with wireless data collection, remote control, and cybersecurity applications.

---

## About the Project

**W.A.S.P.** (Wireless Autonomous Surveillance Platform) is an experimental system that combines mobility, real-time data gathering, and offensive cybersecurity concepts. It integrates:

-  **Vespa Board (ESP32-based motor controller)** – manages movement, obstacle detection, battery monitoring, and the main web interface.
-  **Responsive Web Interface** – designed for mobile use, allowing full control and monitoring via browser.

---

## Requirements

### Hardware

- Vespa Board (ESP32 + motor driver)
- HC-SR04 ultrasonic sensor
- USB cable, basic battery, and chassis

### Software

- Arduino IDE or PlatformIO
- Required libraries:
  - `ESPAsyncWebServer`
  - `AsyncTCP`
  - `ArduinoJson`
  - `esp_now`
  - `RoboCore_Vespa` (custom motor control library)

---

## Connect to the system

### The Vespa board creates a Wi-Fi AP:
-  WASP / 12345678

### Connect via your smartphone
Open browser and go to:
-  http://192.168.4.1

---

## Project Structure 

W.A.S.P/
├── vespa_controller.ino         # Main code for Vespa vehicle
├── /assets/                     # Logos, mockups, and diagrams
├── /docs/                       # Planning, tests, architecture drafts
└── README.md
