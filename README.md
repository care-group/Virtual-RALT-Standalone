# Virtual RALT Standalone

This is a standalone world simulating the [Robotic Assisted Living Testbed (RALT)](https://ralt.hw.ac.uk/). Note that this repository provides the environment model *only*.

Tested on Ubuntu 16.04, using ROS Kinetic and Gazebo 7.16.

![GitHub Logo](/doc/virtual_ralt.png)

# Installation

Clone this repository into your workspace:

```
roscd; cd ..; cd src
git clone https://github.com/care-group/Virtual-RALT-Standalone.git
catkin_make
roscd; cd..
source devel/setup.bash
```

You can then launch the environment as follows:

```
roslaunch virtual_ralt_standalone virtual_ralt_standalone.launch
```