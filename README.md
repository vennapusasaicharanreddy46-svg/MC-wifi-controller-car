# MC-wifi-controller-car
WiFi Controlled Car using ESP8266 is a wireless robotic vehicle operated through a smartphone or laptop via WiFi. The ESP8266 acts as the controller and web server, receiving commands and controlling DC motors through an L298N driver. It demonstrates IoT, wireless communication, and real-time motor control applications.
🚗 WiFi Controlled Car using ESP8266
📌 Overview

This project is a WiFi Controlled Robotic Car built using the ESP8266 (NodeMCU) microcontroller. The car can be controlled wirelessly using a smartphone or laptop through a web browser. The ESP8266 hosts a web server that provides control buttons for movement.

This project demonstrates IoT-based wireless control, embedded systems programming, and motor driver interfacing.

🎯 Features
WiFi-based wireless control
mobile app required
Forward, Backward, Left, Right, and Stop controls
Real-time motor response
Expandable for camera or sensor integration
🛠️ Components Used
ESP8266 NodeMCU
L298N Motor Driver Module
DC Motors (2 or 4)
Robot Chassis
7.4V / 12V Battery
Jumper Wires
⚙️ Working Principle
The ESP8266 creates a WiFi network or connects to an existing WiFi.
It hosts a web server with control buttons.
When a button is pressed, a command is sent to the ESP8266.
The ESP8266 processes the command and controls the motors via the L298N motor driver.
The car moves according to the selected direction.
🚀 How to Use
Install Arduino IDE.
Add ESP8266 board support in Arduino IDE
Upload the provided code to NodeMCU.
Connect motors via L298N.
Power the system.
Connect your phone/laptop to the ESP8266 WiFi.
Open the IP address in a browser.
Control the car.
📂 Project Structure
WiFi-Controlled-Car/
│
├── code/
│   └── wifi_car.ino
├── circuit_diagram/
├── images/
└── README.md
🔮 Future Improvements
Add ESP32-CAM for live streaming
Add obstacle avoidance sensor
Mobile app control
Internet-based control from anywhere
Speed control using PWM
📌 Applications
Surveillance robot
Military robot prototype
Industrial automation
Smart robotics learning project
