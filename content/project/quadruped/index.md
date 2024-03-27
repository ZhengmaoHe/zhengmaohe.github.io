---
title: A quadruped robot with 12-DOF parallel legs
date: 2023-08-29T00:00:00.000Z
summary: " "
---
1. Deriving the Kinematics Model of a Quadruped Robot
	* Deduced the relationship between the position of the foot end and the motor angle through forward and inverse kinematics.
	* Differential the kinematic equation of the leg to obtain the Jacobian matrix, which is the relationship between the joint speed and the foot tip speed.
2. Design Control Algorithm
	* Use trigonometric functions and polynomial functions to plan the trajectory of the foot, and make the foot follow the trajectory through inverse kinematics
	* Simulation development on the webots platform
3. Realized on physical robot
	* Develop based on ROS and deploy the code to NUC
	* Adjust the parameters according to the actual situation
    
* Result: 
	* The robot helped the team win the "National Third Prize".