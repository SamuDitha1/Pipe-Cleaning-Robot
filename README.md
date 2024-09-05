# Pipe-Cleaning-Robot
## Introduction
This project presents a pipe-cleaning robot designed to navigate and clean horizontal pipelines efficiently. The robot integrates various mechanical and electrical components, along with MATLAB simulations and SolidWorks design. This documentation details the design, implementation, and functionalities of the robot system, including clog detection, motor control, and cleaning mechanisms.

## System Overview
The robot operates by detecting clogs inside pipelines using sensors, then using a rotating brush and water jet to remove debris. The project combines SolidWorks 3D modeling for mechanical design and MATLAB Simulink for simulation and control system verification.


## Functionalities
### Core Features
Clog Detection: Identifies clogs inside the pipeline using sensor data, allowing the robot to adjust its operation.
Motor Control: Uses DC motors to drive the robot and control the rotating brush for cleaning.
Water Jet Cleaning: A rotating water jet is used to remove dirt and debris from pipe walls.
Brush Cleaning: A rotating brush further aids in scrubbing the interior of the pipe.
Simulink Simulation: Models the robot's movement and cleaning process, providing an accurate simulation of its performance.
### Advanced Features
Autonomous Navigation: The robot can traverse the pipeline autonomously, adjusting speed and movement based on real-time sensor feedback.
Persistent Data Storage: Stores sensor readings and operational data for post-run analysis.
Environmental Monitoring: Continuously monitors the pipeline's condition and adjusts cleaning mechanisms accordingly.
## Software Architecture
Mechanical Design (SolidWorks)
The mechanical design is created using SolidWorks, where key components such as the rotating brush, wheels, and water jet are modeled and assembled.
The design considers factors like pipeline diameter, debris type, and durability of materials.
MATLAB Simulation (Simulink)
The system is modeled in MATLAB Simulink to simulate the robot's behavior in real-time.
Includes:
DC Motor Model: For both the robot's movement and the brush rotation.
Clog Detection Model: Simulates sensor input for detecting blockages in the pipeline.
Motor Control: Adjusts the robot's speed based on the clog detection model.
Sensor Integration
Integrates sensors to monitor and react to pipeline conditions.
Clog Detection Sensors: Detect blockages and trigger the cleaning mechanism.
Environmental Sensors: Monitor conditions such as temperature, pressure, and pipeline integrity.

## Hardware Components
The pipe-cleaning robot includes the following hardware components:

DC Motors: Powers both the robot's movement and the rotating brush.
Rotating Brush: Cleans the interior of the pipe by scrubbing debris.
Rotating Water Jet: Provides a high-pressure water jet for removing stubborn dirt.
Wheels: Polyurethane wheels designed to move smoothly inside pipelines.
Sensors: Detect clogs and environmental conditions inside the pipe.
Note: Hardware adjustments may require reconfiguration of the control system.

## Requirements
### Hardware
DC Motors (for movement and brush rotation)
Rotating Brush
Rotating Water Jet
Sensors for clog detection
Wheels (Polyurethane)
Stainless Steel Frame
### Software
MATLAB & Simulink
SolidWorks
Arduino (if using microcontroller for motor control)
## Installation
### Hardware Setup
Assemble the robot components as detailed in the design section.
Connect the DC motors, sensors, and rotating mechanisms as described in the port map.
### Software Setup
Clone the repository:
bash
Copy code
git clone https://github.com/SamuDitha1/pipe-cleaning-robot.git
Open the SolidWorks model for 3D design.
Open MATLAB and load the Simulink model for simulation.
Run the simulation to observe the robot’s cleaning process in a virtual environment.
Usage
Running MATLAB Simulations
Open MATLAB and load the Simulink model (pipe_cleaning_simulink.slx).
Run the simulation to see the robot's performance in detecting and cleaning clogs.
Accessing SolidWorks Designs
Open the SolidWorks file (robot_design.SLDPRT) to visualize or modify the robot's mechanical design.
Contributors
Samuditha Hettiarachchi - Lead Developer and Designer
License
This project is licensed under the MIT License - see the LICENSE file for details.

