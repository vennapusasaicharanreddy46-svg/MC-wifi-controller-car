# 🚗📱 WiFi Controlled Car using ESP8266

> A WiFi-based smart robotic vehicle controlled using a mobile application.

---

## 📌 Overview

The **WiFi Controlled Car** is an IoT-based robotic vehicle built using the ESP8266 (NodeMCU) microcontroller. The car is wirelessly controlled through a mobile application over a WiFi network.

The ESP8266 acts as the brain of the system, receiving commands from the mobile app and controlling DC motors via the L298N motor driver module. This project demonstrates wireless communication, embedded systems design, and real-time motor control.

---

## ✨ Key Features

* 📶 WiFi-based control (No Bluetooth required)
* 📱 Controlled using Mobile Application
* 🔄 Real-time Forward, Backward, Left, Right & Stop control
* ⚡ Fast response with low latency
* 🔋 Battery-powered and portable
* 🔧 Expandable for IoT and surveillance applications

---

## 🛠️ Hardware Components

* ESP8266 NodeMCU
* L298N Motor Driver Module
* DC Motors (2 or 4)
* Robot Chassis
* 7.4V / 12V Battery
* Jumper Wires

---

## ⚙️ Working Principle

1. The ESP8266 connects to a WiFi network.
2. The mobile app sends control commands over WiFi.
3. The ESP8266 receives these commands.
4. Based on the command, it sends control signals to the L298N motor driver.
5. The motor driver controls the rotation and direction of DC motors.
6. The car moves accordingly.

---

## 📱 Mobile App Control

The mobile application includes buttons for:

* ⬆️ Forward
* ⬇️ Backward
* ⬅️ Left
* ➡️ Right
* ⏹️ Stop

The app communicates with the ESP8266 using HTTP requests over WiFi.

---

## 🚀 Setup Instructions

1. Install Arduino IDE.
2. Add ESP8266 board support.
3. Upload the provided `.ino` file to NodeMCU.
4. Connect motors to L298N.
5. Power the system.
6. Connect mobile app to the ESP8266 IP address.
7. Start controlling the car.

---

## 📂 Project Structure

```
WiFi-Controlled-Car/
│
├── code/
│   └── wifi_car.ino
├── images/
├── circuit/
└── README.md
```

---

## 🔮 Future Enhancements

* Add ESP32-CAM for live video streaming
* Obstacle avoidance using ultrasonic sensor
* Speed control using PWM
* Internet-based control from anywhere
* Voice control integration

---

## 📌 Applications

* Surveillance robots
* Military robotic systems
* Industrial automation
* Smart IoT robotics
