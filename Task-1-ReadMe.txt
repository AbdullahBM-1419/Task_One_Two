Install & Set VirtualBox + Ubuntu:


1- Download VirtualBox from > https://www.virtualbox.org/wiki/Downloads

2- Choose the download link for your current operating system

3- Install VirtualBox without changing any settings in the installation boxes

4- Download Ubuntu OS iso file from > https://ubuntu.com/download/desktop
*Download version 20.04 only

5- In VirtualBox main interface Choose (New)
then enter the virtual operating system information (name, version...etc)

6- Allocate memory for the virtual operating system

7- For the rest of the boxes/setup windows follow this video
https://www.youtube.com/watch?v=sB_5fqiysi4&ab_channel=TechGumbo
from 5:16 to 6:35 

8- In VirtualBox main interface Choose (Settings)  > (System) > (Processor)
allocate cpu cores for the virtual operating system
do not allocate more than half of the actual processor physical cores

9- In VirtualBox main interface Choose (Settings)  > (System) > (Display)
allocate video memory for the virtual operating system
and select (enable 3d acceleration)

10- In VirtualBox main interface Choose (Settings)  > (System) > (Storage)
and select the virtual operating system iso file

11- Press (OK) to save all settings and adjustments

12- In VirtualBox main interface Choose (Start)
to start/install the virtual operating system session

13- Install Ubuntu with default/standard settings


Please refer to these 2 videos for further clarification...

https://www.youtube.com/watch?v=v1JVqd8M3Yc&ab_channel=ProgrammingKnowledge

https://www.youtube.com/watch?v=sB_5fqiysi4&ab_channel=TechGumbo

--------------------------------------------------------------------------------------------------

Install & Set ROS1: 


1- Go to > http://wiki.ros.org/noetic/Installation/Ubuntu

2- Open the (Terminal) in Ubuntu & enter the following commands/lines
*press enter after each line/command

- sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

*** You will be asked to enter your system password

- sudo apt install curl # if you haven't already installed curl
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

- sudo apt update

- sudo apt install ros-noetic-desktop-full

3- Wait for the download + installation to complete

4- Test the integrity of your installation and files

- source /opt/ros/noetic/setup.bash

Then

- roscore
