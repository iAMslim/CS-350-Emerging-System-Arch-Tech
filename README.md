# 🌡️ Smart Thermostat & Serial Control – Embedded Systems Project  

## Project Overview  

In this project, I developed two embedded systems applications using a Raspberry Pi. The goal was to apply hardware–software integration and structured architecture to real-world device control problems.

The first project implemented serial communication to control hardware output. The second evolved into a fully integrated smart thermostat prototype using sensing, state management, display control, and communication protocols.

Together, these projects demonstrate progression from basic GPIO interaction to coordinated embedded system design.

---

## Provided Code  

The project included:

- Raspberry Pi hardware platform  
- Predefined GPIO mappings  
- Sensor and display wiring configuration  
- Base system framework  

These components handled the hardware environment and interface layer.

---

## Code I Implemented  

I focused on building and integrating the system logic. Specifically, I:

- Configured UART serial communication for LED control  
- Implemented command parsing using `match-case`  
- Controlled GPIO output safely and predictably  
- Implemented a formal state machine with `off`, `heat`, and `cool` states  
- Built temperature comparison logic tied to a configurable setpoint  
- Configured PWM LED behavior for heating and cooling indicators  
- Developed button event handlers for state cycling and setpoint adjustment  
- Integrated I2C communication for temperature sensing  
- Implemented LCD display management with time and system data  
- Built a UART routine to transmit comma-delimited status updates  
- Added multithreading to manage non-blocking display updates  

---

## What This Project Demonstrates  

This project reflects core embedded systems concepts, including:

- Hardware–software integration  
- State-driven architecture  
- Communication protocol configuration (UART and I2C)  
- Event-based input handling  
- Multithreaded coordination  

More broadly, it demonstrates how structured software design can coordinate physical components into a reliable embedded device.

---

## What Computer Scientists Do and Why It Matters  

Computer scientists design systems that connect abstract logic to real-world functionality. In embedded systems, this means coordinating sensors, outputs, and communication interfaces through structured architecture.

These systems form the foundation of IoT devices, automation platforms, and smart infrastructure where reliability and scalability are critical.

---

## How I Approach Problems  

This project reflects how I approach technical challenges:

1. Define the system states and transitions  
2. Separate hardware control from application logic  
3. Implement incrementally  
4. Test under realistic operating conditions  
5. Refine for stability and maintainability  

Rather than expecting immediate success, I focused on structured iteration and performance validation.

---

## Ethical Considerations  

Even in embedded systems development, responsible design is important. It is necessary to consider:

- Reliability and predictable behavior  
- Safe hardware initialization and shutdown  
- Stability in automated decision-making  
- Long-term maintainability and scalability  

---

## Technologies Used  

- Python  
- gpiozero  
- RPi.GPIO  
- Adafruit CircuitPython  
- I2C protocol  
- UART serial communication  
- Python `statemachine` library  
- Multithreading  

---

### Key Skills Demonstrated  

- Embedded systems architecture  
- State machine implementation  
- Serial communication configuration  
- Hardware debugging and integration  
- Modular software design  
- Structured problem solving  
