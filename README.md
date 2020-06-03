# ur10_robotiq_2f_140

Setting up a robot manipulator with a gripper to run proper physics simulations in Gazebo turns out to be quite tricky.
Both the universal robot and the robotiq packages are setup to use position controllers by default without configuring PID values.
This lets gazebo control the joints using the SetPosition method which may lead to weird and undesired behaviors.

This package configures a UR10 universal robot with a Robotiq 2f 140 gripper to use effort controlled positional joints. 

