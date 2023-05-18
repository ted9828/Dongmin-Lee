### 우분투 설치 ROS ###

#setup sources

$ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
 
#setupkey

$ sudo apt install curl 

$ curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

#Installation

$ sudo apt update

$ sudo apt install ros-noetic-desktop-full

$ sudo apt install ros-noetic-slam-gmapping

$ apt search ros-noetic

#zsh

$ echo "source /opt/ros/noetic/setup.zsh" >> ~/.zshrc

$ source ~/.zshrc


#Dependencies for building packages

$ sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential

$ sudo apt install python3-rosdep

#Initialize rosdep

$ sudo rosdep init
	($ rosdep update)
	
	
#################NEXT####################

#managing

$ printenv | grep ROS

$ source /opt/ros/noetic/setup.zsh

#create and build a catkin workspace

$ mkdir -p ~/catkin_ws/src

$ cd ~/catkin_ws/

$ catkin_make

$ source devel/setup.zsh

$ echo $ROS_PACKAGE_PATH/home/youruser/catkin_ws/src:/opt/ros/kinetic/share








































