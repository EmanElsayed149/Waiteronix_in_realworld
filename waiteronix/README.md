# Waiteronix_description
This package contians the description of waiteronix robot. 

# waiteronix_gazebo
this packege contains the simulation of waiteronix robot .

# waiteronix_navigation
this packege contains the navigation of waiteronix robot .
## Dependencies

* Ununtu 20.04
* ROS Neotic

## Installation(Setup)

follow the instructions below to install the simulation part:
first create your workspace...
```bash
mkdir -p waiteronix_Ws/src
```
then clone the repository...
```bash
git clone https...
```
then excute and source the package
```bash
cd ..
catkin_make
source devel/setup.bash
```

## Run

```bash
roslaunch waiteronix_gazebo gazebo.launch
```

>Note : there is a large block (cube) added on the end of the robot to make robot more balanced

- add your world into "waiteronix_gazebo/worlds
- edit line 13 in "waiteronix_description/launch/gazebo.launch" to add your desired world_name

