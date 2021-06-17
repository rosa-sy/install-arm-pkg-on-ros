# install-arm-pkg-on-ros

---
installing arm pkg on Ros,as a first task where I take my summer training in  ( smart methods).
---
first of all download VM virtualBoxManager ...
then download ubuntu(18.04) ..
and  Ros(melodic) by copying some  order
![image](https://user-images.githubusercontent.com/85003576/122482971-4016fa80-cfda-11eb-9b06-ffa5f0fefb5c.png)
![image](https://user-images.githubusercontent.com/85003576/122482929-2bd2fd80-cfda-11eb-82c8-78ce206c2c3e.png)
![image](https://user-images.githubusercontent.com/85003576/122482999-4dcc8000-cfda-11eb-8d1c-14ce75c5be5f.png)
##  upload arm package 

install catkin then  name the workspace that to install the package of arm in it .
go to source by this command (cd ¬/catkin_ws/src).

in source folder (git clone https://github.com/smart-methods/arduino_robot_arm.git)

###  installed all these packages:
$ sudo apt-get install ros-melodic-moveit

$ sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui

$ sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher

$ sudo apt-get install ros-melodic-ros-controllers ros-melodic-ros-control

### video

https://user-images.githubusercontent.com/85003576/122480047-cb8d8d00-cfd4-11eb-9ec9-755ec8e078d1.mp4

when Rviz work we can control the movment of arm by joint_state_publisher
