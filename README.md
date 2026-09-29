# ESP32-DC-Motor-Control
ESP32-based DC motor control system with forward, reverse, stop, and PWM speed control.


## DC Motor Speed Control Using H Bridge MOSFET Circuit & ESP32-
The **ESP32-Based DC Motor Control System** is an embedded control project designed to control the **direction and speed of a DC motor** using an ESP32 microcontroller. The system provides **forward, reverse, and stop** control along with **PWM-based speed regulation**.

The ESP32 generates control signals for a MOSFET-based H-bridge motor driver, allowing the motor's direction to be changed electronically. PWM is used to vary the effective voltage supplied to the motor and thereby control its speed.

The system also includes a **web-based control interface**, through which the user can send commands to the ESP32 for motor operation. A **12 V DC supply** is used for the motor, while a **7805 voltage regulator** provides the required regulated supply for the control circuitry.

### Key Features
* Forward and reverse DC motor rotation
* Motor start/stop control
* PWM-based motor speed control
* Web-based motor control using ESP32
* MOSFET-based H-bridge motor driver
* Separate motor and control power handling
* Hardware-based embedded motor control

### Hardware Used
* ESP32 development board
* DC motor
* IRLZ44N N-channel MOSFET
* IRF4905 P-channel MOSFET
* 7805 voltage regulator
* 12 V DC power supply
* Heat sinks
* Connecting wires and supporting components

### Software & Technologies
* Embedded C
* Arduino IDE
* ESP32
* PWM
* GPIO
* Wi-Fi
* Web-based control
* MOSFET-based motor driving

### Working Principle
The user sends a command through the web interface. The ESP32 receives the command and generates appropriate GPIO and PWM signals for the MOSFET-based H-bridge circuit.

Depending on the command:
**Forward →** Motor rotates in the forward direction.
**Reverse →** Motor rotates in the reverse direction.
**Stop →** Motor is stopped.
**Speed Control →** The PWM duty cycle is varied to control the motor speed.

The project demonstrates the integration of **microcontroller programming, digital control, PWM, power electronics, Wi-Fi communication, and hardware interfacing** in an embedded system.

### Applications
The concept can be extended to:
* Industrial motor control
* Conveyor systems
* Robotics
* Automated machinery
* IoT-based motor control
* Smart actuator systems
