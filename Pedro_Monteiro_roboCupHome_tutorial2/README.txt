# TIAGO c++ project


To build this project, you will need the following:
**********************************************Exercise 1**************************************************
Robot:Tiago
Packages:ics_gazebo

To compile the project, first change directory to the workspace:

"cd /ros/workspaces/tiago_ws"

And then compile it:

"source devel/setup.bash"

"catkin_make"

To execute the environment write the next command:

"roslaunch ics_gazebo tiago.launch world_suffix:=tutorial2"

**********************************************Exercise 2**************************************************
Robot:Tiago
Packages:ics_gazebo    tiago_vis

To compile, change directory as done before and execute the next command:

"source devel/setup.bash"

"catkin_make"

To execute:

"roslaunch ics_gazebo tiago.launch"

 **********************************************Exercise 3**************************************************
Robot:Tiago
Packages:ics_gazebo    controllers_tutorials

To compile:

"source devel/setup.bash"

"catkin_make"

To execute:

"roslaunch ics_gazebo tiago.launch"
"rosrun controller_manager controller_manager kill head_controller"
"roslaunch controllers_tutorials new_head_controller.launch"