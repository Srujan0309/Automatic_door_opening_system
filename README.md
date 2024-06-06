# Automatic Door Opening System using 8051 Microcontroller

## Description

This project involves the development of an Automatic Door Opening System utilizing the 8051 microcontroller. The system is designed to control the opening and closing of a door based on sensor input, enhancing automation and convenience in various applications such as smart homes and secure access points.

## Components Used

- **Microcontroller:** 8051
- **Sensors:** Input sensor connected to P1^4
- **Actuators:** Control pins for door motor connected to P1^1 and P1^2
- **Other Components:** Resistors, Breadboard, Connecting Wires, Power Supply

## Working Principle

The system operates by continuously monitoring the state of an input sensor, which triggers the opening and closing mechanism of the door. The functionality is structured as follows:

### Initialization

- The sensor pin is configured as input.
- The control pins for the door motor are configured as outputs.

### Monitoring and Control

- The system runs in an infinite loop, continuously checking the state of the sensor.
- If the sensor input is high (inp == 1), the door motor is activated to open the door for a specified duration, then close it after another duration.
- If the sensor input is low (inp == 0), the door remains closed.

## Outcome

The Automatic Door Opening System effectively monitors sensor input and controls the door's opening and closing mechanism, providing an automated solution for door management. This project demonstrates my skills in embedded systems, real-time control, and practical applications of microcontroller programming.

## Usage

To use this project, load the code onto an 8051 microcontroller, connect the sensor and motor control pins as specified, and power the system. The door will open or close based on the sensor input.

## Future Enhancements

- Add a buzzer or alarm for unauthorized access.
- Implement a timer to control how long the door stays open.
- Integrate with IoT for remote monitoring and control.



