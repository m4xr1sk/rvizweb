# RVizWeb - RViz, but on your browser

RVizWeb provides a convenient way of building and launching a web application
with features similar to [RViz](https://github.com/ros-visualization/rviz).

This project makes use of the following:

* @jstnhuang's [ros-rviz](https://github.com/jstnhuang/ros-rviz) web component
* @tork-a's [roswww](https://github.com/tork-a/roswww) web server
* @RobotWebTools's [rosbridge_server](https://github.com/RobotWebTools/rosbridge_suite)
  and [tf2_web_republisher](https://github.com/RobotWebTools/tf2_web_republisher)

## HOWTO

Istruzioni originali qui:

https://github.com/osrf/rvizweb/


> cd ~/catkin_max_ws/src/rvizweb/www

> sudo npm install -g bower

> bower install

> npm install

> roslaunch hello_world hello_world.launch

> http://localhost:8000/rvizweb/index.html
