---
title: Optimization-Based Wheeled-Bipedal Robot
date: 2023-08-29T00:00:00.000Z
summary: My graduation project
links:
  - icon_pack: fab
    icon: github
    url: https://github.com/zhmaohe/Goda
    name: code
---

* Version one, [video](https://www.bilibili.com/video/BV1ee4y1U7i2)
	* Simplify the two-wheeled foot model to an inverted pendulum model and apply Newton's Euler equation to obtain the state-space equations of the system.
	* Control with **Linear Quadratic Regulator (LQR)**
	* Used **Virtual Model Control (VMC)** to obtain a mapping of forces and moments in the workspace to moments in the joint space.
* Version two
	* Neglect the robot leg dynamics and use **Single Rigid Body Dynamics (SRBD)** to obtain the state space equations of the system.
	* Using **convex model predictive control (Convex-MPC)** to solve the optimal ground reaction force
	* Using **Whole Body Control (WBC)** Based on Hierarchical Quadratic Optimization (HQP) to solve joint moments(unfinished)
	* Motion state planning using finite state machine (FSM)
	* Build the Webots simulation environment and the robot model on a Linux system based on the ROS platform.
