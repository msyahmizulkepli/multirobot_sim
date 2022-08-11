# multirobot_sim
multirobot simulation in ros noetic

*still in progress

### Software

- Ubuntu 20.04
- ROS Noetic

## How to Use
Install turtlebot3 packages
```shell
cd ~/catkin_ws/src/
git clone https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git
git clone https://github.com/ROBOTIS-GIT/turtlebot3.git
git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git
cd ~/catkin_ws && catkin_make
```
clone this repository in ~/catkin_ws/src/ directory

### Multirobot Simulation

```shell
roslaunch multirobot_sim multirobot_gazebo.launch
```
```shell
roslaunch multirobot_sim multirobot_navigation.launch
```
