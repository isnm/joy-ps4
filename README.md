# joy-panda
$sudo apt-get install ros-kinetic-joy

$sudo pip install ds4drv

roslaunch panda_moveit_config demo.launch

roslaunch panda_moveit_config joystick_control.launch

กรณีที่ไม่ใช่ js0 

roslaunch panda_moveit_config joystick_control.launch dev:=/dev/input/jsX
