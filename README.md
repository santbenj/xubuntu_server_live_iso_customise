> [!WARNING]
I recommend using this script on a Virtual Machine with at least 20 GIO, just to be safe. Also the script will disable passwords on the system and it will not create the ISO, just add the tool to do it.

> [!TIP]
You can customize and add other programms if you need and after you finish customizing the system just launch this command: eggs produce --clone and don't install calamares.

# System debian only 
Download debian ISO from *** and create a virtual machine with it, you can use VirtualBox or virt-manager. Follow the step to install Debian without any desktop-environment and don't put a root password.

This script is a starting point to create a toolbox system which can be export to an ISO with penguins-eggs, It will install a cinnamon desktop-environment with a lot of utility programs, the objective of this script is to have an all-in-one liveUSB system who can repair,backup or customize your computer if you need it. 

This README contains the steps I do to install and configure the toolbox system, all the support packages (network, bluetooth, audio, printers, etc.), along with all my preferred applications and utilities.
There are two script to launch at different times, one to install all the system and the tools and the other to configure and create the ISO 



command 
sudo apt install git 
git clone https://gitlab.com/santrissebenjamin/debiancinnamoneggs.git
cd debianCinnamonEggs
./Install 


Here is a quick review of the themes and Applications installed:

Themes: 
icon theme = tela-red-dark (vinceliuice)
gtk theme = Qogir-Dark(vinceliuce)
cursor themes=oreo_spark_purple () 

Applications: 
clonezilla -> 
gparted -> 


