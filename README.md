### Turtlebot3-with-Gazebo-Simulation
## `sudo apt update`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/01.PNG)

## `sudo apt upgrade`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/02.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/03.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/04.PNG)

## `wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros_melodic.sh`
## `chmod 755 ./install_ros_melodic.sh`


![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/05.PNG)

## `bash ./install_ros_melodic.sh`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/06.PNG)


![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/07.PNG)


![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/08.PNG)

## `sudo apt-get install ros-melodic-joy ros-melodic-teleop-twist-joy`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/09.PNG)

## `sudo apt-get install ros-melodic-teleop-twist-keyboard ros-melodic-laser-proc`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/11.PNG)

## `sudo apt-get install ros-melodic-rgbd-launch ros-melodic-depthimage-to-laserscan`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/12.PNG)

## `sudo apt-get install  ros-melodic-rosserial-arduino ros-melodic-rosserial-python`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/14.PNG)


## `sudo apt-get install ros-melodic-rosserial-server ros-melodic-rosserial-client`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/15.PNG)

## `sudo apt-get install ros-melodic-rosserial-msgs ros-melodic-amcl ros-melodic-map-server`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/16.PNG)

## `sudo apt-get install ros-melodic-move-base ros-melodic-urdf ros-melodic-xacro`


![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/17.PNG)

## `sudo apt-get install ros-melodic-compressed-image-transport ros-melodic-rqt*`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/18.PNG)


## `sudo apt-get install ros-melodic-gmapping ros-melodic-navigation ros-melodic-interactive-markers`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/19.PNG)

## `sudo apt-get install ros-melodic-dynamixel-sdk`

***

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/20.PNG)


## `sudo apt-get install ros-melodic-turtlebot3-msgs`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/21.PNG)

## `sudo apt-get install ros-melodic-turtlebot3`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/22.PNG)

## `cd ~/catkin_ws/src/`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/23.PNG)

## `git clone -b melodic-devel https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/24.PNG)

## `cd ~/catkin_ws && catkin_make`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/25.PNG)

## `source ~/catkin_ws/devel/setup.bash`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/26.PNG)

## `export TURTLEBOT3_MODEL=burger`


![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/27.PNG)

## `roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/28.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/29.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/30.PNG)
## `export TURTLEBOT3_MODEL=waffle`

![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/31.PNG)
## `roslaunch turtlebot3_gazebo turtlebot3_world.launch`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/33.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/32.PNG)


## `export TURTLEBOT3_MODEL=waffle_pi`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/33.PNG)

## `roslaunch turtlebot3_gazebo turtlebot3_house.launch`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/34.PNG)
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/35.PNG)
## `roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch`
![](https://github.com/cpeibrahem/Robot-Navigation-Using-SLAM-ROS/blob/main/image/36.PNG)
