# Line Follower Robot with 8-IR Array Sensors

## Overview

This repository contains the code and documentation for a Line Follower Robot equipped with an 8-Array sensor, Arduino UNO, and an L298-N Motor Driver. The robot is designed to autonomously follow a black line, employing the sensor array to detect the line's path.

## Features

- Utilizes an 8-Array sensor setup for enhanced line detection accuracy.
- Arduino UNO microcontroller manages sensor readings and motor control.
- Stops when reaching an endpoint or continues following the line if no endpoint is detected.
- Improved functionality over previous versions with fewer sensors.

## Hardware Components

- **8-Array Sensors**: Used for line detection.
- **Arduino UNO**: Microcontroller for sensor input processing and motor control.
- **L298-N Motor Driver**: Controls the movement of motors based on sensor readings.

## How It Works

The Line Follower Robot functions by constantly scanning the surface using its 8-Array sensors. It identifies the black line and maneuvers based on sensor readings. When reaching an endpoint, the robot stops, ensuring it does not deviate from the intended path.

## Setup and Usage

1. **Hardware Assembly**:
   - Connect the 8-Array sensors to the designated ports on the Arduino UNO.
   - Attach the L298-N Motor Driver to control the motors.

2. **Upload Code**:
   - Upload the provided `line_follower.ino` code to the Arduino UNO using the Arduino IDE or preferred programming software.

3. **Run the Robot**:
   - Place the robot on the black line surface to initiate its autonomous movement.
   - Observe the robot following the line path and halting at endpoints.

## Files Included

- **line_follower.ino**: Arduino code for the Line Follower Robot.
- **Circuit Diagram.PNG**: Schematic representation of the hardware setup.
- **Line Follower Robot with 8-Array Sensor.jpg**: Image showing the assembled robot.
- **README.md**: This documentation file.

## Notes

- This version of the Line Follower Robot offers improved accuracy and reliability compared to previous iterations with fewer sensors.
- Feel free to modify the code or hardware setup to suit specific requirements.

## Contributors

![hmb_pp](https://github.com/hm-badhon/B-AI-Robotics/assets/85755347/093d31f3-966a-4c6c-8ce6-fd26716b83d9)

- **H.M. Mehedi Hasan (Badhon)**
  - *Associate Robotics Engineer at Next Solution Lab (NSL)*

## License

This project is licensed under [License Name]. [Include license details if applicable.]
