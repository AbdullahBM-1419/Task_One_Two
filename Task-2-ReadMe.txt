> The aim of this assignment is to download ros2 on Jetson Nano

> The steps are divided into 4 main sections

> Students from the online path won't install ros2 on Jetson Nano 
because they do not have the part, Instead they will install it on a virtual machine
+ writing & documenting the steps

----------------------------------------------------------------------------

Download & Install Xubuntu:

* These steps are performed in Windows operating system

1- Download Xubuntu image from this link

https://forums.developer.nvidia.com/t/xubuntu-20-04-focal-fossa-l4t-r32-3-1-custom-image-for-the-jetson-nano/121768

2- Extract the file

* You may have to extract the file twice
The first time you will get a file with a (tar) extension 
And the second time you will get a (disk image file)

----------------------------------------------------------------------------

Download & Install Balena:

* This program copies/burns the system image to an SD card

* These steps are performed in Windows operating system

*It is possible to use a usb to SD adapter
if the Jetson Nano does not have a direct SD card input

1- https://www.balena.io/etcher/

2- Open the program and choose your SD card

3- Select the Xubuntu disk image you extracted earlier

4- Press flash
The process will take 20-40 minutes

5- Ignore disk formatting dialogs/requests & close them

6- Eject your SD card after the process is finished

----------------------------------------------------------------------------

Install Xubuntu on Jetson Nano:

1- Plug your SD card or adapter into Jetson Nano

2- Turn it on and start Xubuntu installation process

----------------------------------------------------------------------------

Install ros2 on Jetson Nano:

* After completing the installation of Xubuntu on Jetson Nano
start the last step, which is to install ros2

1- Copy the commands from the following link line by line
and press (Enter) after each one

https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html

* The installation process of ros2 is straightforward
and should work smoothly if you copy the commands correctly

----------------------------------------------------------------------------

For more information or a visual explanation
please refer to the following two videos:

- https://www.youtube.com/watch?v=ULYe70uvK_c&ab_channel=RoverRobotics

- https://www.youtube.com/watch?v=6WZOlkS4D7c&ab_channel=RoboticsinaNutshell

