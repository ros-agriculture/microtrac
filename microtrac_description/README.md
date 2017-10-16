# microtractor_description
Meshes and URDF for [Open Source Ecology's Micro Tractor](http://opensourceecology.org/wiki/Tractor_Construction_Set_2017)

To Test the URDF:

    $ mkdir -p ~/ros_ws/src
    $ cd ~/ros_ws/src
    $ git clone https://github.com/ros-agriculture/microtractor.git
    $ cd ~/ros_ws
    $ source /opt/ros/kinetic/setup.sh
    $ catkin_make
    $ source devel/setup.sh
    $ roslaunch microtractor_description test_microtractor_urdf.launch

![Micro Tractor RViz](config/microtractor_rviz.png?raw=true "Micro Tractor in RViz")
