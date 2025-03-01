# Obstacle-Detecting Vehicle 🚗🔍

## Overview
This project is an **Arduino-based Obstacle-Detecting Vehicle** that autonomously moves left or right based on detected obstacles. It utilizes an **ultrasonic sensor** to measure distances and make navigation decisions, ensuring smooth movement in a given environment.

## Features
✅ **Autonomous Navigation** – The vehicle detects obstacles and decides whether to move left or right.  
✅ **Ultrasonic Sensing** – Uses an **HC-SR04 ultrasonic sensor** to measure distances accurately.  
✅ **Real-time Decision Making** – Arduino processes sensor data and controls the motors accordingly.  
✅ **Expandable & Upgradable** – Can be improved with additional features such as **AI-based navigation**, **Bluetooth/Wi-Fi control**, or **GPS integration**.

## Components Used
- **Arduino Uno** – Microcontroller for processing sensor data and motor control.
- **HC-SR04 Ultrasonic Sensor** – Detects obstacles by measuring distance.
- **Motor Driver Module (L298N)** – Controls the left and right movement of the vehicle.
- **DC Motors & Wheels** – Enable movement.
- **Power Supply** – Battery pack for the vehicle.

## Working Principle
1. The **HC-SR04 ultrasonic sensor** sends out ultrasonic waves.
2. If an obstacle is detected within a certain distance, the **Arduino** decides whether to turn **left or right** based on predefined logic.
3. The **motor driver module** controls the **DC motors** to change direction accordingly.
4. The vehicle continuously scans and adjusts its movement to avoid obstacles.

## Real-World Applications
This project is based on obstacle-avoidance technology, which is widely used in various real-world applications, such as:
- **Robot Vacuums (Roomba, Roborock, etc.)** – Uses similar ultrasonic and infrared sensors to navigate rooms and avoid obstacles.
- **Autonomous Wheelchairs** – Can be adapted to help visually impaired or elderly individuals navigate safely.
- **Self-Navigating Drones & Robots** – Used in warehouses, security patrols, and medical assistance.
- **Smart Shopping Carts** – Assist shoppers by avoiding obstacles in crowded spaces.
- **Autonomous Delivery Robots** – Companies like Amazon and Starship use obstacle-detection technology for last-mile deliveries.

## Future Enhancements
🚀 **AI-Based Navigation** – Use **machine learning** to enhance movement strategies.  
📡 **Remote Control** – Implement **Bluetooth or Wi-Fi** for manual control.  
🗺 **GPS Integration** – Enable **location tracking** for autonomous outdoor movement.  
📷 **Camera Sensor** – Add **computer vision** for better obstacle detection.

## Installation & Usage
1. **Assemble the Hardware:** Connect the **ultrasonic sensor, motor driver, and motors** to the Arduino.
2. **Upload the Code:** Use the Arduino IDE to upload the `.ino` file to your Arduino board.
3. **Power On the Vehicle:** Use a battery pack to power the circuit.
4. **Watch it Navigate!** The vehicle will detect obstacles and steer accordingly.

## Contribution
We welcome contributions! Feel free to fork the repository, add new features, and create pull requests. 🚀

## License
This project is open-source under the **MIT License**.

## Contact
📧 **Email:** mailabhinavgnair@gmail.com  
🔗 **GitHub:** [Absguy](https://github.com/Absguy)  
🔗 **LinkedIn:** [Abhinav G Nair](https://www.linkedin.com/in/abhinav-g-nair-a353892b6/)

