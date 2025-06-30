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
![Circuit Diagram](https://github.com/user-attachments/assets/340d4af6-4ff6-4dcf-af5c-6e800f717e6b)




## How it Works
1. Voice command sent via Alexa
2. IFTTT triggers a webhook
3. ESP32 receives signal and sends corresponding IR code
