## Installations
```bash
sudo apt-get install ros-<ROS_VERSION>-teleop-twist-keyboard 
```

## Teleop Control
```bash
roslaunch mecanum_robot world.launch
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

## Autonomous Navigation
```bash
roslaunch mecanum_robot world.launch
roslaunch mecanum_robot navigation.launch
```