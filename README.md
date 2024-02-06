# Autonomous Line Following Robot Project

## Overview
This repository contains the source code and documentation for the final project of the Embedded Systems class (during the Fall 2023 semester) at New York University Abu Dhabi; an autonomous robot designed for line following inspired by the RoboCupJunior Rescue Line Rules 2018. The project aims to develop a robot that can navigate a predefined course marked by a black line while overcoming various challenges, including intersections, green squares, and red stop lines.

## Project Objectives
The main objectives of the project are:
- Implementing line following algorithms for accurate navigation.
- Detecting and responding to green squares for decision-making.
- Identifying and stopping at red lines to simulate real-world scenarios.
- Developing intersection detection and decision-making capabilities.
- Ensuring robustness in different environmental conditions, including lighting variations.

## Project Structure
- **src**: Contains the Python source code for image processing and robot control.


## Main Approach and Features

- **Line Following**: Utilizes computer vision algorithms to enable the robot to follow a black line on the floor accurately.

- **Green Square Detection**: Implements image processing to identify green squares on the course. The robot makes decisions based on the size of the green square, determining whether to continue forward, turn left, or turn right.

- **Red Stop Line Detection**: Incorporates mechanisms to detect a red line on the floor, signaling the robot to stop its movement.

- **Intersection Handling**: Uses intersection detection algorithms to identify the center of intersections on the black road. The robot decides the direction to turn based on the position of the green square relative to the intersection.

- **Real-time Decision Making**: Employs real-time processing to make navigation decisions on-the-fly, ensuring dynamic responsiveness to changing course conditions.

- **Robustness Testing**: Tested under various lighting conditions and environments to ensure robust performance in different scenarios.

- **OpenCV Integration**: Leverages the OpenCV library for image processing, contour detection, and other computer vision tasks.


## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies. 
3. Connect the robot hardware and camera.
4. Run the main script. 
5. Monitor the robot's behavior through the provided Jupyter Notebook or real-time camera feed.

## Dependencies
- OpenCV: [Link to OpenCV](https://opencv.org/)
- NumPy: [Link to NumPy](https://numpy.org/)

## Contributors
- Aya El Mir
- Lukelo Luoga
- Kirubel Solomon Tesfaye
