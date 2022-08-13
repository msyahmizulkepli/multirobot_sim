# multirobot_sim
multirobot simulation using multiple turtlebot3 in ros noetic


### Software

- Ubuntu 20.04
- ROS Noetic

## How to Use
Install turtlebot3 packages
```shell
sudo apt install ros-noetic-turtlebot3
sudo apt install ros-noetic-turtlebot3-msgs
sudo apt install ros-noetic-turtlebot3-simulations
```
clone this repository in ~/catkin_ws/src/ directory
```shell
cd ~/catkin_ws/src
git clone https://github.com/msyahmizulkepli/multirobot_sim.git
```

### Multirobot Simulation

```shell
roslaunch multirobot_sim gazebo.launch
```
```shell
roslaunch multirobot_sim navigation.launch
```
