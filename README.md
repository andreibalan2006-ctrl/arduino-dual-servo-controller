# Dual Servo Motor Controller using Arduino

This repository contains the hardware schematic and code for controlling two independent servo motors using an Arduino Uno and two potentiometers[cite: 9]. 

## 📝 Project Overview
This project demonstrates how to map analog inputs to pulse-width modulation (PWM) outputs. By turning the knobs on the potentiometers, you can smoothly and independently control the rotation angle (0° to 180°) of each servo motor.

## 🛠️ Hardware Requirements
Based on the circuit design[cite: 9], you will need:
* 1x Arduino Uno board
* 1x Breadboard
* 2x Micro Servo Motors
* 2x Potentiometers (Rotary)
* Jumper wires

## ⚡ Circuit Connections
The wiring is set up as follows[cite: 9]:

**Power Supply:**
* Arduino **5V** -> Breadboard Positive (+) Rail
* Arduino **GND** -> Breadboard Negative (-) Rail

**Potentiometers (Inputs):**
* **Potentiometer 1:** Outer pins to 5V and GND; Middle pin to Arduino **Analog Pin A0**
* **Potentiometer 2:** Outer pins to 5V and GND; Middle pin to Arduino **Analog Pin A1
