# Peltier-Based Beverage Cooler (ATmega32)

This project implements a microcontroller-based beverage cooling system using a thermoelectric Peltier module. An ATmega32 monitors temperature via an LM35 sensor, controls cooling through a relay, and displays real-time temperature on a 16×2 LCD.

## Overview
1. Monitors beverage temperature using LM35 sensor.
2. Controls cooling via Peltier module and relay.
3. Displays real-time temperature on 16×2 LCD.
4. Implemented using AVR assembly language.

## Features
1. ATmega32-based control logic
2. LM35 temperature sensing with ADC
3. Relay-based power switching for Peltier module and fan
4. Real-time temperature display on 16×2 LCD
5. Embedded system implemented in AVR assembly

## Applications
1. Small-scale beverage cooling
2. Embedded system learning and demonstration
3. Microcontroller-based automation projects

## Files Included
1. 'firmware' – AVR assembly source code
2. 'simulation' – Proteus simulation files and screenshots
3. 'hardware' – Hardware setup images
4. 'docs' – Project report

## Instructions
1. Open the Proteus simulation files in the 'simulation' folder.
2. Compile and upload the AVR assembly code to the ATmega32.
3. Connect the LM35, relay, Peltier module, and LCD as shown in the hardware setup.
4. Power on the system and observe temperature regulation on the LCD.

## Acknowledgements
1. Developed by Muhammad Ibrahim and Mohammad Ahtesam.
2. Special thanks to resources and tutorials used for AVR assembly and embedded systems.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
