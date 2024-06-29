# IoT Analog/Digital Clock using ESP32

This project showcases an IoT-based analog and digital clock using an ESP32 microcontroller and an OLED display. The clock synchronizes time over the internet using NTP (Network Time Protocol).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Components](#components)
- [Circuit Diagram](#circuit-diagram)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

This project demonstrates how to build a simple IoT clock using the ESP32 microcontroller. It can display time in both analog and digital formats on an OLED display. The time is synchronized using NTP servers, ensuring accurate timekeeping.

## Features

- **Accurate Timekeeping**: Synchronizes time over the internet using NTP.
- **Dual Display**: Can switch between analog and digital clock displays.
- **OLED Display**: Uses an SSD1306 OLED display for clear and crisp output.

## Components

- ESP32 Development Board
- SSD1306 OLED Display
- Connecting Wires
- Breadboard (optional)

## Circuit Diagram

![Wiring_Scheme](https://github.com/toximate/IoT-Digital-Analog-Clock-ESP32/assets/133029523/6417f189-992d-420f-b845-8830a57c2c63)

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/toximate/IoT-Digital-Analog-Clock-ESP32.git
   cd IoT-Digital-Analog-Clock-ESP32

2. **Install the required libraries**:
  - Adafruit GFX Library
  - Adafruit SSD1306 Library
You can install these libraries via the Arduino Library Manager.

3. **Upload the code to your ESP32**:
  - Open the Arduino IDE.
  - Open the relevant .ino file.
  - Connect your ESP32 to your computer.
  - Select the correct board and port.
  - Upload the code.

## Usage

- Power on your ESP32.
- The ESP32 will connect to the specified WiFi network.
- The current time will be displayed on the OLED screen in the selected format.
- (Add instructions for switching between analog and digital clock displays if applicable)

