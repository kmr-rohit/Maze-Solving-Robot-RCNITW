# maze-solving-robo
maze solver
## how to compile it??
1. clone the repository
2. Delete the build and devel folder from catkin_ws
3. do the same for simulation_ws
4. Run ```catkin_make``` in both workspace.

### our project is ready to deploy!!
## simulation_ws
### how to run it 
1. ```roslaunch gazebo_ros empty_world.launch```
2. ```roslaunch m2wr_description spawn.launch```
3. the model gets spawned.

## catkin_ws
bug2.launch -> moves the bot from one point to another avoiding the obstaclesby traveling in a line and moving around the object
              ```roslaunch motion_plan bug2.launch```
obstacle_avoidance.py -> move straight through obstacles
              ```rosrun motion_plan obstacle_avoidance.py```
go_to_point.py -> move from one point to another
              ```rosrun motion_plan go_to_point.py```
 


