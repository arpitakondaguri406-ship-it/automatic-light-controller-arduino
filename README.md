# Automatic Light Controller using Arduino

## Project Overview
This project automatically turns ON an LED when the surrounding light intensity becomes low using an LDR sensor.

## Components
- Arduino Uno
- LDR Sensor Module
- LED
- 220Ω Resistor

## Working Principle
The Arduino continuously reads the analog value from the LDR.
If the light intensity falls below a threshold, the LED turns ON.
Otherwise, it remains OFF.

## Pin Connections
LDR AO → A0
LDR VCC → 5V
LDR GND → GND
LED → D7

## Software
Arduino IDE / Wokwi Simulator

## Future Improvements
- Automatic street light
- Smart home lighting
- Energy-saving lighting system
