# easy_panda_moveit_config

This is an add-on for the upstream MoveIt! config for the Franka Emika Panda robot.

It replaces the MoveIt! RViz tutorial buttons with the planning interface.

### Play around with the robot in RViz

<img src="docs/img/demo.png" width="345"/>

```bash 
roslaunch easy_panda_moveit_config demo.launch
```

<!-- TODO

### Play around with the robot in RViz and Gazebo

```bash 
roslaunch easy_panda_moveit_config moveit_planning_execution.launch sim:=true 
```

### Move the real robot

```bash 
roslaunch easy_panda_moveit_config moveit_planning_execution.launch robot_ip:=<YOUR ROBOT IP>
```

-->