# STM32-Based Smart Kitchen Safety Monitoring System

An STM32-based embedded systems project for kitchen safety monitoring, integrating sensor data acquisition, local display, alarm logic, actuator output, and basic Wi-Fi communication.

## Project Overview
This project was developed as an undergraduate capstone design project.

The system monitors temperature, gas concentration, and flame status using multiple sensors. Based on predefined thresholds and detection results, the STM32 controller updates the OLED display, triggers alarm outputs, and drives external control modules such as relay, fan, and servo.

This project demonstrates embedded firmware development, sensor interfacing, hardware-software integration, and functional testing on a custom STM32-based platform.

## Key Features
- Temperature monitoring using DS18B20
- Gas detection using MQ-series sensor
- Flame detection
- OLED-based local status display
- Buzzer and LED alarm output
- Relay, fan, and servo control logic
- Wi-Fi communication using ESP8266 for basic wireless data transmission

## Hardware Components
- STM32F103C8T6 microcontroller
- DS18B20 temperature sensor
- MQ gas sensor
- Flame sensor
- OLED display
- ESP8266 Wi-Fi module
- Relay module
- Servo motor
- Fan
- Buzzer and LED indicators

## Repository Structure
- `code/` - STM32 firmware source code and Keil project files
- `docs/` - system block diagram and selected software flowcharts
- `hardware/` - schematic and PCB layout
- `media/` - simulation, prototype, and functional test images

## Representative Materials
### System Design
- System block diagram: `docs/system_block_diagram.png`
- Main control flowchart: `docs/main_program_flowchart.png`

### Hardware
- Schematic: `hardware/schematic.PNG`
- PCB layout: `hardware/pcb_layout.PNG`

### Demonstration
- Prototype overview: `media/prototype.jpg`
- Temperature and gas test: `media/temperature_gas_test.png`
- Flame detection test: `media/flame_detection_test.png`
- Wi-Fi synchronization demo: `media/wifi_sync_demo.png`
- Proteus simulation: `media/proteus_simulation.png`

## My Contributions
- Developed STM32 firmware for sensor reading, threshold judgment, and output control
- Integrated temperature, gas, flame, OLED, relay, servo, buzzer/LED, and ESP8266 modules
- Participated in hardware implementation and functional testing
- Organized the project materials into a GitHub portfolio repository

## Notes
- The mobile app shown in the demonstration images was used for communication testing and data visualization.
- The mobile app itself was not developed as the core part of this project repository.
- This repository mainly focuses on embedded system design, firmware logic, hardware integration, and testing results.

## Tools and Environment
- Keil uVision
- STM32 standard peripheral libraries
- Proteus
- Custom PCB implementation

## Author
Junyi (Betty) Jin
