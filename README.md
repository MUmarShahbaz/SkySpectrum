# SkySpectrum

## Overview
SkySpectrum is a versatile wireless communication system featuring a custom RF transmitter and a universal receiver. It supports multiple communication protocols, including RF, WiFi, Bluetooth, and ESP-NOW, making it adaptable for a variety of applications such as RC vehicles, drones, home automation, and general RF control.

## Features
### Transmitter
- **Microcontroller:** Arduino Nano
- **Communication Module:** nRF24L01
- **Input Components:**
  - 4 Buttons
  - 2 Joysticks
  - 4 Potentiometers
  - 2 Toggle Switches
  - 1 MPU6050

### Receiver
- **Microcontroller:** ESP32 Devkit V1
- **Communication Modules:**
  - nRF24L01 (Primary RF Communication)
  - Bluetooth (For mobile control)
  - WiFi (For long-range connectivity)
- **Reconfigurable as a Pseudo-Transmitter:** Can also be used as a Transmitter.

## Communication Range
| Mode                                               | Range (Ideal Conditions) |
|:---------------------------------------------------|:------------------------:|
| Transmitter to Receiver (One-way)                  | 1 km                     |
| Transmitter to Receiver (Two-way)                  | 100 m                    |
| Transmitter to Transmitter                         | 1 km (No Purpose)        |
| Pseudo-Transmitter to Receiver (One-way & Two-way) | 100 m                    |

## Development
- **IDE:** Arduino IDE
- **Libraries Used:**
  - RF24 (for nRF24L01 communication)
  - Custom MPU6050 library (if possible)

## Usage
- **Default Communication Mode:** RF
- **Receiver is Fully Configurable:** Code can be modified based on use case.
- **Example Applications:**
  - RC Airplanes/Drones
  - Wifi Home Automation Control Units
  - Bluetooth Cars/Boats
  - General RF-Based Wireless Control

## Repository Contents

| Folder                      | Purpose                                          |
|:----------------------------|:-------------------------------------------------|
| **PCBs**                    | PCB schematics and gerber files                  |
| **PCBs/RC Receiver**        | Discontinued, replaced by **Universal Receiver** |
| **PCBs/Universal Receiver** | The Receiver                                     |
| **PCBs/RC Transmitter**     | The Transmitter                                  |
| **README.md**               | Project overview and description                 |
