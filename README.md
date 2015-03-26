#ati_netft_ros_driver

This is the driver for the ATI NET/FT box that is used to connect to ATI F/T sensor. This repo is ported from https://code.ros.org/svn/wg-ros-pkg/stacks/netft/trunk. 
It has been catkinized and updated for ROS Indigo.

Usage
-----

Use the ROS node in the package as a stand-alone node for publishing F/T information. E.g.:
```rosrun netft_rdt_driver netft_node --address 192.168.1.1```

The NET/FT box defaults to 192.168.1.1 as its ip address but this can be changed using the browser-based interface.
