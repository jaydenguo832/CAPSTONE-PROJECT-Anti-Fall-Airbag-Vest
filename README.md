# Anti-Fall Airbag Vest

Wearable safety device that detects falls using embedded algorithms and deploys an airbag in real time to reduce impact injuries.

Developed as a Capstone Engineering Project in collaboration with **Sapphire Sky Solutions**.

---

## Project Overview

This system detects fall events using onboard IMU data and triggers a CO₂ valve to deploy an airbag before ground impact.

Key features:

- Real-time fall detection using embedded algorithms
- Wireless notification via Bluetooth
- Pre-deployment warning system
- Compact wearable electronics module
- Configurable CO₂ valve actuation interface

---

## Demo

[Video Demo](link-to-video)

![Demo](images/demo.png)

---

# System Overview

![System Overview](slides/slide_04.png)

The project focuses on the **embedded electronics module and fall-detection algorithm**, while the mechanical airbag vest and proprietary CO₂ puncture mechanism are external components.

---

# Hardware Architecture

![Hardware Architecture](slides/slide_08.png)

The electronics module integrates:

- **MCU Control System**
- **Battery & Power Management**
- **CO₂ Valve Driver**
- **Wearable-focused packaging**

---

# MCU Control System

![MCU](slides/slide_09.png)

The system uses an **Arduino Nano 33 BLE Sense Rev2**, enabling:

- Onboard IMU-based fall detection
- Real-time processing at 64 MHz
- Direct control of valve driver and warning indicators
- Bluetooth connectivity for mobile alerts

---

# Power System

![Battery](slides/slide_10.png)

Power is provided by a **3.7V 18650 Li-ion battery** with:

- ~50 hours runtime
- removable battery design
- 5V regulated supply for stable MCU operation

---

# CO₂ Valve Control

![Valve Control](slides/slide_11.png)

A configurable electronic valve driver enables testing with commercially available CO₂ solenoid valves.

Key design considerations:

- 24V / 0.4A valve actuation capability
- Reduced mechanical complexity
- Future integration with proprietary puncture mechanisms

---

# Wearable Integration

![Wearable Integration](slides/slide_12.png)

The electronics module was designed for wearable use:

- **Dimensions:** 8.4 × 7.2 × 3.1 cm  
- **Weight:** 123 g  
- Integrated **pre-deployment warning buzzer**

---

# Prototype

*(More prototype photos coming soon)*

| Electronics Module | Worn Prototype |
|---|---|
| ![](images/prototype_pcb.png) | ![](images/prototype_wearable.png) |

---

# Future Improvements

- PCB V3 hardware optimization
- Custom CO₂ actuation system
- Improved fall detection dataset
- Mobile application integration

---

# Repository Structure
