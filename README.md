# Enterprise Multi-Branch Network Design

A simulated enterprise network infrastructure developed using Cisco Packet Tracer, connecting Cairo Headquarters with the Alexandria Branch.

## Architecture

The network follows a multi-branch architecture designed to provide departmental segmentation, controlled communication, centralized services, and secure connectivity between geographically separated sites.

## Network Implementation

| Component | Implementation |
|---|---|
| Network Segmentation | VLANs, IEEE 802.1Q |
| Inter-VLAN Communication | Router-on-a-Stick |
| Dynamic Routing | OSPF |
| WAN Connectivity | Site-to-Site IPsec VPN |
| IP Address Management | IPv4 Subnetting |
| Network Services | DHCP, DNS |
| Access Control | ACLs |
| Device Management | SSH |
| Layer 2 Security | Port Security |

## Network Topology

The infrastructure consists of two interconnected sites:

- **Cairo Headquarters:** Department-based VLANs and centralized network infrastructure.
- **Alexandria Branch:** Segmented departmental networks and server infrastructure.

## Security Considerations

- Departmental network isolation through VLAN segmentation.
- Traffic filtering using Access Control Lists.
- Secure administrative access through SSH.
- Switch port access restrictions.
- Encrypted inter-branch communication using IPsec VPN.

## Repository Structure

├── Packet-Tracer/
├── Configurations/
├── Documentation/
├── Screenshots/
└── README.md

## Author

Yousef Abdelkader Kamel

Cybersecurity & Network Engineering Student

[GitHub](https://github.com/yousefabd123pA)
