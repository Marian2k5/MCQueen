# MCQueen
# WRO Future Engineers - Smart Car Project

## Project Overview
An autonomous smart car designed to navigate a track using an ultrasonic sensor for obstacle detection, an L298N motor driver, and a servo motor for steering control.

---

##  Bill of Materials (Components List)

| Component | Function / Description | Quantity |
| :--- | :--- | :--- |
| **Microcontroller** | Arduino Uno | 1 |
| **Motor Driver** | L298N Dual H-Bridge Module | 1 |
| **Distance Sensor** | HC-SR04 Ultrasonic Sensor | 1 |
| **Steering Actuator** | Servo Motor | 1 |
| **Driving Motors** | DC Gear Motors | 2 |
| **Power Source** | Battery Pack | 1 |
| **Chassis** | Smart Car Chassis Frame | 1 |
| **Wiring** | Jumper Wires (M-to-M, M-to-F) | Assorted |

---

##  Power & Hardware Setup
* **Logic Power:** Arduino powered via USB during testing.
* **Motor Power:** Main battery pack connected directly to the L298N 12V terminal.
* **Shared Ground:** Common ground established between Arduino GND and L298N GND.
  
##  Hardware & Design Justifications
* **Arduino Uno:** Chosen for its reliability, broad community library support, and ease of interfacing with external sensors and motor drivers.
* **L298N Motor Driver:** Used to handle the higher current requirements of the DC motors while keeping motor voltage separate from the Arduino's logic supply.
* **HC-SR04 Ultrasonic Sensor:** Provides accurate distance measurement to track walls and obstacles dynamically.
