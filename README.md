# Differential Drive Robot with Big Tyres

This repository is being used for a Differential Drive Robot Simulation in Gazebo + Rviz.

## Progress (Platform: ROS1 Kinetic Kame)

- Created a basic base_link (Chassis)

- Wheel Integration

- NEXT: Add collision

## Usage

To use this repository

```bash
  mkdir -p ~/catkin_ws/src
  cd ~/catkin_ws/src
  git clone https://github.com/a-hamzah/ros_robotics.git
  cd ..
  catkin_make
  source ~/catkin_ws/devel/setup.bash
  roslaunch ros_robotics dd_robot_rviz.launch model:=dd_robot.urdf
```

## Screenshots

![Screenshot 2023-09-17 01:09:41](https://github.com/a-hamzah/rev_python/assets/25130682/96af0373-89cd-4258-ba90-d73dc4de8206)

![Screenshot from 2023-09-17 18-44-47](https://github.com/a-hamzah/ros_robotics/assets/25130682/ef5941af-843f-42e6-9e8e-b808ab10bd08)
