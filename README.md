# Traffic Light Project with Ultrasonic Sensor

This project simulates a traffic light system that changes the light sequence based on the distance measured by an ultrasonic sensor. When an object is detected within a certain range, the traffic light will change to red, indicating that vehicles should stop.

## Table of Contents

- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Wiring Diagram](#wiring-diagram)
- [Code](#code)
- [Usage](#usage)
- [License](#license)

## Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- Ultrasonic distance sensor (e.g., HC-SR04)
- LEDs (Red, Yellow, Green)
- Resistors (220 ohm)
- Breadboard and jumper wires

## Software Requirements

- Arduino IDE

## Wiring Diagram

Connect the components as follows:

- **Ultrasonic Sensor**:
  - VCC to 5V
  - GND to GND
  - TRIG to pin 9
  - ECHO to pin 8

- **LEDs**:
  - Red LED:
    - Anode (longer leg) to pin 12
    - Cathode (shorter leg) to GND (with a 220 ohm resistor)
  - Yellow LED:
    - Anode (longer leg) to pin 3
    - Cathode (shorter leg) to GND (with a 220 ohm resistor)
  - Green LED:
    - Anode (longer leg) to pin 13
    - Cathode (shorter leg) to GND (with a 220 ohm resistor)

![Wiring Diagram](path/to/your/image.png)

