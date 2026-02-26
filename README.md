🌡️ Embedded Systems Portfolio – Smart Thermostat & Serial Control
Project Overview

In this course, I developed two embedded systems projects using a Raspberry Pi. The goal was to apply hardware–software integration principles and structured architecture to real-world device control problems.

The first project focused on serial communication and GPIO control. The second expanded into a fully integrated smart thermostat prototype using sensing, state management, display control, and communication protocols.

Together, these projects demonstrate growth from basic hardware interaction to structured embedded system design.

Provided Code

The projects included:

Raspberry Pi hardware platform

GPIO mappings and circuit configuration

Sensor and display wiring setup

Base environment structure

These components handled the physical interface and hardware layer.

Code I Implemented
Serial Light Control (Module Two)

Configured UART serial communication

Implemented command parsing using match-case

Controlled GPIO output for LED actuation

Ensured safe GPIO cleanup and program exit

Smart Thermostat Prototype (Module Seven)

Implemented a formal state machine with off, heat, and cool states

Built temperature comparison logic tied to a configurable setpoint

Configured PWM LED behavior for heating and cooling indicators

Developed button event handlers for state cycling and setpoint adjustment

Integrated I2C communication for temperature sensing

Implemented LCD display management with time and system data

Built a UART output routine for transmitting status updates

Added multithreading for non-blocking display updates

What This Project Demonstrates

These projects reflect core embedded systems concepts, including:

Hardware–software integration

GPIO configuration and control

Communication protocol implementation (UART and I2C)

State-driven architecture

Event-based input handling

Multithreaded system coordination

They demonstrate progression from single-device control to coordinated multi-component embedded systems.

What Computer Scientists Do and Why It Matters

Computer scientists design systems that connect software logic to real-world hardware. In embedded systems, this means managing sensors, outputs, and communication interfaces through structured architecture.

These systems are foundational in IoT devices, automation platforms, and smart infrastructure where reliability and scalability are critical.

How I Approach Problems

Understand hardware constraints and interfaces

Define clear system states and transitions

Separate hardware control from application logic

Implement incrementally

Test under realistic operating conditions

Refine for stability and maintainability

Ethical Considerations

Responsible embedded system design requires attention to:

Reliability and predictable behavior

Safe hardware initialization and shutdown

Stable automated control logic

Long-term maintainability and scalability

Technologies Used

Python

gpiozero

RPi.GPIO

Adafruit CircuitPython

I2C protocol

UART serial communication

Python statemachine library

Multithreading

Key Skills Demonstrated

Embedded systems architecture

State machine implementation

Serial communication configuration

Hardware debugging and integration

Modular system design

Structured problem solving
