# Control of Rover Arm Using Controller

## Overview

Converts joystick inputs to meaningful messages to control the robotic manipulator of the rover.

## Features

* Subscribes to the topic /joy\_arm that gets Joystick input.  
* Performs some operations, such as addition and subtraction, and also scales to 255 to make sense of the joystick inputs.  
* Publishes this message to the topic /stm\_write as an Int32MultiArray.

## Requirements

* Joystick or Controller  
* joy.launch, which is the launch file for both controllers.  
* Robotic manipulator which subscribes to the topic /stm\_write

## Usage

* Connect to a joystick as per joy.launch  
* Launch the joy.launch file  
* Control using the controller.

## Configuration

Configuring the joystick/controller might be necessary. Configuration can be done by changing the dev and remap tags in the joy.launch file. The dev tag clarifies which joystick is used to give input. The remap tag is used to change the topic name.

## License

Take lite bro.  
