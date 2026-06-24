# AR Core 2 - Task 3

This repository contains a ROS 2 workspace for a simple Autonomous Mobile Robot (AMR) model built using URDF (Unified Robot Description Format). The project demonstrates robot modeling, wheel integration, TF frame generation, and visualization in RViz2 using both Python and C++ launch approaches.

# Project Structure

```text
AR_core2_task3/
├── amr_ws_cpp/
│   └── src/
│       └── amr_description/
│           ├── urdf/
│           ├── CMakeLists.txt
│           └── package.xml
│
├── amr_ws_py/
│   └── src/
│       └── amr_description/
│           ├── urdf/
│           ├── CMakeLists.txt
│           └── package.xml
│
├── py_amr_urdf.png
├── cpp_amr_urdf.png
├── README.md
└── .vscode/
    └── settings.json


## 🎯 Objective

The goal of this project is to:

* Build a simple four-wheeled AMR using URDF
* Understand robot structure definition in ROS 2
* Visualize robot models and coordinate frames in RViz2
* Learn robot modeling workflows using both Python and C++ launch files



## 🧩 Features

* ROS 2 package structure (amr_description)
* URDF-based AMR model
* Four-wheel robot configuration
* TF frame visualization
* RViz2 integration
* Python launch workflow
* C++ launch workflow
* Modular design for future expansion
* Gazebo integration for future improvements



## ⚙️ Requirements

To use this workspace, you should have:

ROS 2 : Jazzy
RViz2 (for visualization)
Gazebo (optional for simulation)



## 🚀 Visualizing the Robot

To visualize the URDF model in RViz:

ros2 launch urdf_tutorial display.launch.py model:=$PWD/amr.urdf
For both the python and c++
make sure you are in the right file directory.


## 📌 Future Improvements

Future upgrades can include:

* Adding wheel joint control
* Integrating sensors (LiDAR, IMU, Camera)
* Gazebo simulation environment
* SLAM and Navigation Stack integration
* Differential drive controller implementation
* Autonomous path planning

## 📚 Learning Outcomes

Through this project, I gained practical understanding of:

* Robot modeling using URDF
* ROS 2 package architecture
* Robot visualization in RViz2
* TF frame management
* Python and C++ launch systems
* Modular robotics system design

## 📜 License

This project is open for learning, educational, and academic use.
