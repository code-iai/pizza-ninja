The pizza cutting/rearrangement stuff. 

Will contain code relevant to making the robot cut regions out of a pizza selected by toppings, and rearranging the slices into some given sets.

## Installation
* ```rosdep update```
* ```cd ~/catkin_ws/src```
* ```wstool merge https://raw.githubusercontent.com/code-iai/pizza_ninja/master/rosinstall/base.rosinstall```
* ```wstool update```
* ```rosdep install --ignore-src --from-paths pizza-ninja iai_naive_kinematics_sim```
* ```cd ~/catkin_ws```
* ```catkin_make```
