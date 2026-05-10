# Multi-Subnet-IP-Routing
![Network Topology](topology.png)
Advanced Cisco Packet Tracer lab demonstrating inter-VLAN style routing across four distinct subnets using a centralized 2811 router gateway
# Multi-Subnet Network Infrastructure & IP Routing

This repository contains a Cisco Packet Tracer project focused on segmenting a network into four distinct subnets, all managed by a single central router serving as the default gateway.

### Key Features:
* **Subnet Segmentation:** Four independent networks (198.168.1.x, 2.x, 3.x, 4.x) to improve traffic management and security.
* **Centralized Routing:** Implementation of a Cisco 2811 router as the core gateway for inter-subnet communication.
* **Network Topology:** Star-bus hybrid featuring 4 switches (2960-24TT) and a central distribution node.
* **Dedicated Server Segment:** One subnet is dedicated to server resources, simulating a small data center or management VLAN.

### IP Address Schema:
* **Network 1:** 198.168.1.1 (Server Subnet)
* **Network 2:** 198.168.2.1 (Workstation Group A)
* **Network 3:** 198.168.3.1 (Workstation Group B)
* **Network 4:** 198.168.4.1 (Workstation Group C)

### Hardware Used:
* 1x Cisco 2811 Router
* 4x Cisco 2960-24TT Switches
* Multiple End Devices (PCs and Generic Server)
