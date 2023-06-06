## Installations
```bash
sudo apt-get install ros-<ROS_VERSION>-teleop-twist-keyboard
sudo apt-get install ros-<ROS_VERSION>-gmapping
sudo apt-get install ros-<ROS_VERSION>-amcl 
sudo apt-get install ros-<ROS_VERSION>-navigation 
```

## Teleop Control
```bash
roslaunch mecanum_robot world.launch
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

## Mapping 
```bash
roslaunch mecanum_robot world.launch
roslaunch mecanum_robot gmapping.launch
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
rosrun map_server map_saver -f ~/<folder_name>/<map_name>
```

## Autonomous Navigation
```bash
roslaunch mecanum_robot world.launch
roslaunch mecanum_robot navigation.launch
rosrun mecanum_robot move_goal.py
```

## Mechanical Properties
```bash
Wheel Width: 31.5 mm
Wheel Radius: ~ 30 mm
Wheel Base: 235 mm
Track: ~ 270mm
```