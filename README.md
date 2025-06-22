# Distance-Measurement-System
# Arduino-Based Ultrasonic Distance Measurement System with LED Indication

This project is a simple yet effective distance measurement system using an *HC-SR04 ultrasonic sensor, an **Arduino board, and **LEDs* for distance indication. The system continuously measures the distance to an obstacle and provides visual feedback using LEDs based on the detected range.

##  Components Used

- Arduino Uno (or any compatible board)
- HC-SR04 Ultrasonic Sensor
- LEDs (Red, Yellow, Green)
- Resistors (220Ω for each LED)
- Breadboard and Jumper wires
- USB cable for programming

##  Working Principle

The *HC-SR04 ultrasonic sensor* measures the time taken for an ultrasonic pulse to travel to an obstacle and back. The Arduino calculates the distance based on this time and lights up the LEDs based on the range:

- *Green LED*: Object is at a safe distance (> 100 cm)
- *Yellow LED*: Object is moderately close (50 cm - 100 cm)
- *Red LED*: Object is very close (< 50 cm)

## Applications

- *Parking assistance system
- *Obstacle detection for robots
- *Safety alert systems

## Key Features

- *Easy to build hardware
- *Low power consumption
- *Visual based alerts
- *Expandable design
