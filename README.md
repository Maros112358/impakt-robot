# IMPAKT-ROBOT
ROS package for robot for mobile robotics on MFF UK

This robot uses robotic platform **MP-500** and robotic arm **UR-5**:
- **MP-500** https://www.neobotix-robots.com/products/mobile-robots/mobile-robot-mp-500
- **UR-5** https://github.com/ros-industrial/universal_robot

# Install
To install the robot, run the following commands:
```
cd <your_ws>/src
git clone https://github.com/Maros112358/impakt-robot.git
git clone https://github.com/neobotix/neo_simulation.git
git clone https://github.com/neobotix/neo_kinematics_differential
git clone https://github.com/neobotix/neo_msgs.git
git clone https://github.com/neobotix/neo_srvs.git
git clone https://github.com/neobotix/neo_common.git
git clone https://github.com/neobotix/neo_localization.git
git clone https://github.com/neobotix/slam_gmapping.git
sudo apt-get install ros-noetic-ros-controllers=0.21.1-1focal.20230306.100040
sudo apt-get install ros-noetic-gazebo-ros-control=2.9.2-1focal.20230216.004103
sudo apt-get install ros-noetic-navigation=1.17.3-1focal.20230216.021527
sudo apt-get install ros-noetic-joy=1.15.1-1focal.20230215.231441
sudo apt-get install ros-noetic-teleop-twist-keyboard=1.0.0-1focal.20230215.213345
sudo apt-get install ros-noetic-amcl=1.17.3-1focal.20230215.231533
sudo apt-get install ros-noetic-neo-local-planner=1.0.1-1focal.20230216.015503
sudo apt-get install ros-noetic-map-server=1.17.3-1focal.20230215.213811
sudo apt-get install ros-noetic-move-base=1.17.3-1focal.20230216.021300
sudo apt-get install ros-noetic-universal-robots=1.3.1-1focal.20230413.061438
cd ..
catkin_make
. devel/setup.bash
```

# Start the robot
To start the robot, run the following command
```
roslaunch impakt-robot impakt.launch
```
