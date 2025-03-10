Hey, 
  This project implements a human hand model using URDF (Unified Robot Description Format) in ROS 2. The model was initially written in a standard URDF file and later converted into a Xacro (XML Macros) file to improve modularity and reduce repetitive code.

FEATURES:
1.Five fingers (Thumb, Index, Middle, Ring, and Pinky)
2.Mimic joints for realistic motion of knuckles
3.Xacro macros to simplify and reduce redundant code
4.Revolute joints with motion limits
5.Material properties for visualization
6.Compatible with RViz for simulation

FILE STRUCTURE:
- human_hand_mimic.urdf.xacro  # Xacro file defining the hand structure
- launch/display.launch.py AND ALSO I'VE ADDED XML LAUNCH FILE WHICH IS launch/display.launch.xml # Launch file to visualize in RViz
- rviz/urdf.rviz               # RViz configuration file

