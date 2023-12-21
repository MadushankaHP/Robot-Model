# Robot-Model
This repository contains ROS (Robot Operating System), Gazebo, and Unity integration for the Waveshare JetBot ROS AI Kit. The kit includes a URDF model for the robot with  a CSI camera and RealSense depth camera.

**Prerequisites**

Before using this code, make sure you have the following installed:

1. ROS (Robot Operating System) - [Installation Guide](https://wiki.ros.org/Installation).

**Setup**

1. Clone this repository to your ROS workspace:

   ```bash
   git clone https://github.com/MadushankaHP/Robot-Model.git
   
2. Build the ROS workspace:
   ```bash
   cd your_ros_workspace
   catkin_make
   source devel/setup.bash

**Usage**

Launch the Robot model node:
   ```bash
   roslaunch jetbot_model display_jet_csi.launch
   ```
   ```bash
   roslaunch jetbot_model display_jet_real.launch
   ```
