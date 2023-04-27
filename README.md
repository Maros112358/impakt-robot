# IMPAKT-ROBOT
ROS package for robot for mobile robotics on MFF UK

# Install
## Prerequisites
To run the robot, ROS packages for following robots are required:
- **MP-500* https://www.neobotix-robots.com/products/mobile-robots/mobile-robot-mp-500
- **UR-%** https://github.com/ros-industrial/universal_robot

## Clone and install
Run the following commands to install the package
```
roscd <your_ws>
cd src
git clone git@github.com:Maros112358/impakt-robot.git
catkin_make
```

# Start the robot
To start the robot, run the following command
```
roslaunch impakt-robot impakt.launch
```
