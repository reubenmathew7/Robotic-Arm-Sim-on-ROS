# ROS-Based Robotic Arm Simulation

## Requirements

This project was built using ROS Melodic Morenia on Ubuntu 18.04.

## Why I Built This Project

This project was driven by a deep fascination with robotics and automation, particularly the integration of advanced technologies to create intelligent systems. The goal was to explore and enhance my understanding of robotic arm simulations while leveraging tools like ROS, MoveIt, and Gazebo to bridge the gap between theoretical concepts and practical applications in robotics.

## What This Project Does

The ROS-Based Robotic Arm Simulation provides a comprehensive framework for simulating and controlling a robotic arm. Key functionalities include:

- **3D Model Integration**: Converts SOLIDWORKS models into URDF format for compatibility with ROS.
- **Motion Planning and Control**: Utilizes MoveIt for precise motion planning and control of the robotic arm.
- **Physics Simulation**: Implements Gazebo for realistic physics-based simulation.
- **Visualization**: Employs RViz for real-time visualization of the robotic arm's movements.
- **Automation**: Includes custom Python scripts to automate repetitive or complex arm movements.

## How It Works

1. **Model Conversion**: A 3D model of the robotic arm is designed in SOLIDWORKS and converted into a URDF file, making it compatible with the ROS framework.
2. **Simulation Setup**: The URDF file is integrated into a ROS Catkin workspace, where MoveIt is configured for motion planning, and Gazebo is set up for physics-based simulation.
3. **Visualization**: RViz is used to visualize the robotic arm's movements, enabling real-time monitoring and debugging.
4. **Automation Scripts**: Custom Python scripts are developed to programmatically control the arm's movements, allowing for complex operations without manual intervention.

## Results

This project successfully demonstrated the simulation of a robotic arm in a virtual environment, achieving:

- Seamless integration of 3D models into the ROS ecosystem.
- Effective motion planning using MoveIt with collision avoidance.
- Realistic visualization and physics simulation through RViz and Gazebo.
- Enhanced automation capabilities via Python scripting, enabling efficient task execution.

Through this project, I gained valuable hands-on experience with robotics software tools and strengthened my skills in system integration and automation.
