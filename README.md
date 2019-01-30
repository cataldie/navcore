# navcore

bashrc config

source /opt/ros/melodic/setup.bash
source /home/user/catkin_ws/devel/setup.bash
export ROS_PACKAGE_PATH=/home/user/catkin_ws/src:$ROS_PACKAGE_PATH
export GAZEBO_MODEL_PATH=/home/user/catkin_ws/src/



roslaunch navcore_gazebo navcore.launch
