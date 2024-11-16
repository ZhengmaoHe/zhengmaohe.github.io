---
title: Large Drone Robot Based On Visual Aid - R&D Representative
date: 2023-08-29T00:00:00.000Z
summary: A six-axis drone with a diameter of 170cm that can hover in the air and firing rubber balls.
# tags:
# links:
#   - icon_pack: fab
#     icon: github
#     url: https://github.com/zhmaohe/Goda
#     name: code
# image:
#   focal_point: Center
#   preview_only: false
#   filename: goda.gif

#example
# title: "python-yaml2bib"
# summary: "[`yaml2bib`](https://github.com/basnijholt/yaml2bib): Convert a readable `yaml` file with DOIs *only* to a properly formatted BibTeX file. 📃"
# tags:
#   - latex
#   - bibtex
#   - python
#   - converter
#   - yaml
# date: "2019-03-12T00:00:00"
# external_link: "https://github.com/basnijholt/yaml2bib"

---
1. Drone Motion Control
    * Gimbal control
        * According to the gimbal model, design the feed-forward-serial controller to realize the gimbal motion and muzzle launch.
        * Use CAN, UART and other communication protocols to realize the bottom control.
    * Airframe control
        * Combine the UAV model and simulation test to design the controller.
        * Application development of DJI A3 Onboard SDK on STM32 chip and deployment of the above controller.
        * Fuse sensor data such as optical flow and TOF to achieve centimeter-level fixed-point hovering.
2. Joint commissioning:
        * Transmit height, speed and other data to NUC through serial protocol, and receive gimbal target angle.
        * Adopt Kalman filter to make the gimbal can follow the target angle smoothly.

* Innovation:
    * Design a new type of gimbal self-stabilization model, which can avoid the effect of launch vibration on self-stabilization effect and reduce the cost significantly.
    * Creatively designed a self-stabilization algorithm for the launch state vehicle based on a simplified model, so that the UAV can maintain centimeter-level precision hovering in the muzzle high-frequency launch state.
