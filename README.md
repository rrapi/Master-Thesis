# Master-Thesis
Final work of the M.Sc. degree course in Artificial Intelligence and Robotics - Sapienza, Rome (IT)

## Goal

Develop a framework of AI Planning for the execution of Robotics lab quality
measurements and test the approach on the robots in the P&G robotics lab.

## Brief presentation of the chapters

In ***Chapter 1***, motivations and objectives of this thesis work.

In ***Chapter 2*** an introduction of the Theoretical starting point will be introduced, such as AI
planning, Previous Practice used, Robot Kinematics, Robot Control, Motion Planning,
Cobots, Human-Robot Interaction, Robot Perception and Object Detection.

In ***Chapter 3*** the software technology and tools used for sending commands and control
the robot, perceiving the environment and tracking the system behaviour: Docker, ROS,
Gazebo, MoveIt!, RViz, Transforms, Universal Robotic Description Format (URDF), Petri
Net Plans (PNP) and Plan Execution Interface (PLEXI) frameworks with which the plans
were implemented, OpenCV, ArUco Markers, Roboflow, YOLOv5, Tesseract OCR and
PySimpleGUI is described. Their advantages and disadvantages, how and why they have
been used to develop this thesis.

In ***Chapter 4*** the robot and devices used for performing the experiment product tests:
UR5e robotic arm, Robotiq 2F-85 gripper, Microsoft LifeCam Cinema, Mettler Toledo scale
and Mark-10 Motorized Test Stand is described. Their principal features, how they works
and why have been used in this thesis.

In ***Chapter 5*** the aim and objectives that we wanted to reach with this thesis work are
described. Also a little description of the main problems encountered during this work and
their solution.

In ***Chapter 6*** the Solution Design used for solving the problem. In particular is shown
the Laboratory configuration, The Diagram of the Plan flow used to solve this tasks, the
Action and Fluents implemented that composes the plan, the HRI Recovery procedures used
to resume from a certain unexpected event and the advantages of this solution.

In ***Chapter 7*** the implementation details of the modules realized by me and with
my colleague collaboration will be shown and described, such as the Camera calibration,
connection and interface between Gripper and PC-ROS, the position of the pouch with
respect to the robot, interpolation over gripper grasping angles, the MoveIt! complete robot
configuration for IK and the collision avoidance solution to prevent the robot collide with
objects in the scene.

In ***Chapter 8*** a set of pictures showing the results obtained. Is possible to observe the
robot while opening the drawer, grasping some pouches, or going to Mark-10 position and
waiting for test to be completed.

In ***Chapter 9*** is done a discussion about this work and which could be the future works.

In ***Chapter A*** will be described some technical aspects used in this thesis, such as Drivers
and packages used to make the robot work properly.

In ***Chapter B*** more details about the tools and software are described.
