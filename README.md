# 🐾 Cat-Dispenser - Intelligent Treat Dispenser for Pets

<p align="center">
  <img src="https://github.com/SerMirak/Cat-Dispenser/blob/main/logo%201.png" alt="Cat-Dispenser Logo" width="200">
</p>

## 📖 Description

**Cat-Dispenser** is an innovative project designed to simplify the lives of pet owners. This smart treat dispenser leverages accessible and high-performing technologies like Arduino, combined with sensors and an ESP32-S3 microcontroller, to deliver an automated and connected experience.

The project stands out for its ergonomic design, ease of use, and efficiency, allowing precise treat dispensing both automatically and manually via a mobile app.

---

## 🛠️ Features

- **Automated and Scheduled Dispensing**: 
  - Dispenses treats at pre-defined times using an internal clock.
- **Remote Manual Control**: 
  - Treat dispensing triggered via a Wi-Fi-connected mobile application.
- **Treat Level Monitoring**: 
  - Ultrasonic Ranger for real-time monitoring of treat reserves.
- **Robust and Safe Design**: 
  - 3D-printed PLA structure ensures safe, durable, and daily use.
- **Reliability and Ease of Use**: 
  - Intuitive design, ideal for all users.

---

## 📑 Technologies and Components Used

- **Electronics:**
  - ESP32-S3 microcontroller for global control and connectivity.
  - Ultrasonic Ranger to detect treat levels.
  - Stepmotor to activate the dispensing mechanism.
  - LED to indicate distributor status.
  - The OLED screen displays the scheduled times for the three meals, the current time, and if it is well-connected to blynk.
  - Button for manual dispensing.
  - External power supply to provide a stable power supply for the motor.
- **3D Printing:**
  - Structure and reservoir printed using PLA filament for lightweight and durable design.
- **Programming:**
  - C++ development to manage sensors, Wi-Fi interface, and motor control.
- **Mobile Application:**
  - Connected interface for remote control of functionalities.

---

## 🧪 Tests and Results

### Validated Features
- Precise treat dispensing in both automatic and manual modes.
- Reliable monitoring of treat levels using the ultrasonic sensor.
- Robust design, ensuring safety for pets and internal components.

### Performance Analysis
- **Precision**: Consistently accurate treat dispensing.
- **Reliability**: Extended testing validates the robustness of components and their integration.
- **Ergonomics**: User interface is intuitive and easy to operate.

---

## 🚀 Future Improvements

- **Enhanced Sensors**: Improve calibration or add additional sensors for better accuracy.
- **Adaptable Mechanism**: Optimize the system to handle treats of various shapes and sizes.
- **Energy Efficiency**: Add a sleep mode to reduce power consumption during idle periods.
- **Compact and Aesthetic Design**: Redesign the enclosure for a sleeker and more adaptable product.
- **Extended Features**: Introduce a water dispensing system with level monitoring and notifications.

---

## 🗂️ Project Structure

1. **Hardware:**
   - ESP32-S3, Ultrasonic Ranger, Stepmotor, OLED screen, LED, Button for manual dispensing, external power supply.
2. **Schematics and Diagrams:**
   - Logical and assembly diagrams
3. **Source Code:**
   - Manages sensors, motors, OLED screen? Wi-Fi interface.


