# High Tension Transmission Line Inspection Robot

## Overview

The High Tension Transmission Line Inspection Robot is an IoT-enabled robotic platform developed for the inspection and monitoring of high-voltage transmission lines. The system helps detect faults, monitor environmental and electrical parameters, and provide real-time data to operators through wireless communication.

## Features

* Real-time temperature monitoring
* Voltage and current measurement
* GPS-based fault location tracking
* Ultrasonic obstacle detection
* Color-based hotspot detection
* Wireless monitoring using NodeMCU and Wi-Fi
* Blynk app integration
* Arduino-based control system

## Hardware Components

* Arduino UNO
* NodeMCU (ESP8266)
* GPS Module
* Ultrasonic Sensor (HC-SR04)
* Temperature Sensor (LM35)
* Voltage Sensor Module
* Current Sensor Module
* Color Sensor (TCS3200/TCS230)
* L293D Motor Driver
* DC Motors
* Buzzer
* Battery and Power Supply

## Software Requirements

* Arduino IDE
* TinyGPS Library
* ESP8266 Board Package
* Blynk Platform

## System Workflow

1. Robot moves along the transmission line.
2. Sensors continuously collect operational data.
3. Temperature, voltage, and current values are monitored.
4. Ultrasonic sensor detects obstacles.
5. Color sensor identifies hotspot fault regions.
6. GPS module records latitude and longitude.
7. Data is transmitted to the monitoring application.
8. Operators receive real-time updates and fault alerts.

## Project Structure

```text
HTTLIR/
│
├── src/
│   └── HTTLIR.ino
│
├── docs/
│   └── Project_Report.pdf
│
├── images/
│   ├── Block_Diagram.png
│   ├── Circuit_Diagram.png
│   └── Robot_Model.png
│
└── README.md
```

## Applications

* Power transmission line inspection
* Fault detection and monitoring
* Smart grid maintenance
* Preventive infrastructure maintenance
* Remote monitoring systems

## Future Improvements

* Thermal camera integration
* AI-based fault classification
* LiDAR-based navigation
* Cloud data analytics
* Autonomous obstacle avoidance

## Authors

* Patel Chikkalinge Gowda

## License

This project is intended for academic and educational purposes.
