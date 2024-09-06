# Deliveri-Bot: Autonomous Hotel Delivery Robot
## Project Overview
Deliveri-Bot is an AI-powered autonomous robot designed to revolutionize hotel room service deliveries. By automating the delivery process, we aim to enhance guest experience and improve operational efficiency in the hospitality industry.

## Features

Autonomous Navigation: Advanced algorithms for navigating dynamic indoor environments
Obstacle Avoidance: Real-time detection and avoidance of static and moving obstacles
Secure Delivery Protocols: Ensuring safe and secure delivery of items to guest rooms
AI-Powered Decision Making: Optimal route planning and task prioritization
Integration with Hotel Management Systems: Seamless coordination with existing hotel infrastructure

## Technologies Used

ROS (Robot Operating System)
Python
PyTorch
TensorFlow
OpenCV
Gazebo (for simulation)
SLAM algorithms
Git (for version control)

## Setup and Installation

Clone the repository:
git clone "https://github.com/manojkumareedhara/delivery_bot_description.git"

cd deliveri-bot

Install dependencies:
 pip install -r requirements.txt

Set up ROS environment (assuming ROS is already installed):
 source /opt/ros/noetic/setup.bash
catkin_make

Configure simulation environment:
 roslaunch deliveri_bot gazebo_simulation.launch


## Usage

Start the Deliveri-Bot system:
 roslaunch deliveri_bot main.launch

For simulation and testing:
 rosrun deliveri_bot test_navigation.py

To integrate with hotel management system, update the configuration in config/hotel_integration.yaml

### Contributing
We welcome contributions to the Deliveri-Bot project! Please read our CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.
