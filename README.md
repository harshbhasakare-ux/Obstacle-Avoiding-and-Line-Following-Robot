# Obstacle-Avoiding-and-Line-Following-Robot
An Arduino UNO based autonomous robot that follows a black line and detects and avoids obstacles using IR sensors and an ultrasonic sensor.
Obstacle Avoiding and Line Following Robot 🤖

📌 Project Overview

This project presents an autonomous mobile robot developed using Arduino UNO R3. The robot can follow a black line using IR sensors and detect obstacles using an ultrasonic sensor. When an obstacle is detected, the robot performs an avoidance movement and continues its operation.

🎯 Objectives

- Develop an autonomous robotic vehicle.
- Follow a predefined black line.
- Detect obstacles using ultrasonic sensing.
- Avoid obstacles without human intervention.
- Improve practical knowledge of embedded systems and robotics.

🛠️ Hardware Components

1. Arduino UNO R3
2. L298N Motor Driver
3. Two IR Sensors
4. HC-SR04 Ultrasonic Sensor
5. Servo Motor
6. Two BO DC Motors
7. Robot Chassis with Two Wheels
8. Battery Supply
9. Connecting Wires

💻 Software Requirements

- Arduino IDE
- Embedded C / Arduino C++
- Arduino UNO Board Package

🔌 Pin Connections

Component| Arduino Pin
ENA| D6
IN1| D13
IN2| D12
IN3| D11
IN4| D10
ENB| D5
Right IR Sensor| D2
Left IR Sensor| D4
Ultrasonic TRIG| D9
Ultrasonic ECHO| D8
Servo Motor| D3

⚙️ Working Principle

1. Line Following

The two IR sensors detect the black line and white surface. Arduino processes the sensor readings and controls the motors through the L298N motor driver.

2. Obstacle Detection

The HC-SR04 ultrasonic sensor measures the distance between the robot and an obstacle.

3. Obstacle Avoidance

When an obstacle is detected within the programmed distance, the robot stops and performs the programmed avoidance movement before continuing.

📊 Applications

- Autonomous robotics
- Industrial automation
- Smart transportation
- Educational robotics
- Embedded systems learning

🚀 Future Scope

- Bluetooth and Wi-Fi control
- Advanced path planning
- PID-based line following
- Improved obstacle detection
- IoT-based robot monitoring

👨‍💻 Developed By

Student Name: Harshad Bhasakare

Branch: Electronics and Telecommunication Engineering

Project: Obstacle Avoiding and Line Following Robot

📜 License

MIT License (if selected for this repository).
