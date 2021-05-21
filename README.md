mybot_gazebo_tutorial
=====================

Tutorial on creating a ROS-enabled mobile robot in Gazebo 

roalaunch mybot_gazeob mybot_world.launch
rosrun turtlebot_teleop turtlebot_teleop_key /turtlebot_teleop/cmd_vel:=/mybot/cmd_vel

// launch kbot (use this one) 
// in properties.xacro, set param gazebo value=true or false to execute gazebo parts or not
roslaunch mybot_control kbot_gazebo.launch
rosrun turtlebot_teleop turtlebot_teleop_key /turtlebot_teleop/cmd_vel:=/cmd_vel