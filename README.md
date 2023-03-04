# rover-arm-pcb

A custom robot arm control PCB for the 2023 SSRT rover.

## Features
* Onboard microcontroller breakout board, like an Arduino Mega or similar
* Controls up to:
    * 7x NEMA23 stepper motors
    * 2x servo motors
    * 7x limit switches
    * A spotlight
    * Other peripherals, like grip strength load cell sensors
* Per-motor current sensing capabilities
* Integrates with off-the-shelf stepper motor drivers (TB6560) and custom circuitry for high reliability and ease of assembly

## Methodology
* PCB is designed in KiCAD v7.0.
* PCB design is used as a teaching tool, so simplicity and likelihood of success was prioritized

## Dependencies
https://github.com/Alarm-Siren/arduino-kicad-library

## Opportunities for Impovement
* Use an encoder/decoder for the EN pins, instead of using so many pins on the microcontroller.
