# NETWORKWALKS-rashmi-B083-CYBERSECURITY-LAB-SETUP-WEEK-1
cybersecurity lab setup ,Kali Linux setup ,NAT network and IP setup in virtual machine
This project is part of the NetworkWalks Cybersecurity Week 1 practical assignment.

The objective is to build a cybersecurity testing lab environment using VirtualBox and Kali Linux. Kali Linux is configured as the attacking/testing machine with a dedicated NAT Network, static IP address, Internet access, clipboard sharing, drag-and-drop support, and a shared folder.

 Lab Objectives

The lab environment was configured with the following requirements:

Use VirtualBox as the base virtualization platform.
Install and configure Kali Linux as the attacking/testing machine.
Create a NAT Network using the 10.0.0.0/24 subnet.
Configure Kali Linux with the IP address 10.0.0.2/24.
Enable full Internet access from Kali Linux.
Enable clipboard sharing between the host and Kali Linux.
Enable file drag-and-drop between the host and Kali Linux.
Configure a shared /downloads folder from the host machine.

🛠️ Tools Used
Tool	Purpose
VirtualBox	Virtualization platform
Kali Linux	Attacking/testing machine
NAT Network	Network connectivity
GitHub	Project documentation
Linux Terminal	Configuration and testing

VirtualBox Setup

VirtualBox was used as the base virtualization platform for the cybersecurity lab.

After installing VirtualBox, a virtual machine was created for Kali Linux.

Configuration
Virtualization Platform: VirtualBox
Guest OS: Kali Linux
Network Mode: NAT Network





 Kali Linux Setup

Kali Linux was installed as the attacking/testing machine for the cybersecurity lab.

The Kali Linux virtual machine was configured with the required resources and network settings.






 NAT Network Configuration

A NAT Network was created in VirtualBox using the required subnet:

10.0.0.0/24

This provides the Kali Linux virtual machine with network connectivity while allowing Internet access through the host system.

Network Configuration
Network Type: NAT Network
Network: 10.0.0.0/24




Kali Linux IP Address

Kali Linux was configured with the following IP address:

IP Address: 10.0.0.2
Subnet Mask: 255.255.255.0
CIDR: /24

The configured address was verified from the Kali Linux terminal.

Example command:

ip addr





 Internet Connectivity

After configuring the NAT Network, Internet connectivity from Kali Linux was tested.

The connection was verified using network testing commands such as:

ping -c 4 google.com

Successful replies confirmed that Kali Linux had Internet access.



Lab Verification

After completing the configuration, the following requirements were verified:

VirtualBox installed and configured

Kali Linux installed

NAT Network configured

Network subnet configured as 10.0.0.0/24

Kali Linux IP configured as 10.0.0.2/24

Internet connectivity verified


 
Troubleshooting
Problem

During the lab setup, network connectivity and virtual machine configuration may require troubleshooting if Kali Linux does not receive the expected IP address or cannot access the Internet.

Solution

I checked the VirtualBox NAT Network configuration, verified the Kali Linux network interface, and tested the connection using Linux networking commands.

I also verified the VirtualBox settings for clipboard sharing, drag-and-drop, and shared folders.

 What I Learned

Through this project, I learned:

How to create and configure a virtual cybersecurity lab.
How to install and configure Kali Linux in VirtualBox.
How NAT Networks work in VirtualBox.
How to configure and verify an IPv4 address.
How to test Internet connectivity from Kali Linux.
How to configure clipboard sharing and drag-and-drop.
How to configure shared folders between a host and virtual machine.
How to document cybersecurity lab work using GitHub.



I did face some issues but learnt in the process to resolve them great start for the learning....
