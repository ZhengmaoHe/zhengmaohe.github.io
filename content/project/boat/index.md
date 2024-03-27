---
title: Yolov4-Assisted Unmanned Surface Waste Collection Vessel - Electric Control Group Leader
date: 2023-08-29T00:00:00.000Z
summary: An unmanned ship was successfully delivered to Guangzhou River Management Center and put into use.
---

1. Preliminary work
	* Recruiting teammates in the fields of mechanical, hardware and hydraulic engineering.
	* Determine the implementation plan according to the needs of Party A (Guangzhou River Management Centre) and various literature
2. Boat motion control
	* Read various Chinese and foreign literature, combined it with the actual situation, and designed a set of MCU-NUC joint control schemes.
	* Used the cascade control system to complete the motion control.
	* Use CAN, UART and other communication protocols to realize the bottom control.
3. Joint commissioning:
	* Used the serial protocol to receive the target position identified by Yolov4 on Xavier NX.
	* Used the Kalman filter algorithm made the boat follow the target garbage more smoothly.
* Result: 
	* The finished unmanned ship was successfully delivered to Guangzhou River Management Center and put into use;
	* Received several awards and made applications for patents and software copyrights.
