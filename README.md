# Security Robot

A mobile embedded security robot designed to monitor its surroundings using multiple sensors while supporting both autonomous and manual operation. The robot utilizes ultrasonic sensing for obstacle detection, a PIR sensor for motion detection, and an IR remote interface for user control.

---

## Overview

This project was developed as the final integrated project for an Embedded Systems course. The system combines multiple sensors, motor control, and user interaction into a mobile robotic platform capable of environmental monitoring and navigation.

The robot integrates motion sensing, obstacle detection, and remote-control functionality while demonstrating embedded programming, sensor integration, and hardware system design.

### Demo

🎥 [Demo Video](https://youtube.com/shorts/vbmVGlrL-Wg?is=kajh2vK03fF_jFiv)
   -***note*** In the video the robot is performing its searching algorithm by going in a circle and finding the farthest point. But once an obstacle comes close the ultrasonic sensor sends and interrupt to make it go a different way.
---

## My Contributions

I was responsible for the integration of the robot's hardware and software subsystems, including sensor implementation, motor control, wiring design, and system testing.

Key contributions included:

- Integrated multiple sensors into a single embedded platform.
- Developed software for sensor monitoring and robot control.
- Implemented stepper motor control and navigation logic.
- Created wiring diagrams and pinout documentation.
- Planned hardware layout and interconnections prior to assembly.
- Performed subsystem integration testing and troubleshooting.
- Validated communication between sensors, motors, and the microcontroller.

---

## Features

- Ultrasonic obstacle detection
- PIR motion sensing
- IR remote control interface
- Stepper motor-driven locomotion
- Autonomous obstacle response
- Multi-sensor data processing
- Embedded microcontroller-based control system

---

## Hardware Components

- Microcontroller Development Board
- Ultrasonic Distance Sensor
- PIR Motion Sensor
- IR Receiver Module
- IR Remote Controller
- Stepper Motors
- Motor Driver Circuitry
- Mobile Robot Chassis
- Battery Power System

---

## How It Works

1. The ultrasonic sensor continuously scans for nearby obstacles.
2. The PIR sensor monitors for motion within the environment.
3. The microcontroller processes sensor information in real time.
4. Stepper motors control robot movement and navigation.
5. Users can issue commands through an infrared remote control.
6. The robot reacts to environmental inputs while executing movement commands.

---

## Skills Demonstrated

- Embedded Systems Programming
- C Programming
- Sensor Integration
- Motor Control
- Hardware Debugging
- Wiring Design
- System Integration
- Microcontroller Development
- Technical Documentation
- Troubleshooting and Testing

---

## Challenges

- Integrating multiple sensor inputs into a single control system.
- Managing hardware pin assignments and resource allocation.
- Debugging communication between sensors and actuators.
- Coordinating real-time sensor monitoring and motor control.
- Validating system functionality through testing and iterative refinement.

---

## Engineering Lessons Learned

- Gained experience integrating multiple sensing technologies into a single embedded system.
- Learned how to organize hardware resources and pin assignments for complex projects.
- Improved troubleshooting techniques when debugging sensor and motor interactions.
- Developed a stronger understanding of real-time embedded system behavior.
- Learned the importance of planning hardware layouts before assembly.

---

## Documentation

Additional project documentation can be found in the `images/` directory.

Included documentation contains:
- Wiring diagrams
- Pinout references
- Hardware integration notes
- Hand-drawn system planning sketches
- Sensor connection mappings
- Development notes and implementation references

## Source Code

The project was developed incrementally throughout an Embedded Systems course. Source files retain their original project structure and naming conventions to preserve compatibility with the original development environment.

## Repository Structure

```text
security-robot/
├── README.md
├── LICENSE
├── src/
│   └── Security_Robot/
├── docs/
├── images/
└── videos/
```

## Future Improvements

- Wireless control functionality
- Additional environmental sensors
- Autonomous patrol capability
- Improved obstacle avoidance algorithms
- Camera integration for monitoring

---

## Authors

Eric Nguyen

Developed as part of an Embedded Systems course project.
