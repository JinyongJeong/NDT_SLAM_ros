# NDT_SLAM_ros
NDT based SLAM alogrithm from HDL slam

This code is based on [hdl_graph_slam](https://github.com/koide3/hdl_graph_slam)

# Requirement

- OpenMP
- PCL 1.7
- g2o
- suitesparse

The following ROS packages are required:

- geodesy
- nmea_msgs
- pcl_ros
- ndt_omp

```
# for indigo
sudo apt-get install ros-indigo-geodesy ros-indigo-pcl_ros ros-indigo-nmea-msgs
# for kinetic
sudo apt-get install ros-kinetic-geodesy ros-kinetic-pcl-ros ros-kinetic-nmea-msgs ros-kinetic-libg2o
# for melodic
sudo apt-get install ros-melodic-geodesy ros-melodic-pcl-ros ros-melodic-nmea-msgs ros-melodic-libg2o
```
