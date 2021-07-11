# Using-SLAM-map-to-launch-Naviguation-Simulation

*** Steps ***
- Steps are extra easy this time. 
- first, please follow the instruction in previous respositry named SLAM-Map Turtlebot
- after the previous step you should've already created the map and all packages are ready to navigate now.
- use the following commands to launch simulation world:

$ export TURTLEBOT3_MODEL=burger
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch

- run the naviguation node with the following commands: 

$ export TURTLEBOT3_MODEL=burger
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

