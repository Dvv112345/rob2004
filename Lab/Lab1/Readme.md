# Laboratory 1

Welcome to the first laboratory of the semester. Throughout the semester, we will use a 3 degrees of freedom robot the NYU Finger and a simulation of the robot.

<img src="images/nyu_finger_1.jpg" width="200"> <img src="images/nyu_finger_simu.png" width="200">

The NYU finger is an [open source](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware) torque-controlled robot, based on the leg of a quadruped robot, [Solo12](https://open-dynamic-robot-initiative.github.io/). It means that you could in principle build your own and improve it! Videos of the quadruped can be found [here](https://www.youtube.com/channel/UCx32JW2oIrax47Gjq8zNI-w)

## Goals
The goal of the laboratory are
1. learn how to access sensors and actuators
2. understand the sense-plan-act loop
3. write your first controller


## Pre-requisites
Most of the lab can be done on your personal computer (except the real-robot part). All the required software is installed on the lab computers but to do the lab on your machine, you will need to have installed on your machine. To do so, follow the instructions [here](../../docs/Installation.md).

## Step 1: Typical control loops with sensors and actuators
Complete the [sensors_and_actuators Jupyter Notebook](sensors_and_actuators.ipynb)

## Step 2: Closing the loop with a PD controller
Complete the [pd_controller Jupyter Notebook](pd_controller.ipynb)