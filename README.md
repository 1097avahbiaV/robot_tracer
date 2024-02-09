# robot_tracer
This is a final project for the course CSCI 5551, it is merely for public display, and has already been presented and graded. The project is subject to the rules and regulations provided by the University of Minnesota and the course academic standards. Please feel free to use and credit this project as a reference.

### project description
This is a simplistic take on developing a robot that is able to follow a given path drawn on a digital canvas provided to a user. Hypothetically, the user should be able to draw complex and convoluted paths, and irrespective of what is provided, the robot shall chart out the shortest path of the complex path and move to a marked destination, from a marked starting point.

the path generation is using a combination of defining a closed space area and appplying the RRT algorothm, in an effort to generate optimized paths quickly. There are far more efficient approaches to this that I will take up and develop further as an update to this project.

Albeit the simple application, there is not enough open source exposure from what I had searched for at the time. Hence I took a simple taskk of developing a simulation to reflect this purpose.


### contributions

My key contributions to this project revolved around developing the simulated world you run this robot in, building the robot model on Gazebo, establishing the ROS environemnt and package, and writing the movement script, integrating the output from the digital canvas to a defined movement path in ROS. I am found <a href="https://www.linkedin.com/in/vaibhava-krishna-devulapalli">here</a>


The contributors to this project are <a href="https://www.linkedin.com/in/rushikesh-zende-43077a131">Rushikesh Zende</a> and Rahul Autade.

### running of the project

You can take this repository and download it onto your system.

You reqiore a working setup of a ROS Environment on your system, if you do not have one, please refer to the installatin of ROS 1 onto your system.
1. launching ROS master using the command `roscore`
2. please move into your ros workspace
3. use `catkin_make` and build all the repositories
4. source the setup file present within your devel folder of the workspace
5. launch the world file using the command `roslaunch ros_rspository name irs_project.launch`
6. open a new terminal and run `python3 trial.py`


### credits

I would like to credit
1. EYantra, the robotics competition hoted by IIT Bombay, and my experience with working on the EYantra in finding open source 3D materials to help assemble my simulated world quickly.
2. The ROS Wiki
