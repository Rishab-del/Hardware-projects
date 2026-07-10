# 🔐 Arduino Password Protected Door Lock System

An Arduino-based smart door lock system that uses a keypad for password authentication. The system unlocks the door by rotating a servo motor when the correct password is entered. A green LED indicates successful access, while a red LED and buzzer alert the user when an incorrect password is entered.

## ✨ Features

- 🔑 Password-based authentication
- 🔒 Servo motor door locking mechanism
- ✅ Green LED indicates successful authentication
- ❌ Red LED indicates incorrect password
- 🔊 Buzzer alarm for wrong password attempts
- 📟 16x2 LCD displays system status
- ⌨️ 4x4 Keypad for password input
- ⚡ Real-time access control

---

## 🛠 Hardware Components

- Arduino Uno
- 4×4 Matrix Keypad
- Servo Motor (SG90)
- 16x2 LCD Display (I2C/Parallel)
- Green LED
- Red LED
- Buzzer
- Breadboard
- Jumper Wires
- USB/5V Power Supply

---

## 💻 Software

- Arduino IDE
- Embedded C / Arduino C++

---



## ⚙️ Working Principle

1. The user enters a password using the keypad.
2. Arduino compares the entered password with the stored password.
3. If the password is correct:
   - The LCD displays **"Access Granted"**.
   - The green LED turns ON.
   - The servo motor rotates to unlock the door.
   - After a short delay, the servo returns to the locked position.
4. If the password is incorrect:
   - The LCD displays **"Access Denied"** or **"Wrong Password"**.
   - The red LED turns ON.
   - The buzzer sounds to indicate an invalid attempt.


## 🚀 Future Improvements

- RFID Authentication
- Fingerprint Sensor Integration
- OTP Verification
- Bluetooth App Control
- Wi-Fi & IoT Monitoring
- OLED Display
- Multiple User Password Support
- Password Change Feature
- Intruder Detection with Camera

---

## 📚 Concepts Used

- Embedded Systems
- Arduino Programming
- Servo Motor Control
- Password Authentication
- LCD Interfacing
- Keypad Interfacing
- Digital Input/Output
- Access Control Systems

---

## 👨‍💻 Author

**Rishabh Patel**

B.Tech CSE | Robotics & Embedded Systems Enthusiast

---

## ⭐ If you like this project, don't forget to Star the repository!
