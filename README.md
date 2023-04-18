# Phase1
1) For preparing the system first follow the TurtleBot3 - ROBOTIS e-Manual.<br/>
https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/#gazebo-simulation<br/>

```sh
Download the following
git clone https://github.com/ROBOTIS-GIT/turtlebot3
git clone https://github.com/ROBOTIS-GIT/open_manipulator 
```

- launch Turtlebot3
```sh
    export TURTLEBOT3_MODEL=waffle_pi_for_open_manipulator
    roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```
-run the code
```sh
    python3 Ball_and_Goal_follower.py
```  
