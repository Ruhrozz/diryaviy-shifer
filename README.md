# Run:  

roslaunch turtlebot3_gazebo diryaviy_shifer_2020.launch
roslaunch diryaviy_shifer_core autorace_core.launch
rostopic pub -1 /robot/mode std_msgs/UInt8 "data: 1"
roslaunch diryaviy_shifer_core diryaviy_shifer_mission.launch

diryaviy_shifer -> diryaviy_shifer