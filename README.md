# Project 1: Run a Network Scan with Nmap

## Overview
Using Nmap, a network scanning tool, to identify devices and open ports on your network

** Legal disclaimer:**
All exercises and demostration done in this project were conducted on my personal network, for which i possess full ownership and control. 

## Steps 
1. Install Nmap
- On linux: Run sudo apt install nmap
- On windows/Mac: Download nmap from nmap.org

2. Find your IP Range.
- Open a terminal/Command prompt and type Ipconfig (Windows) or ifconfig(Linux/Mac)
- Note your ip address, I will be using 192.168.1.1 for security purpose

3. Scan the network
- Use the command nmap -sP 192.168.1.0/24
 This will list all devices on your network

4. Explore Open Ports
- Use the command: nmap -p 1-1--- (Specific IP address)
  This scans for the open ports on a specific device
  
## Findings
There would be a confirmation that the host is up and other informations like what ports are opened, the type of service they provide and the version of the service running. 
