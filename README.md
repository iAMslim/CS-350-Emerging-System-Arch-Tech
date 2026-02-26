CS 350 – Emerging Systems Architectures and Technologies
Embedded Systems Portfolio Artifacts
📌 Overview

This repository contains selected artifacts from CS 350 that demonstrate my development in embedded systems design, hardware–software integration, and structured state-driven architecture.

The projects progress chronologically from early GPIO and serial communication work to a fully integrated smart thermostat prototype. Together, they reflect both technical growth and architectural maturity across the course.

🧩 Module Two Milestone
Serial Light Control Server

File: SerialLightControl-Server.py
Source: 

SerialLightControl-Server

🔎 Purpose

This project was completed during Module Two and represents one of my first structured embedded systems implementations.

The system controls an LED on a breadboard using UART serial communication. The Raspberry Pi listens for commands over the serial interface and turns the LED on or off accordingly.

💡 Skills Demonstrated

UART configuration and serial protocol communication

Broadcom GPIO pin numbering

Safe GPIO initialization and cleanup

Structured command handling using match-case logic

Hardware actuation based on incoming commands

This milestone laid the foundation for understanding how embedded systems communicate across physical interfaces.

🔥 Module Seven Integration / Final Project
Smart Thermostat Prototype

File: Thermostat.py
Source: 

Thermostat

🔎 Purpose

This artifact represents the most advanced system built during the course.

The thermostat prototype simulates the embedded control layer of a commercial smart thermostat. It integrates sensing, user input, state management, display control, and serial communication into a cohesive system.

⚙️ System Features

Reads temperature data via I2C (AHT20 sensor)

Implements a formal state machine with off, heat, and cool states

Controls LEDs using PWM for visual state representation

Handles user input through physical buttons

Updates a 16x2 LCD display with real-time system data

Sends comma-delimited status updates over UART every 30 seconds

Uses multithreading for display management

🧠 Architectural Focus

Rather than relying on simple conditional branching, I structured the thermostat around a formal state machine model. This improved:

Predictability

Readability

Maintainability

Scalability

This shift reflects my progression from “making hardware work” to designing embedded systems intentionally.

🪞 Reflection
🧩 Project Summary

Across these modules, the problem evolved from controlling a single LED through serial input to building a fully integrated smart thermostat prototype.

Before cloud analytics, dashboards, or mobile applications exist, the embedded device itself must reliably:

Sense environmental data

Manage operating states

Respond to user input

Actuate hardware

Communicate status updates

This prototype focuses on building that dependable embedded foundation.

✅ What I Did Well

Designed around a structured state machine architecture

Separated hardware, logic, and display responsibilities

Implemented clean GPIO and serial initialization/cleanup

Improved debugging discipline for hardware-level issues

Transitioned from script-based coding to modular system design

📈 Areas for Improvement

Expand error handling for sensor and serial failures

Introduce abstraction layers for hardware scalability

Implement structured logging for diagnostics

Add fault tolerance for communication interruptions

Future iterations could integrate Wi-Fi and cloud-based APIs to extend functionality.

🛠 Tools and Technologies

gpiozero and RPi.GPIO

Adafruit CircuitPython libraries

Python statemachine framework

UART serial configuration

Multithreading in embedded systems

I2C sensor communication

Beyond software, this project strengthened my ability to interpret hardware documentation, troubleshoot wiring issues, and reason through physical system design.

🔄 Transferable Skills

Event-driven programming

State machine modeling

Hardware–software integration

Communication protocol configuration

Modular architecture design

Embedded debugging methodology

These competencies apply directly to IoT systems, robotics, automation platforms, and distributed edge computing environments.

🧱 Maintainability & Adaptability

The thermostat architecture is designed for extension. By separating responsibilities into structured components, the system can be adapted to include:

Wireless communication

Cloud integration

Additional sensors

Expanded state logic

The design emphasizes clarity, modularity, and scalability.
