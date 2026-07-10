# 🚗 Arduino Smart Robot Car

An Arduino-based 4WD Smart Robot Car capable of autonomous navigation using multiple sensors and control modes. The robot combines **Obstacle Avoidance**, **Light Following**, and **IR Remote Control**, demonstrating embedded systems, robotics, motor control, and sensor integration using Arduino.

---

## 📌 Features

- 🚗 4WD robotic platform
- ⚡ Arduino-based control system
- 🔋 Rechargeable battery powered
- 🚧 Obstacle avoidance using an ultrasonic sensor
- 💡 Light following using dual LDR sensors
- 🎮 Wireless control using an IR remote
- 📏 Real-time distance measurement
- ⚙️ Motor speed and direction control
- 🔄 Autonomous navigation
- 🛠 Modular and expandable design

---

## 🛠 Hardware Used

- Arduino Uno
- L298N Motor Driver
- HC-SR04 Ultrasonic Sensor
- 2 × LDR Sensors
- IR Receiver Module
- IR Remote Control
- 4 × DC Geared Motors
- 4 × Robot Wheels
- Acrylic Chassis
- 18650 Battery Pack
- Breadboard
- Jumper Wires
- Power Switch

---

## 💻 Software

- Arduino IDE
- Embedded C / Arduino C++

---

## ⚙️ Working

### 🚧 Obstacle Avoidance Mode

1. The ultrasonic sensor continuously measures the distance in front of the robot.
2. If an obstacle is detected within the predefined distance:
   - The robot stops.
   - Moves backward.
   - Changes its direction.
   - Continues moving safely.

### 💡 Light Following Mode

1. Two LDR sensors continuously detect light intensity.
2. The robot moves toward the brighter light source.
3. It automatically turns left or right based on sensor readings.

### 🎮 IR Remote Control Mode

1. The IR receiver receives commands from the remote.
2. Users can control:
   - Forward
   - Backward
   - Left
   - Right
   - Stop

---

## 🚀 Future Improvements

- 📱 Bluetooth Control
- 🌐 Wi-Fi & IoT Integration
- 📷 Camera Module
- 🤖 AI Object Detection
- 🛣️ Line Following using IR Sensors
- 📍 GPS Navigation
- 📡 Mobile App Control
- 🔋 Battery Level Monitoring

---

## 📚 Concepts Used

- Arduino Programming
- Embedded Systems
- Robotics
- Motor Control
- Ultrasonic Sensor Interfacing
- LDR Sensor Interfacing
- IR Remote Communication
- Autonomous Navigation
- Obstacle Avoidance

---

## 👨‍💻 Author
**Rishabh Patel**  
B.Tech CSE, IIIT-Delhi  
Passionate about Robotics, Embedded Systems, IoT, and Full-Stack Development.

## ⭐ If you found this project useful, don't forget to Star the repository!
