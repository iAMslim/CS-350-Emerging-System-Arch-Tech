🔧 CS 350 – Embedded Systems Portfolio
🌡️ Smart Thermostat & Serial Control Projects
📌 Project Overview

In this course, I developed two embedded systems projects using a Raspberry Pi.

The first focused on serial communication and GPIO control.
The second evolved into a fully integrated smart thermostat prototype combining sensing, state management, display control, and communication protocols.

Together, these projects demonstrate progression from basic hardware interaction to structured embedded system architecture.

🧩 Project One – Serial Light Control
File

SerialLightControl-Server.py

What It Does

This project implements UART serial communication to control an LED through GPIO output. The Raspberry Pi listens for incoming commands and toggles the LED accordingly.

What I Implemented

Configured UART serial interface

Implemented command parsing using match-case

Controlled GPIO output using Broadcom numbering

Ensured safe GPIO shutdown and cleanup

What This Demonstrates

Serial communication setup

Low-level GPIO control

Structured command handling

Safe hardware lifecycle management

🌡️ Project Two – Smart Thermostat Prototype
File

Thermostat.py

What It Does

The thermostat integrates multiple hardware components into a cohesive embedded system:

Reads temperature via I2C (AHT20 sensor)

Implements a formal state machine (off, heat, cool)

Controls LEDs using PWM

Handles user input through physical buttons

Updates a 16x2 LCD display

Sends comma-delimited status updates over UART every 30 seconds

Uses multithreading for non-blocking display updates

Architectural Focus

Rather than relying on basic conditional logic, the system is structured around a state-driven architecture. This improves:

Predictability

Readability

Maintainability

Scalability

🚀 What These Projects Demonstrate

Hardware–software integration

Communication protocol configuration (UART & I2C)

State machine implementation

Event-driven system design

Multithreaded coordination

Modular embedded architecture

🧠 How I Approach Embedded Problems

Define system states clearly

Separate hardware control from application logic

Implement incrementally

Validate under realistic conditions

Refine for stability and maintainability

🛠 Technologies Used

Python

gpiozero

RPi.GPIO

Adafruit CircuitPython

I2C protocol

UART serial communication

Python statemachine library

Multithreading

💡 Key Skills Demonstrated

Embedded systems architecture

State machine design

Serial communication configuration

Hardware debugging and integration

Modular system development

Structured problem solving
