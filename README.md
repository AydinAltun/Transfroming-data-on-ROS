# Transfroming-data-on-ROS

The sensor data can not be used directly on our robot beacuse coordinate frame are different.For this reason we need to transform by using ros::tf module
Assume that we have a lidar and robot where lidar is placed at the top of the robot. So the base_laser and base_link can be considered.
