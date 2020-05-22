# kinova-control

How to use the Moveit Environment file

- Put traj_object.scene file in the following directory:

      kinova-ros/kinova_moveit/robot_configs/j2s7s300_moveit_config/config

- Put the j2s7s300_virtual_robot_demo_traj.launch file in the following directory:

      kinova-ros/kinova_moveit/robot_configs/j2s7s300_moveit_config/launch
   

- Launch the virtual robot using the new launch file:

      roslaunch j2s7s300_moveit_config j2s7s300_virtual_robot_demo_traj.launch
