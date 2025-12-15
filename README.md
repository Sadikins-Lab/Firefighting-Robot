# Microcontroller-Based Autonomous Firefighting Robot

## Overview
This project presents the design and implementation of a **microcontroller-based autonomous firefighting robot** capable of detecting and extinguishing small-scale fires without human intervention. The robot uses flame and obstacle detection sensors to autonomously navigate toward a fire source and activate a fire suppression mechanism.

The project is intended for **educational, research, and prototyping purposes**, particularly in the areas of embedded systems, robotics, and autonomous control.

---

## Key Features
- Autonomous navigation and decision-making
- Flame detection and localization
- Obstacle avoidance
- Automatic fire extinguishing mechanism
- Compact and modular design
- Low-cost and easily reproducible hardware

---

## System Architecture
The robot operates by continuously scanning its surroundings using flame and obstacle sensors. Upon detecting a flame, it calculates the direction of the fire, navigates toward it, and activates the extinguishing unit when a safe distance is reached.

### Block Diagram
*(Insert system block diagram here)*

---

## Hardware Components
- Microcontroller (e.g., Arduino / STM32 / ESP32)
- Flame sensors
- Ultrasonic or IR obstacle sensors
- Motor driver module (e.g., L298N / TB6612FNG)
- DC gear motors with wheels
- Fire extinguishing unit (water pump / fan / CO₂ module)
- Power supply (Li-ion battery / battery pack)
- Chassis and mechanical frame

---

## Software and Tools
- Embedded C / Arduino framework
- Microcontroller IDE (Arduino IDE / PlatformIO / STM32CubeIDE)
- Serial monitor for debugging
- Optional simulation tools

---

## Working Principle
1. The robot continuously monitors the environment using flame sensors.
2. When a flame is detected, the robot determines its direction.
3. Obstacle sensors ensure safe navigation toward the fire.
4. Once the robot reaches an optimal distance, the extinguishing mechanism is activated.
5. After fire suppression, the robot resumes scanning mode.

---

## Build Process

### Mechanical Assembly
*(Insert images of chassis and mechanical assembly here)*

### Electronics and Wiring
*(Insert images of circuit connections and wiring here)*

### Final Prototype
*(Insert images of the completed robot here)*

---

## Circuit Diagram
*(Insert circuit schematic here)*

---

## Code Structure
```text
├── src/
│   ├── main.c / main.ino
│   ├── motor_control.c
│   ├── sensor_reading.c
│   └── fire_control.c
├── docs/
│   └── diagrams
└── README.md
