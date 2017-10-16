# microtrac_description
Meshes and URDF for [Open Source Ecology's MicroTrac](http://opensourceecology.org/wiki/Tractor_Construction_Set_2017)

To Test the URDF:

    $ mkdir -p ~/ros_ws/src
    $ cd ~/ros_ws/src
    $ git clone https://github.com/ros-agriculture/microtrac.git
    $ cd ~/ros_ws
    $ source /opt/ros/kinetic/setup.sh
    $ catkin_make
    $ source devel/setup.sh
    $ roslaunch microtrac_description test_microtrac_urdf.launch

![MicroTrac RViz](config/microtrac_rviz.png?raw=true "MicroTrac in RViz")
