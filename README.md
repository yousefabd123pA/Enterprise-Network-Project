# Enterprise Network Security Project

## Project Overview
This project simulates a secure multi-branch enterprise network connecting a headquarters in Cairo with a branch office in Alexandria using Cisco Packet Tracer.

The project focuses on network segmentation, inter-branch connectivity, routing, and network security controls.

## Project Objectives
- Design a multi-branch enterprise network.
- Segment departments using VLANs.
- Configure inter-VLAN routing.
- Enable dynamic routing using OSPF.
- Implement a site-to-site IPsec VPN.
- Apply network security controls and secure device management.
- Test connectivity and troubleshoot network issues.

## Technologies and Concepts
- Cisco Packet Tracer
- VLANs and Trunking
- Router-on-a-Stick
- OSPF
- Site-to-Site IPsec VPN
- Access Control Lists (ACLs)
- SSH
- Port Security
- AAA
- Syslog and NTP
- DHCP and DNS
- File Server

## Network Design

### Cairo Headquarters
The headquarters network is designed to support multiple departments using separate VLANs and IP subnets.

| VLAN | Department | Network |
|---|---|---|
| 10 | HR | 192.168.1.0/26 |
| 20 | Department 20 | 192.168.1.64/26 |
| 30 | Department 30 | 192.168.1.128/26 |
| 40 | Department 40 | 192.168.1.192/26 |

### Alexandria Branch
The branch network is designed with separate subnets for departments, management, IT, and servers.

| Department | Network |
|---|---|
| Sales | 192.168.1.0/29 |
| Support | 192.168.1.8/29 |
| Operations | 192.168.1.16/29 |
| Management | 192.168.1.24/29 |
| IT | 192.168.1.32/29 |
| Server Network | 192.168.2.40/30 |

*Note: The IP addressing plan must be verified against the final Packet Tracer topology, particularly the potential overlap between the Cairo and Alexandria networks.*

## Security Features
The project design includes network segmentation, ACL-based traffic restrictions, secure remote device management through SSH, switch port security, and a planned site-to-site VPN.

Implementation and testing status should be confirmed against the final Packet Tracer configuration.

## Testing and Validation
Planned tests include:
- Inter-VLAN connectivity.
- Inter-branch connectivity.
- OSPF neighbor and route verification.
- VPN connectivity.
- ACL rule validation.
- SSH access.
- DHCP and DNS functionality.
- Server reachability.

## Project Structure


Enterprise-Network/
├── README.md
├── 01-Network-Design.md
├── 02-Device-Configurations.md
├── 03-Security-Implementation.md
├── 04-Testing-and-Troubleshooting.md
├── screenshots/
└── Enterprise-Network.pkt


## Author
Yousef Abdelkader Kamel
