RoboND-Localization-Project
Udacity's Robotics Nanodegree 'Where am I?' Project

udacity bot
In order to run the udacity bot benchmark model use the following commands:

first terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch udacity_bot udacity_world.launch

Second terminal:
$cd /home/workspace/catkin_ws/
$source devel/setup.bash
$roslaunch udacity_bot amcl.launch

last terminal: 
$cd /home/workspace/catkin_ws/
$source devel/setup.bash
$rosrun udacity_bot navigation_goal

my bot
In order to run the my bot personal model use:

first terminal:
$cd /home/workspace/catkin_ws/
$catkin_make
$source devel/setup.bash
$roslaunch udacity_bot my_bot_udacity_world.launch

Second terminal:
$cd /home/workspace/catkin_ws/
$source devel/setup.bash
$roslaunch udacity_bot my_bot_amcl.launch

last terminal: 
$cd /home/workspace/catkin_ws/
$source devel/setup.bash
$rosrun udacity_bot navigation_goal

