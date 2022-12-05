# Run:  

roslaunch turtlebot3_gazebo turtlebot3_autorace_2020.launch
roslaunch turtlebot3_autorace_core autorace_core.launch
rostopic pub -1 /robot/mode std_msgs/UInt8 "data: 1"
roslaunch turtlebot3_autorace_core turtlebot3_autorace_mission.launch