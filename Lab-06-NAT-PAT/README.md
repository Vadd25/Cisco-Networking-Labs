# Lab 06 – NAT/PAT

## Overview
This lab demonstrates the configuration of Network Address Translation (NAT) and Port Address Translation (PAT) using Cisco Packet Tracer.

The goal was to allow devices on a private network to communicate through an outside network while translating private IP addresses using PAT.

## Network Details

- Private network: 192.168.10.0/24
- NAT inside interface: GigabitEthernet0/0
- NAT outside interface: GigabitEthernet0/1
- Outside interface IP: 203.0.113.1/30
- PAT configured using interface overload

## Configuration

The inside and outside NAT interfaces were identified:

- GigabitEthernet0/0 – NAT inside
- GigabitEthernet0/1 – NAT outside

An access control list was used to identify the private addresses that should be translated.

PAT was then configured using the outside interface with the `overload` option.

## Verification

The configuration was tested using:

- Ping connectivity tests
- `show ip nat translations`
- `show ip nat statistics`

Successful connectivity was achieved with 0% packet loss during testing.

## Skills Demonstrated

- IPv4 addressing
- NAT configuration
- PAT (NAT overload)
- Inside and outside NAT interfaces
- Access control lists for NAT
- Default routing
- Connectivity testing
- NAT verification and troubleshooting

## Screenshots

The Screenshots folder contains:

- Network topology
- NAT/PAT configuration
- NAT statistics
- Successful connectivity test

## Files

- `Lab-06-NAT-PAT.pkt` – Cisco Packet Tracer lab file
- `Screenshots/` – Configuration and verification evidence

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI