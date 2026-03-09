# Anti-Fall Airbag Vest

Wearable safety device that detects falls using embedded algorithms and deploys an airbag in real time to reduce impact injuries.

Developed as a Capstone Engineering Project for **Sapphire Sky Solutions** with Dr. Jimmy Wang.
![Capstone Resume Slide Edit_page-0002](https://github.com/user-attachments/assets/5d79c148-6998-4a67-94ec-ffd2c87d3e76)

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

## Demo Video

[![Watch the Demo](https://github.com/user-attachments/assets/85b5abdd-9ca9-44bb-a522-e3d4c0775a9c)](https://drive.google.com/file/d/176ka4YX3g7VdFCOAG7YfthU7qUPhSOTZ/view)

---

# Project Overview

![Capstone Resume Slide Edit_page-0003](https://github.com/user-attachments/assets/34956b57-b89b-4959-a20b-4c72510f3c10)
![Capstone Resume Slide Edit_page-0004](https://github.com/user-attachments/assets/e2e78218-c1c9-4a2b-806e-eba3e457c475)
![Capstone Resume Slide Edit_page-0005](https://github.com/user-attachments/assets/e7a7d5c8-1c3c-4504-b2b5-22ac5f3a9157)



The project focuses on the **embedded electronics module and fall-detection algorithm**, while the mechanical airbag vest and proprietary CO₂ puncture mechanism are external components.

---

# Hardware Architecture
![Capstone Resume Slide Edit_page-0008](https://github.com/user-attachments/assets/d188b3fe-5584-4d8d-9188-e3516cb753ba)


The electronics module integrates:

- **MCU Control System**
- **Battery & Power Management**
- **CO₂ Valve Driver**
- **Wearable-focused packaging**

---

# MCU Control System
![Capstone Resume Slide Edit_page-0009](https://github.com/user-attachments/assets/ec1b484a-459f-40a9-814d-eb5af80b533e)

The system uses an **Arduino Nano 33 BLE Sense Rev2**, enabling:

- Onboard IMU-based fall detection
- Real-time processing at 64 MHz
- Direct control of valve driver and warning indicators
- Bluetooth connectivity for mobile alerts

---

# Power System
![Capstone Resume Slide Edit_page-0010](https://github.com/user-attachments/assets/1783af3a-6716-4791-9c9e-77723c9164b5)


Power is provided by a **3.7V 18650 Li-ion battery** with:

- ~50 hours runtime
- removable battery design
- 5V regulated supply for stable MCU operation

---

# CO₂ Valve Control
![Capstone Resume Slide Edit_page-0011](https://github.com/user-attachments/assets/78527aa8-bc57-4fd1-b9d9-9f00bb4b771a)

A configurable electronic valve driver enables testing with commercially available CO₂ solenoid valves.

Key design considerations:

- 24V / 0.4A valve actuation capability
- Reduced mechanical complexity
- Future integration with proprietary puncture mechanisms

---

# Wearable Integration
![Capstone Resume Slide Edit_page-0012](https://github.com/user-attachments/assets/92cae2d4-480b-40e2-8928-051edf9d2650)

The electronics module was designed for wearable use:

- **Dimensions:** 8.4 × 7.2 × 3.1 cm  
- **Weight:** 123 g  
- Integrated **pre-deployment warning buzzer**

---

# Prototype
![IMG_6552](https://github.com/user-attachments/assets/c9a12527-6a84-472d-b93b-80ea68808058)
![IMG_6576](https://github.com/user-attachments/assets/1edf0890-cf8a-4aa2-bd3f-aa4fe3d35c90)
![IMG_6580](https://github.com/user-attachments/assets/4f7eae57-ea4a-496e-bb0e-b58be0302082)
![IMG_6651](https://github.com/user-attachments/assets/220ed411-cff1-403e-b47d-73f7758fcc11)
![IMG_6583](https://github.com/user-attachments/assets/21611365-b7a6-4a5a-b4c1-626eb6e1a61d)
![IMG_6652](https://github.com/user-attachments/assets/29d47378-88a2-4c0e-b5db-352ead94196e)
*(More prototype photos coming soon)*

---

# Future Improvements

- PCB V3 hardware optimization
- Custom CO₂ actuation system
- Improved fall detection dataset
- Mobile application integration

---

# Repository Structure
