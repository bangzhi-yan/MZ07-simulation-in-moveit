# MZ07-simulation-in-moveit
MZ07 model in moveit simulator  
run urdf:  
copy mz07 urdf folder into ~/catkin_ws/src  
under ~/catkin_ws  
catkin build  
source ~/devel/setup.bash  
roslaunch mz07 display.launch  
run moveit demo:  
copy mz07_moveit_config folder into ~/catkin_ws/src  
catkin build  
source ~/devel/setup.bash  
roslaunch mz07_moveit_config demo.launch
