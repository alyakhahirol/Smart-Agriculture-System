# Smart-Agriculture-System
Smart Agriculture System that monitors critical parameters for plant growth and automated irrigation according to schedule.

## Overview

Smart agriculture plays an essential role in ensuring healthy plant growth and increasing farming productivity. This project focuses on developing a Smart Agriculture System that monitors and controls plant conditions automatically with minimal manual intervention. The main objective is to help small-scale farmers by automating the watering process and displaying real-time environmental data such as temperature, humidity, sunlight intensity, and soil moisture.

This system uses the **NodeMCU ESP32** microcontroller because of its built-in WiFi capabilities and low power consumption. It utilizes:
- Capacitive soil moisture sensor
- DHT22 for temperature and humidity
- LDR to detect sunlight
- Water level sensor to monitor irrigation tank status
- OLED display (SSD1306) for local monitoring
- Buzzer and LED for alerts
- A 5V water pump controlled by a relay for irrigation
- DS3231 RTC module for accurate timekeeping

The system also connects to the Blynk IoT mobile application to allow remote monitoring and basic control. A fertilizer suggestion feature recommends suitable fertilizer types based on the selected plant. This setup targets leafy vegetables such as choy sum and spinach and is designed for semi-outdoor or protected indoor environments (balconies, rooftop gardens) using natural sunlight.
