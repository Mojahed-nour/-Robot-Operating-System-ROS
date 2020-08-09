# Robot-Operating-System-ROS
The Robot Operating System ( ROS) is a robust system for for writing robot software..

Seeking to simplify the task of producing complex and stable robot behavior across a wide range of robotic platforms by using set of tools, libraries and conventions offered  in ROS

![images](https://user-images.githubusercontent.com/67114907/89722996-7cacb980-d9f9-11ea-920f-bbc3553ee6f9.jpg)

## Creating ROS Workspace
Setup a catkin workspace in which one or more catkin packages can be built

![1](https://user-images.githubusercontent.com/67114907/89723022-c4cbdc00-d9f9-11ea-88c9-bfb7c9db8bf8.jpg)

## Creating ROS package
Use the catkin_create_pkg script to create a new catkin package

![2](https://user-images.githubusercontent.com/67114907/89723066-3efc6080-d9fa-11ea-8aa6-cdffda2c9262.jpg)


Making new directory 
```
$$ mkdir scripts

$$ cd scripts
```
![3](https://user-images.githubusercontent.com/67114907/89723223-1f663780-d9fc-11ea-8255-39dc56292ebe.jpg)


# creating publisher node
```
$ wget https://raw.github.com/ros/ros_tutorials/kinetic-devel/rospy_tutorials/001_talker_listener/talker.py
$ chmod +x talker.py
```
* [talker.py](https://github.com/Mojahed-nour/-Robot-Operating-System-ROS/blob/master/talker.py) - The python code

![4](https://user-images.githubusercontent.com/67114907/89723131-01e49e00-d9fb-11ea-84f1-f5e04595a5ad.jpg)


# creating Subscriber node
```
$ wget https://raw.github.com/ros/ros_tutorials/kinetic-devel/rospy_tutorials/001_talker_listener/listener.py
$ chmod +x listener.py
```
* [listener.py](https://github.com/Mojahed-nour/-Robot-Operating-System-ROS/blob/master/listener.py) - The python code

![5](https://user-images.githubusercontent.com/67114907/89723146-250f4d80-d9fb-11ea-8a8a-03e2359f7c86.jpg)
