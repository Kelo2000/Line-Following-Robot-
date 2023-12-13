# Embedded_Systems_Fall2023
# Autonomous Robot Line Following Project

## Overview
This repository contains the source code and documentation for an autonomous robot designed for line following inspired by the RoboCupJunior Rescue Line Rules 2018. The project aims to develop a robot that can navigate a predefined course marked by a black line while overcoming various challenges, including intersections, green squares, and red stop lines.

## Project Objectives
The main objectives of the project are:
- Implementing line following algorithms for accurate navigation.
- Detecting and responding to green squares for decision-making.
- Identifying and stopping at red lines to simulate real-world scenarios.
- Developing intersection detection and decision-making capabilities.
- Ensuring robustness in different environmental conditions, including lighting variations.

## Project Structure
- **src**: Contains the Python source code for image processing and robot control.
- **docs**: Documentation files, including project guidelines, specifications, and flowchart explanations.
- **tests**: Unit tests for validating the functionality of different modules.
- **images**: Sample images used for testing and documentation.

## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Connect the robot hardware and camera.
4. Run the main script: `python main.py`.
5. Monitor the robot's behavior through the provided Jupyter Notebook or real-time camera feed.

## Dependencies
- OpenCV: [Link to OpenCV](https://opencv.org/)
- NumPy: [Link to NumPy](https://numpy.org/)

## Contributors
- [Your Name]
- [Contributor 1]
- [Contributor 2]

## License
This project is licensed under the [MIT License](LICENSE).
