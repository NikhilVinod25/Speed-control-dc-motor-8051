# Speed Control of DC Motor using 8051

## Overview
This project demonstrates speed control of a DC motor using an AT89C51 (8051) microcontroller.
Different motor speeds are obtained by selecting different resistor inputs.
The complete system is simulated using Proteus Design Suite.

## Hardware Components
- AT89C51 (8051 Microcontroller)
- L293D Motor Driver IC
- DC Motor
- Push Button Switches
- Resistors
- Power Supply

## Software Tools
- Keil µVision
- Proteus Design Suite

## Firmware
The Proteus simulation uses a compiled **HEX file** loaded directly into the AT89C51 microcontroller.

- The HEX file contains the final firmware used for simulation.
- Motor speed control is achieved using software-based switching logic.
- Source code is not included in this repository.

## Working Principle
The microcontroller reads different resistor-based inputs through switches.
Each input corresponds to a predefined motor speed.
By varying the ON and OFF duration of the motor drive signal,
the average voltage applied to the DC motor is controlled.

## Simulation Results
Proteus simulation screenshots for all six speed levels
(including motor OFF and maximum speed) are available
in the `images/` folder of this repository.

## Applications
- DC motor speed control
- Embedded systems laboratory experiments
- Educational and academic projects

## Notes
This repository focuses on simulation and firmware deployment using a HEX file in Proteus.
