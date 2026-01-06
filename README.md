# Peltier-Based Beverage Cooler (ATmega32)

This project implements a microcontroller-based beverage cooling system using a thermoelectric Peltier module. An ATmega32 monitors temperature via an LM35 sensor, controls cooling through a relay, and displays real-time temperature on a 16×2 LCD.

## Features
1) ATmega32-based control logic
2) LM35 temperature sensing using ADC
3) Relay-based power switching for Peltier module and fan
4) Real-time temperature display on 16×2 LCD
5) Implemented in AVR assembly language

## System Overview
1) The LM35 sensor provides analog temperature data to the ATmega32 ADC
2) The microcontroller compares temperature against a threshold
3) A relay is switched ON/OFF to control the Peltier module and cooling fan
4) Current temperature is displayed on the LCD

## Tools & Technologies
1) ATmega32
2) AVR Assembly
3) Proteus (simulation)
4) LM35 temperature sensor
5) Peltier TEC1-12706
6) Relay module
7) 16×2 LCD

## Repository Structure
1) 'firmware/' – AVR assembly source code  
2) 'simulation/' – Proteus simulation files and screenshots  
3) 'hardware/' – Hardware setup images  
4) 'docs/' – Project report

## Notes
This project demonstrates embedded system design, low-level microcontroller programming, and practical hardware–software integration.
