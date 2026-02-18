GESTURE CONTROLLED ROBOT CAR

This project implements a wireless gesture-controlled robotic car using an Arduino Nano, ADXL335 accelerometer, and nRF24L01 RF communication modules.
The system enables intuitive, real-time control of a robotic vehicle through hand gestures, eliminating the need for traditional remote controllers. It demonstrates an accessible and adaptive human–machine interaction model suitable for robotics education, automation systems, and defense-oriented applications

Problem Statement: 
Traditional robotic control systems often rely on joystick-based or button-based interfaces, which may lack intuitiveness and adaptability. Gesture-controlled robotics systems remain limited in accessibility and widespread implementation.
This project addresses these challenges by designing a compact and adaptive system that interprets hand gestures using accelerometer data and transmits commands wirelessly to control robot movement in real time.

System Architecture
The system consists of two primary modules:
1. Transmitter Module (Hand Unit)
Arduino Nano
ADXL335 Accelerometer
nRF24L01 RF Module
The accelerometer captures hand tilt and motion.
Arduino processes the analog signals and converts them into directional commands (forward, backward, left, right).
These commands are transmitted wirelessly using the nRF24L01 module.

2. Receiver Module (Robot Unit)
Arduino Nano
nRF24L01 RF Module
L298N Motor Driver
DC Motors
The receiver module interprets incoming RF signals and controls the motors via the L298N motor driver, enabling real-time gesture-to-motion response.

Working Mechanism
Hand tilts are detected by the ADXL335 accelerometer.
Arduino maps acceleration values to directional commands.
Commands are transmitted wirelessly via nRF24L01.
The receiver Arduino decodes the signal.
L298N motor driver activates motors accordingly.
The robot moves in real time based on hand gestures.

Components Used
Arduino Nano
ADXL335 Accelerometer
nRF24L01 RF Module
L298N Motor Driver
DC Motors
Battery Pack
Chassis
