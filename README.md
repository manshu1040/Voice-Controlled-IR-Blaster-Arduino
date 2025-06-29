# Voice-Controlled-IR-Blaster-Arduino

## Overview
A smart IR blaster system that controls appliances like TVs and ACs using voice commands through Alexa or Google Assistant.

## Tech Stack
- Arduino Uno/ESP32
- IR LED and receiver
- IFTTT for voice command integration
- WiFi module (ESP8266/ESP32)

## Features
- Voice control using Alexa/Google Assistant
- IR signal replication
- Affordable home automation system

## Circuit Diagram
![1000054007](https://github.com/user-attachments/assets/fb70de4b-1060-4449-a395-1b0318f6e4da)
![1000054008](https://github.com/user-attachments/assets/cb4fa45d-4622-4862-aa91-e0831ef82dab)




## How it Works
1. Voice command sent via Alexa
2. IFTTT triggers a webhook
3. ESP32 receives signal and sends corresponding IR code
