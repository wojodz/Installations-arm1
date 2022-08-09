# Installations-arm1
Installations arm in ros online
use ROS devolment studio https://www.theconstructsim.com/
go to my rosject - create  new project -select your project and run 
choose (ROS NOITIC)
write this code 
```cd ~/catkin_ws/src```

```git clone https://github.com/smart-methods/arduino_robot_arm.git ```

```cd ~/catkin_ws ```

```rosdep install --from-paths src --ignore-src -r -y```

```sudo apt-get install ros-noetic-moveit```

```sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui```

```sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher```

```sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control```

```catkin_make```

```roslaunch robot_arm_pkg check_motors.launch```
![image](https://i.ibb.co/6bLbJF3/2022-08-08-2.png)
