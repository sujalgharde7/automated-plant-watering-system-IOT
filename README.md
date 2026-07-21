# 🌱 Automated Plant Watering System using IoT

## Overview

The Automated Plant Watering System is an IoT-based project designed to automate irrigation by monitoring soil moisture levels. The system uses an ESP32 microcontroller to continuously read the soil moisture sensor. When the soil becomes dry, the ESP32 activates a relay module that turns on a water pump. Once adequate moisture is restored, the pump automatically switches off.

This project helps conserve water while reducing human effort in maintaining plants.

---

## Features

- Automatic watering based on soil moisture
- ESP32-based IoT implementation
- Water conservation
- Low power consumption
- Easy to expand for multiple plants
- Suitable for home gardens and smart agriculture

---

## Components Used

| Component | Quantity |
|----------|----------|
| ESP32 Development Board | 1 |
| Soil Moisture Sensor | 1 |
| Relay Module (5V) | 1 |
| Mini DC Water Pump | 1 |
| Jumper Wires | Several |
| Breadboard | 1 |
| Power Supply | 5V |

---

## Software Used

- Arduino IDE
- ESP32 Board Package
- Embedded C++

---

## Working Principle

1. Soil moisture sensor measures soil moisture.
2. ESP32 reads sensor values.
3. If moisture falls below a threshold:
   - Relay turns ON.
   - Water pump starts.
4. When moisture reaches the desired level:
   - Relay turns OFF.
   - Pump stops.

---

## Applications

- Home Gardening
- Smart Agriculture
- Greenhouse Automation
- Indoor Plants
- Water Conservation

---

## Future Improvements

- Mobile App Monitoring
- Blynk Integration
- ThingSpeak Cloud
- Weather Forecast API
- Solar Powered Operation

---

## Author

**Sujal Gharde**

B.Tech Electronics & Telecommunication Engineering

St. Vincent Pallotti College of Engineering and Technology

Nagpur, Maharashtra
