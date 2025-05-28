# Radar-System
Radar System Using ESP8266, Ultra Sonic Sensor(HC-SR01), Servo Motor(SG90) and Controlling With Blynk

Radar System Using ESP8266, Ultrasonic Sensor (HC-SR04), Servo Motor (SG90), and Blynk Control
This project demonstrates a real-time Radar System built using the ESP8266 NodeMCU, HC-SR04 ultrasonic sensor, and a SG90 servo motor, with mobile app integration using Blynk for control and monitoring.

📡 Project Overview
The system simulates a radar scanner that rotates the ultrasonic sensor using a servo motor to detect objects within its range. The distance data is sent via Wi-Fi (MQTT/Blynk) and visualized on a mobile application (Blynk) and optionally on a Processing-based radar GUI.

🔧 Components Used
ESP8266 NodeMCU

HC-SR04 Ultrasonic Sensor

SG90 Servo Motor

Blynk IoT Mobile App

Jumper Wires, Breadboard, USB Cable

🧠 Features
Servo motor sweeps the ultrasonic sensor from 0° to 180°.

Real-time distance detection using HC-SR04.

Object data transmitted via Wi-Fi using Blynk.

Mobile app dashboard for start/stop control and live distance data.

(Optional) Radar visualization using Processing IDE.

📲 Mobile App (Blynk)
Start/Stop button to control radar sweep.

Live distance display from ultrasonic sensor.

Virtual pins used for seamless interaction between NodeMCU and Blynk.

📡 Data Visualization (Optional)
Processing IDE script for radar sweep simulation.

Displays real-time angle and distance arcs.

💻 Folder Structure
bash
Copy
Edit
/Radar-System-ESP8266
│
├── Arduino_Code/           # ESP8266 sketch (Radar + Blynk)
├── Processing_GUI/         # Radar visualization code (optional)
├── Blynk_Setup.md          # Blynk configuration instructions
├── Schematics/             # Circuit diagram and setup images
└── README.md               # Project overview and documentation
🛠️ Getting Started
Connect the components as per circuit diagram.

Flash the provided Arduino code to ESP8266 using Arduino IDE.

Set up Blynk app with correct auth token and virtual pins.

(Optional) Run Processing sketch for visual radar display.

🎓 Project Info
Branch: CS (IoT)-B, Department of Internet of Things

Institution: NIET College

Team Members:

Sohail Raza (2101331550074)

Supervisor: Mushtaq Ahmed Rather

Submitted: May 2025

