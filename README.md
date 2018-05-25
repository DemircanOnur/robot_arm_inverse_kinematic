# robot_arm_inverse_kinematic

This project created by Onur Demircan at Selcuk University as a school project.
Project includes 6-axis robot arm. 
URDF represents visual and collision of robot arms's joint and link.
5_axis_robot_arm.cpp provide robot inverse kinematics as for that user's input point x,y,z.

For work this project follow guide:

$roscore  (Open rosmaster)

$gazebo   (Open gazebo)

//İf you encountered gazebo errors use:

$gazebo -verbose

$rosrun robot_arm 5_axis_robot_arm (Running Inverse kinematic script)

The result must be figure 1.


joint1: revolute, along z axis, between base_link and link1;
joint2: revolute, along y axis, between link1 and link2;
joint3: revolute, along y axis, between link2 and link3;
joint4: revolute, along y axis, between link3 and link4;
joint5: prismatic, along y axis, between link4 and link5;
joint6: prismatic, along y axis, between link4 and link6;
