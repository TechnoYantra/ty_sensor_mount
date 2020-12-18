# TechnoYantra Sensor Mount

This package contains the files for ROS integration of Technoyantra Sensor Mount (ty_sensor_mount) which is a custom designed & 3D Printed mount which holds various sensors together like

 * RPLiDAR A1 360° Laser Range Scanner
 * Intel® RealSense™ Depth Camera D435 and
 * Intel® RealSense™ Tracking Camera T265

This sensor mount can be placed on your robot to get simultaneous data from all of your sensors.

This package currently supports and is been tested on ROS Kinetic Kame & ROS Melodic Morenia running on Ubuntu 16.04 & Ubuntu 18.04 respectively.

## Dependencies

### Git

Firstly, make sure you have Git installed on your PC. If not, then you can install git using

```
sudo apt-get install git
```

### Realsense_ros_gazebo

The ty_sensor_mount package uses the Realsense Camera descriptions from the realsense_ros_gazebo package made by Marton Juhasz. We have forked Marton's repo on to avoid any type of conflict in dependencies. To install the forked package,

Simply change your terminal directory to your src folder of your workspace

```
cd catkin_ws/src
```

where *catkin_ws* should be replaced by the name of your workspace and then clone the forked package by

```
git clone https://github.com/TechnoYantra/realsense_ros_gazebo
```

## Installation

To install the ty_sensor_mount package, stay in the src folder of your Catkin Workspace like before and then run the following command

```
git clone https://github.com/TechnoYantra/ty_sensor_mount
```

And you are done! You can now use the ty_sensor_mount package!!!

## How to use
