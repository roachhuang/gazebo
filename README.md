mybot_gazebo_tutorial
=====================

Tutorial on creating a ROS-enabled mobile robot in Gazebo 

roalaunch mybot_gazeob mybot_world.launch
rosrun turtlebot_teleop turtlebot_teleop_key /turtlebot_teleop/cmd_vel:=/mybot/cmd_vel

// launch kbot
roslaunch mybot_control kbot_gazebo.launch
rosrun turtlebot_teleop turtlebot_teleop_key /turtlebot_teleop/cmd_vel:=/cmd_vel