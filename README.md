# Autonomous Robot Control System

This repository contains the code for controlling an autonomous robot with obstacle detection and line-following capabilities.

## Components Used
- Arduino Uno
- Infrared (IR) sensors
- Ultrasonic sensor
- DC Motors

## Wiring
- Right motor: 
  - Enable pin: 6
  - Pin 1: 7
  - Pin 2: 8
- Left motor: 
  - Enable pin: 5
  - Pin 1: 9
  - Pin 2: 10
- IR Sensors: 
  - Right sensor: A1
  - Left sensor: A3
  - Middle sensor: A2
- Ultrasonic sensor: 
  - Trigger pin: 3
  - Echo pin: 11

## Setup
1. Connect the components according to the wiring mentioned above.
2. Upload the provided code to your Arduino Uno board.
3. Open the serial monitor to observe the output.

## Operation
The robot is programmed to perform the following tasks:
- Line-following: It uses the IR sensors to detect black lines on the ground and adjust its path accordingly.
- Obstacle detection: It uses the ultrasonic sensor to detect obstacles in its path and stop or change direction accordingly.

## Usage
1. Ensure that the environment has black lines for the robot to follow.
2. Place obstacles within the detection range of the ultrasonic sensor.
3. Power on the robot and observe its behavior.

## Note
- Adjust the motor speed (`MOTOR_SPEED`) as per your requirements.
- Ensure proper calibration of sensors for accurate detection.
- This code serves as a basic framework and can be expanded upon for more complex behaviors.

