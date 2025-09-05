Linux Networking Lab

Overview
This project demonstrates a small Linux networking lab with a central server providing multiple core network services. 
Two client machines connect to the server,one has a static IP and another one is using dhcp. The setup is designed for students, hobbyists, and sysadmins to practice Linux networking concepts.


Central Linux Server
====================
DHCP server for automatic IP address assignment
DNS server for hostname resolution
FTP server for file transfer
Firewall rules for security and traffic control
Optional basic services (e.g., web hosting, SSH, file sharing)

Network Diagram & Client Machines
===============
One client with a static IP address
One client using DHCP-assigned IP address
Both clients can access all services provided by the server but with same restrictions: network diagram below


<img width="600" height="500" alt="Linux Lab" src="https://github.com/user-attachments/assets/e90bdf96-814e-427f-8818-ce206c9e4a7b" />

Requirements
============
One Linux server (can be a VM,  physical machine)
Two client machines (VMs,  or physical machines)
Basic knowledge of Linux command line and networking

Setup Guide
===========
Prepare the server
Install Linux (Ubuntu/Debian/CentOS recommended)
Configure and enable DHCP, DNS, and FTP services
Add firewall rules for traffic control

Prepare the clients
Client 1: Configure a static IP address
Client 2: Use DHCP to obtain an IP address from the server

Test services
Verify DHCP leases
Resolve hostnames via DNS
Upload/download files with FTP
Test firewall rules and basic connectivity

Future Improvements
Integrate monitoring with  Grafana
Bash script for automating some tasks.
