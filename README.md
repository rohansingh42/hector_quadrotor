#CMSC818B_Final_Project

Hector quadrotor environment by TU-Darmstadt

## To build repo
```
mkdir -p hector_ws/src
cd hector_ws/src
https://github.com/tu-darmstadt-ros-pkg/hector_quadrotor.git
cd ..
catkin_make
source devel/setup.bash
```
Make sure you are on branch __kinetic-devel__

## For the project
- Launch files for spawning quad rotors in gazebo are in package _hector_quadrotor_gazebo_

- Theres a package _cmsc818b_hector_ with just launch files for now for lauching 2 drones with camera in the willow garage environment.
```
roslaunch cmsc818b_hector two_quad_demo.launch
```