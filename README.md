# Phase1
1) Ubuntu version 20.4 focal fosa - ROS neotic
2) Prepare the system first from TurtleBot3 - ROBOTIS e-Manual.<br/>
https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/#gazebo-simulation<br/>

3)
```sh
Download the following for the world and models
git clone https://github.com/ROBOTIS-GIT/turtlebot3
git clone https://github.com/ROBOTIS-GIT/open_manipulator 
```

4)launch Turtlebot3
```sh
    export TURTLEBOT3_MODEL=waffle_pi_for_open_manipulator
    roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```
5)run the code
```sh
    python3 Ball_and_Goal_follower.py
```  
