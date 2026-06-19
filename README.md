# ESP32 Weather Station

## Overview

A virtual IoT weather station built using ESP32 and DHT22 in the Wokwi simulator.

The system measures temperature and humidity and displays the sensor readings in real time.

## Features

- Temperature monitoring
- Humidity monitoring
- ESP32 microcontroller
- DHT22 sensor integration
- WiFi connectivity
- Real-time sensor readings

## Hardware Used

- ESP32 DevKit V1
- DHT22 Temperature and Humidity Sensor

## Software Used

- Arduino IDE
- Wokwi Simulator
- GitHub

## Project Structure

ESP32-Weather-Station

├── README.md

└── weather_station.ino

## How It Works

1. ESP32 initializes the DHT22 sensor.
2. ESP32 connects to WiFi.
3. Sensor data is collected every 2 seconds.
4. Temperature and humidity values are displayed through the Serial Monitor.

## Future Improvements

- Web Dashboard
- MQTT Integration
- Cloud Data Logging
- Mobile Notifications
- ThingSpeak Integration

## Simulation

Run the project online using Wokwi:

PASTE_YOUR_WOKWI_LINK_HERE

## Author

Godson Daniel
ECE Student | Embedded Systems | ESP32 | IoT
