# Self-Powered-Underwater-Data-Logger
This project is a wearable triage wristband built around a PIC16F18324 microcontroller that monitors heart rate, blood oxygen (SpO2), and body temperature, then streams the readings wirelessly through a BLE module.

## Features
- Multi-Sensor Biometric Monitoring: Tracks heart rate and SpO2 via a MAX30102 pulse-oximetry sensor, and body temperature via an NTC thermistor
- Wireless Reporting: Streams live readings over Bluetooth Low Energy through an RN4871 module for remote triage monitoring
- Rechargeable Power System: Single-battery design with LiPo charging, dual-rail (1.8V/3.3V) LDO regulation, and USB-C surge protection
- Low-Power Operation: Interrupt-driven sleep/wake cycle triggered directly by the sensor's data-ready signal to conserve battery life


## Schematic
<p align="center">
  <img width="900" alt="image" src="https://github.com/user-attachments/assets/82e39621-6ebe-47c7-bc6c-baaf98d64965" />
</p>

## PCB Preview
<p align="center">
<img width="475" alt="_Medtech_ONB — PCB Editor 2026-09-21 9_18_44 PM" src="https://github.com/user-attachments/assets/c005ac64-aba9-462f-85b6-5881fc76887d" />
</p>


## 3D Board Render




## Firmware Architecture

