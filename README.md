# installROS
Install Robot Operating System (ROS) on NVIDIA Jetson TK1

This script will install Robot Operating System (ROS) on the NVIDIA Jetson TK1 development kit.

Note: 8-8-16 - Separated out the shell file updateRepositories.sh
so that repositories are updated explicitly. These may or may not be
needed for your application. In particular, updating the restricted repository may cause issues with peripherals such as an Intel RealSense camera

The script is based on the Ubuntu ARM install of ROS Indigo: http://wiki.ros.org/indigo/Installation/UbuntuARM

The ROS wiki (http://wiki.ros.org/NvidiaJetsonTK1) suggests that the Grinch Kernel be installed before install ROS. Instructions for installing the Grinch Kernel are available at: https://devtalk.nvidia.com/default/topic/823132/embedded-systems/-customkernel-the-grinch-21-3-4-for-jetson-tk1-developed/. There is also a JetsonHacks repository which will install the Grinch Kernel for L4T 21.X located at: https://github.com/jetsonhacks/installGrinch.

Maintainer of ARM builds for ROS is http://answers.ros.org/users/1034/ahendrix/

Information gathered from:
http://wiki.ros.org/NvidiaJetsonTK1 and
http://wiki.ros.org/indigo/Installation/UbuntuARM.

When asking questions or looking for help running ROS on NVIDIA Jetson TK1 use the jetson_tk1 tag on ROS answers:
 http://answers.ros.org/questions/scope:all/sort:activity-desc/tags:jetson_tk1/page:1/

