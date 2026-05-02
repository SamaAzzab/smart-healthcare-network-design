<img width="1575" height="918" alt="image" src="https://github.com/user-attachments/assets/09f33d6a-a77a-4935-82f3-375a9d614116" />
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
<img width="1575" height="918" alt="image" src="https://github.com/user-attachments/assets/2f484940-08af-4c21-bb6d-e7311ebf3360" />


### VLAN Configuration
<img width="875" height="242" alt="image" src="https://github.com/user-attachments/assets/e00dcc4b-d4c4-4e0d-82aa-b67e900a8397" />


### Trunk Configuration
<img width="762" height="209" alt="image" src="https://github.com/user-attachments/assets/823c0994-ab05-47e3-8a33-2a90684e40d1" />


### IP Configuration
<img width="887" height="211" alt="image" src="https://github.com/user-attachments/assets/148294e6-6044-44fd-97d5-7bf0aa71d4bc" />


### Connectivity Testing
<img width="892" height="387" alt="image" src="https://github.com/user-attachments/assets/d2c3af3d-0ef6-4b2b-bcba-1ee0df1653b4" />


#### Successful Ping
<img width="822" height="277" alt="image" src="https://github.com/user-attachments/assets/83029c8b-c1a6-4db3-b42c-27de9317e8e8" />



#### Failed Ping (Access Control / Misconfiguration Case)
<img width="890" height="179" alt="image" src="https://github.com/user-attachments/assets/4265aa31-92aa-4a44-9a4e-3ee1f2fedf5a" />



### Running Configuration
<img width="795" height="488" alt="image" src="https://github.com/user-attachments/assets/85d53f13-9722-4010-a10e-86677864e1f5" />



## Key Learning Outcomes
- Designed a secure multi-VLAN network architecture
- Implemented routing and DHCP services
- Applied access control for network security
- Performed troubleshooting using real network commands
- Validated connectivity and isolation between networks
