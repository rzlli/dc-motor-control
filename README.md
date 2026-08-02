# Arduino DC Motor Control using L293D

## Overview
This project demonstrates how to control four DC motors using an Arduino Uno and an L293D motor driver. The circuit was designed and simulated in Tinkercad to demonstrate basic motor direction control.

## Features
- Controls four DC motors.
- Forward movement for 30 seconds.
- Backward movement for 60 seconds.
- Alternating right and left turns.

## Components
- Arduino Uno
- L293D Motor Driver
- 4 DC Motors
- Jumper Wires

---

## Wiring Connections

- L293D Pin 1 (Enable 1,2) → 5V

- L293D Pin 2 (IN1) → Arduino Digital Pin 2

- L293D Pin 3 (OUT1) → Motor 1 & Motor 2 (Terminal 1)

- L293D Pin 4 → GND

- L293D Pin 5 → GND

- L293D Pin 6 (OUT2) → Motor 1 & Motor 2 (Terminal 2)

- L293D Pin 7 (IN2) → Arduino Digital Pin 3

- L293D Pin 8 (VCC2) → 5V

- L293D Pin 9 (Enable 3,4) → 5V

- L293D Pin 10 (IN3) → Arduino Digital Pin 4

- L293D Pin 11 (OUT3) → Motor 3 & Motor 4 (Terminal 1)

- L293D Pin 12 → GND

- L293D Pin 13 → GND

- L293D Pin 14 (OUT4) → Motor 3 & Motor 4 (Terminal 2)

- L293D Pin 15 (IN4) → Arduino Digital Pin 5

- L293D Pin 16 (VCC1) → 5V

---

## Software
- Tinkercad

## Project Workflow
The Arduino sends control signals to the L293D motor driver, which drives the connected DC motors according to a predefined sequence:
1. Move forward.
2. Move backward.
3. Turn right.
4. Turn left.

This project demonstrates the basic principles of controlling DC motors and changing their rotation direction using an H-Bridge motor driver.

## Repository Contents
- Arduino code (.ino)
- Circuit screenshot
