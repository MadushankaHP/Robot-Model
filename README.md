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
1. ROS
   Launch the Robot model node:
      ```bash
      roslaunch jetbot_model display_jet_csi.launch
      ```
      ```bash
      roslaunch jetbot_model display_jet_real.launch
      ```
   After running the launch file, you can import the robot model through the RViz view.As shown in the figure 1 below.
   
   ![rviz_screenshot_2023_07_21-15_51_04](https://github.com/MadushankaHP/Robot-Model/assets/68281297/585af19e-efb3-4ec2-a6b6-e40954512f90)

   Additionally, a demo video is available [here](https://youtu.be/1bNIfHKPuOc).


3. Unity
   
   
