# Dashboard for ROS-based System

A simple software for monitoring the ROS system on robot via web page on different computer. This software is mainly used for Robocup @work lab

# Contributors:
1. Lokesh Veeramacheneni
2. Anargh Viswanath
3. Zuha Karim

# Required Softwares:
This sections describes the softwares used along with the installation procedures
1. ROS Kinetic
Setup computer to receive software from ros packages
```bash
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
Setup keys for ROS
```bash
sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
```
Install ROS package
```bash
sudo apt-get install ros-kinetic-desktop-full
```
2. Cockpit:
```bash
sudo apt-get -y install cockpit
```
Clone the github and open terminal and run
```bash
bash install.sh
```
# Features of project:
1. Easy visualization of ROS nodes.
2. Common platform for visualizing the ROS statistics.
3. Easy start and stop of ROS nodes (If possible).

# Coding Standards to be followed:
1. Python - PEP8
2. Javascript - Google JavaScript Style Guide

# How to Install?
Step-01:
Clone the Repository to the destination folder using 
```bash
git clone git@github.com:lokeshveeramacheneni/Software-Development-Project.git
```
Step-02:
Open Dashboard folder and then run the below command from terminal
```bash
bash install.sh
```

# Credits:
1. Prof. Dr. Nico Hochgeschwender
2. M.Sc Deebul Nair 
3. Minh Nguyen
4. Ulliyada Arun Devaiah
5. Venkata Santosh Muthireddy
# License:
Mozilla Public License 2.0
