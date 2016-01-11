The pizza cutting/rearrangement stuff. 

Will contain code relevant to making the robot cut regions out of a pizza selected by toppings, and rearranging the slices into some given sets.

## Installation from source using ```catkin``` and ```rosdep```
### Getting and compiling the source code
Assumptions: ROS Indigo on Ubuntu 14.04, correctly set up ```catkin``` workspace at ```~/catkin_ws/src```.
* ```rosdep update```
* ```cd ~/catkin_ws/src```
* ```wstool init .``` (optional, if you already did this before)
* ```wstool merge https://raw.githubusercontent.com/code-iai/pizza_ninja/master/rosinstall/base.rosinstall```
* ```wstool update```
* ```rosdep install --ignore-src --from-paths .```
* ```cd ~/catkin_ws```
* ```catkin_make```

### Running the unit-tests to see that everything went fine
The following tests should compile and run without errors:
* ```cd ~/catkin_ws```
* ```catkin_make run_tests_giskard```
* ```catkin_make run_tests_iai_naive_kinematics_sim```
