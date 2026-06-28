# Intelligent Library Assistance Bot

An autonomous robotic system that automates book retrieval inside libraries using QR-code navigation, Computer Vision, IoT, and Cloud Integration.

## Overview

Large libraries require significant human effort to locate and retrieve books. This project automates the entire workflow using an intelligent mobile robot capable of:

- Navigating through library aisles
- Identifying requested books
- Retrieving books using a robotic gripper
- Delivering books to the librarian
- Updating cloud records in real time

## Problem Statement

Traditional libraries rely heavily on manual searching and retrieval.

Challenges include:

- Time-consuming book search
- Human errors
- Poor scalability
- High manpower requirement
- Lack of physical automation

## Proposed Solution

The Intelligent Library Assistance Bot combines:

- QR-code navigation
- ESP32 motor control
- Computer Vision
- Cloud synchronization
- Robotic arm automation

to create a fully autonomous library assistant.

## Features

- Autonomous navigation
- QR-code based localization
- Obstacle avoidance
- Book identification
- Servo-controlled robotic gripper
- Google Sheets integration
- Google AppSheet interface
- Real-time cloud synchronization
- Low-cost hardware architecture

## System Workflow

```
User Request
      │
      ▼
Google AppSheet
      │
      ▼
Google Sheets Database
      │
      ▼
    ESP32
      │
      ▼
QR Navigation
      │
      ▼
Target Rack
      │
      ▼
Book Detection
      │
      ▼
Robotic Gripper
      │
      ▼
Book Pickup
      │
      ▼
Return Navigation
      │
      ▼
Book Delivery
```


## Hardware Used

- ESP32
- Camera Module
- L298N Motor Driver
- Servo Motors
- DC Motors
- Ultrasonic Sensors
- IR Sensors
- Li-ion Battery
- LCD Display

## Software Stack

| Category | Technologies |
|-----------|--------------|
| Programming | Python, C++ |
| Computer Vision | OpenCV |
| Cloud | Google Sheets |
| Frontend | Google AppSheet |
| Microcontroller | ESP32 |


## System Architecture

The system handles:

- QR code processing
- Navigation logic
- Image processing
- Cloud communication
- Motor control
- Servo control
- Sensor monitoring
- Obstacle avoidance

## Performance

| Metric | Result |
|---------|--------|
| QR Detection Accuracy | 99% |
| Book Identification Accuracy | 97% |
| Navigation Speed | 0.3 m/s |
| Retrieval Time | 90 seconds |

## Applications

- University Libraries
- Public Libraries
- Digital Archives
- Museums
- Book Warehouses

## Future Enhancements

- Voice Assistant
- Multi-Robot Coordination
- Autonomous Charging Dock
- AI Route Optimization
- Facial Recognition

## Authors

- Tharani R.
- V. Haritha
- S. Harshini
