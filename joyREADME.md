# Joystick ROS Launch File for Rover Teleop

# Overview

This is a launch file that uses the ROS driver package “joy”, in order to use Linux joysticks or game controllers to send joystick messages to ROS nodes. It establishes communication between two joysticks, one for traversal and one for the arm of the rover,  with other ROS nodes that might require joystick inputs, by subscribing to the /joy topic.

# Features

* It launches ROS communication between two joysticks.  
* The joystick input can be subscribed to.  
* Connect the first two joysticks connected by default.

# Requirements

* ROS distribution.  
* Joy package.  
* Two compatible joysticks.

# Usage

Run the following command to use this launch file:

\>\~$ roslaunch \~/RoverH2024/joy.launch

# Configuration

* To change the joystick connected, change the dev parameter.  
* To change the topic, change the remap tag.

# License

Take lite bro.

