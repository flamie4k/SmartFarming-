# Smart Farming System

A smart farming system built on an **ESP32 microcontroller** to monitor environmental conditions critical for plant growth. This project integrates **light**, **humidity**, **water level**, and **soil moisture** sensors to help automate and optimize plant care.

## Features

- **Real-time environmental monitoring**
  - Ambient light intensity
  - Air humidity and temperature (via DHT or similar sensor)
  - Soil moisture levels
  - Water reservoir level
- **Wi-Fi connectivity using ESP32**
  - Remote monitoring through web dashboard or MQTT
- **Data logging**
  - Local storage or cloud integration options
- **Automation-ready**
  - Can trigger pumps, fans, or lights based on sensor thresholds

## Hardware Components

- **ESP32 Development Board**
- **Light Sensor** (e.g., LDR, BH1750)
- **Humidity/Temperature Sensor** (e.g., DHT11, DHT22, SHT31)
- **Soil Moisture Sensor** (capacitive recommended for durability)
- **Water Level Sensor** (float switch or analog sensor)
- Optional components:
  - Relay module
  - Water pump
  - Grow lights

## System Architecture

1. Sensors collect environmental data in real time.
2. ESP32 reads sensor inputs and processes thresholds.
3. Data is published to a dashboard, serial monitor, or cloud service.
4. Automated triggers can activate actuators (pump, fan, lighting).
5. Logged data provides insights for optimizing plant conditions.

## Installation

1. Install **Arduino IDE** or **PlatformIO**.
2. Add the **ESP32 board package**.
3. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/smart-farming.git
