# Smart Healthcare Network Design

## Overview
This project presents a secure and scalable network design for a healthcare clinic using Cisco Packet Tracer. The network is segmented using VLANs to isolate departments and protect sensitive medical data while maintaining controlled communication.

## Network Design
The system includes multiple departments:
- Reception
- Billing
- Medical Staff
- IT Support
- Guest Network

Each department is assigned a dedicated VLAN and subnet to ensure security and efficient traffic management.

## Features
- VLAN segmentation (Reception, Billing, Medical, IT, Guest)
- Inter-VLAN routing using router-on-a-stick
- DHCP configuration for dynamic IP assignment
- Trunking between switches and routers
- Access Control Lists (ACLs) for security
- Firewall-style traffic restrictions
- Connectivity testing using ping and routing tables

## Technologies Used
- Cisco Packet Tracer
- VLANs
- Subnetting
- DHCP
- ACLs
- Routing (Static / RIP)
- Network troubleshooting tools

## Screenshots

### Network Topology
![Topology](screenshots/topology.png)

### VLAN Configuration
![VLAN](screenshots/vlan-config.png)

### Trunk Configuration
![Trunk](screenshots/trunk-config.png)

### IP Configuration
![IP1](screenshots/ipconfig-1.png)
![IP2](screenshots/ipconfig-2.png)

### Routing Table
![Routing](screenshots/routing-table.png)

### Connectivity Testing

#### Successful Ping
![Ping Success](screenshots/ping-success.png)

#### Failed Ping (Access Control / Misconfiguration Case)
![Ping Fail](screenshots/ping-failure.png)

### Running Configuration
![Config](screenshots/running-config.png)

## Key Learning Outcomes
- Designed a secure multi-VLAN network architecture
- Implemented routing and DHCP services
- Applied access control for network security
- Performed troubleshooting using real network commands
- Validated connectivity and isolation between networks
