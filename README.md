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

## Wiring Connections

| L293D Pin | Connected To |

|-----------|--------------|

| 1 (Enable 1,2) | 5V |

| 2 (IN1) | Digital Pin 2 |

| 3 (OUT1) | Motor 1 & Motor 2 (Terminal 1) |

| 4 (GND) | GND |

| 5 (GND) | GND |

| 6 (OUT2) | Motor 1 & Motor 2 (Terminal 2) |

| 7 (IN2) | Digital Pin 3 |

| 8 (VCC2) | 5V |

| 9 (Enable 3,4) | 5V |

| 10 (IN3) | Digital Pin 4 |

| 11 (OUT3) | Motor 3 & Motor 4 (Terminal 1) |

| 12 (GND) | GND |

| 13 (GND) | GND |

| 14 (OUT4) | Motor 3 & Motor 4 (Terminal 2) |

| 15 (IN4) | Digital Pin 5 |

| 16 (VCC1) | 5V |

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
