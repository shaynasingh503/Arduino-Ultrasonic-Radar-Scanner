# 📡 Arduino Ultrasonic Radar Scanner

<p align="center">

🚀 **A Real-Time Radar Simulation using Arduino UNO, HC-SR04 Ultrasonic Sensor, Servo Motor & Processing IDE**

⭐ Detect Objects | 📏 Measure Distance | 🎯 Visualize in Real-Time

</p>

---

## 📖 Project Overview

The **Arduino Ultrasonic Radar Scanner** is an embedded systems project that simulates the working of a radar. It combines **hardware** and **software** to detect nearby objects and display them on an interactive radar interface.

The **HC-SR04 Ultrasonic Sensor** is mounted on a **Servo Motor**, allowing it to rotate between **15° and 165°**. During each scan, the sensor measures the distance of objects and sends the information to the **Processing IDE** via serial communication.

The Processing application visualizes the scanning process as a **green radar arc**, while detected objects appear as **red dots**, creating a realistic radar effect.

---

## 🎓 Project Details

🏫 **Associated With:** Vellore Institute of Technology

📅 **Duration:** February 2024 – May 2024

🎯 **Domain:** Embedded Systems | IoT | Arduino

---

# ✨ Features

✅ Real-Time Object Detection

✅ Interactive Radar Visualization

✅ Servo Controlled Scanning (15°–165°)

✅ Detects Objects within 20 cm Radius

✅ Arduino & Processing Integration

✅ Live Serial Communication

✅ Easy to Build and Understand

---

# 🛠 Hardware Components

| 🔧 Component | 📌 Quantity |
|-------------|------------|
| Arduino UNO | 1 |
| HC-SR04 Ultrasonic Sensor | 1 |
| SG90 Servo Motor | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |
| USB Cable | 1 |

---

# 💻 Software Used

- 🖥 Arduino IDE
- 🎨 Processing IDE
- 💡 Embedded C
- 🔌 Serial Communication

---

# ⚙️ Working Principle

### 🔄 Step 1

The **Servo Motor** continuously rotates from **15° to 165°**.

⬇️

### 📡 Step 2

The **HC-SR04 Ultrasonic Sensor** emits ultrasonic waves.

⬇️

### 📏 Step 3

The sensor receives the reflected waves and calculates the object's distance.

⬇️

### 💬 Step 4

Arduino sends the **Angle + Distance** through Serial Communication.

⬇️

### 🖥 Step 5

Processing IDE receives the data.

⬇️

### 🎯 Step 6

Detected objects appear as **Red Dots** on a **Green Radar Screen**.

⬇️

### 🔁 Step 7

The scanning process repeats continuously for real-time monitoring.

---

# 📸 Hardware Setup

<p align="center">
<img width="568" height="611" alt="Screenshot 2026-07-02 132606" src="https://github.com/user-attachments/assets/58ed3cb0-ed98-43fa-8ff2-a7ef652798c5" />
</p>

---

# 🔌 Circuit Diagram

<p align="center">
<img width="827" height="485" alt="Screenshot 2026-07-02 142850" src="https://github.com/user-attachments/assets/5804dd01-1169-4130-a354-c071f46fe195" />


---

# 📊 Radar Output

<p align="center">
<img width="577" height="335" alt="Radar jpg" src="https://github.com/user-attachments/assets/9d25c6ab-f3b7-407c-a81c-3cd5195e8a42" />

---

# 📂 Project Structure

```
Arduino-Ultrasonic-Radar-Scanner
│
├── Arduino_Code
│     └── RadarScanner.ino
│
├── Processing_Code
│     └── RadarDisplay.pde
│
├── Images
│     ├── radar_setup.jpg
│     ├── circuit_diagram.png
│     ├── output.png
│     └── working.gif
│
├── Video
│     └── demo.mp4
│
├── README.md
└── LICENSE
```

---

# 🚀 Technologies Used

🟢 Arduino Programming

🟢 Embedded C

🟢 Processing IDE

🟢 Sensor Interfacing

🟢 Embedded Systems

🟢 IoT

🟢 Serial Communication

---

# 🌟 Applications

📡 Mini Radar System

🚗 Obstacle Detection

🤖 Robotics

🏠 Smart Automation

🚁 Drone Navigation

🚘 Autonomous Vehicles

🎓 Educational Demonstration

---

# 🔮 Future Enhancements

✨ Increase Detection Range

📶 Add Bluetooth Connectivity

🌐 IoT-Based Remote Monitoring

🛰 360° Scanning using Stepper Motor

📱 Mobile Application Integration

📊 Data Logging

🧠 AI-Based Object Recognition

---

# 📈 Project Highlights

🎯 Real-Time Detection

⚡ Fast Response

🔄 Continuous Scanning

💻 Hardware + Software Integration

🛠 Beginner Friendly

📚 Excellent Embedded Systems Learning Project

---

# 👩‍💻 Author

## Shayna Singh

🎓 Final Year B.Tech (ECE)

🏫 VIT Bhopal University

💡 Passionate about Embedded Systems, IoT & Smart Electronics

🌟 Building Real-World Hardware + Software Solutions

---

# ⭐ If you found this project useful...

### 🌟 Please consider giving it a ⭐ on GitHub!

It motivates me to build more exciting Embedded & IoT Projects. 🚀✨
