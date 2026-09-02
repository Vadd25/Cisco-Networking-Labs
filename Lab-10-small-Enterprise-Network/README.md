# Lab 10 – Small Enterprise Network

## Objective
Design, configure, secure, and verify a small enterprise network using Cisco Packet Tracer.

This project combines multiple networking and security concepts from the previous labs into a single integrated network.

## Network Overview
The network was designed to simulate a small enterprise environment with multiple devices and network segments.

The project demonstrates network segmentation, connectivity, automatic IP addressing, secure device management, traffic filtering, and switch port security.

## Technologies Configured
- VLANs
- 802.1Q trunking
- DHCP
- Access Control Lists (ACLs)
- SSH secure remote management
- Switch port security
- Static/sticky MAC address security
- IP addressing and default gateways
- Network connectivity verification

## VLANs and Trunking
VLANs were used to logically segment the enterprise network.

Trunk links were configured to transport VLAN traffic between network devices.

The VLAN and trunk configurations were verified using Cisco IOS commands.

## DHCP
DHCP was configured to automatically provide network addressing information to client devices.

Router interfaces and client connectivity were verified after configuration.

## Access Control Lists
ACLs were implemented to control traffic within the network.

Testing demonstrated that authorized traffic was permitted while restricted traffic was successfully blocked.

## Port Security
Switch port security was configured to improve Layer 2 security.

Sticky MAC address functionality was used to dynamically learn and secure MAC addresses on switch ports.

Security violation behavior was also tested and verified.

## SSH Secure Management
SSH was configured to provide encrypted remote management access to network devices.

Successful SSH sessions were established to verify secure remote administration.

## Verification and Testing
The network was tested using multiple verification methods, including:

- Ping connectivity tests
- Default gateway testing
- VLAN verification
- Trunk verification
- ACL permit/deny testing
- Port security verification
- SSH remote login testing
- Cisco IOS show commands

## Skills Demonstrated
- Enterprise network design
- Cisco router and switch configuration
- VLAN configuration
- 802.1Q trunking
- DHCP
- Access Control Lists
- Switch port security
- SSH
- Network segmentation
- Network security
- Connectivity testing
- Network troubleshooting
- Cisco IOS CLI
- Cisco Packet Tracer

## Files
- `Lab-10-Small-Enterprise-Network.pkt` – Complete Cisco Packet Tracer enterprise network
- `Screenshots/` – Configuration, security, topology, and verification evidence

## Result
A functional small enterprise network was successfully configured and tested.

The project integrates routing, switching, IP addressing, network segmentation, automated addressing, access control, port security, and secure remote management into a single network environment.