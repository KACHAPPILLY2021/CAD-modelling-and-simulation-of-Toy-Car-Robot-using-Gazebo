Instructions:

####################################

To build the package:

1. Copy the'car_pkg' folder in the src folder of the catkin workspace.
2. Open the terminal in catkin workspace foler and build the package using 'catkin_make'.
3. Source the package by enter command 'source devel/setup.bash'

####################################

To run the teleop demo
Open 2 different terminals.

In first terminal, type following commands
1. source devel/setup.bash
2. roslaunch car_pkg template_launch.launch

In second terminal, type following commands
1. source devel/setup.bash
2. rosrun car_pkg teleop_template.py

####################################

To run the publisher subscriber demo
Open 3 different terminals.

In first terminal, type following commands
1. source devel/setup.bash
2. roslaunch car_pkg template_launch.launch

In second terminal, type following commands
1. source devel/setup.bash
2. rosrun car_pkg publisher_node.py

In third terminal, type following commands
1. source devel/setup.bash
2. rosrun car_pkg subscriber_node.py

####################################

