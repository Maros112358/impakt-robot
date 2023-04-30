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
sudo apt-get install ros-noetic-ros-controllers
sudo apt-get install ros-noetic-gazebo-ros-control
sudo apt-get install ros-noetic-navigation
sudo apt-get install ros-noetic-joy
sudo apt-get install ros-noetic-teleop-twist-keyboard
sudo apt-get install ros-noetic-amcl
sudo apt-get install ros-noetic-neo-local-planner
sudo apt-get install ros-noetic-map-server
sudo apt-get install ros-noetic-move-base
sudo apt-get install ros-noetic-universal-robots
cd ..
catkin_make
. devel/setup.bash
```

# Start the robot
To start the robot, run the following command
```
roslaunch impakt-robot impakt.launch
```
