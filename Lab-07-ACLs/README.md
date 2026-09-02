# Lab 07 – Access Control Lists (ACLs)

## Objective
Configure and verify an extended Access Control List (ACL) to control traffic between different networks.

## Network Overview
This lab demonstrates how ACLs can be used to control which devices or networks are permitted or denied access to network resources.

## Configuration
An extended ACL was configured on the router to filter traffic based on source and destination IP addresses.

The ACL was applied to the appropriate router interface and direction to enforce the required traffic restrictions.

## Verification
Connectivity tests were performed to confirm that the ACL was working correctly.

- HR traffic was successfully permitted.
- Sales traffic was successfully blocked.
- Ping tests were used to verify the ACL behavior.

## Skills Demonstrated
- Extended Access Control List configuration
- ACL permit and deny statements
- Applying ACLs to router interfaces
- Traffic filtering
- Network connectivity testing
- Troubleshooting ACL configurations
- Cisco IOS CLI
- Cisco Packet Tracer

## Files
- `Lab-07-ACLs.pkt` – Cisco Packet Tracer lab file
- `Screenshots/` – Screenshots showing ACL configuration and verification

## Result
The ACL was successfully configured and tested. Authorized traffic was permitted while restricted traffic was blocked according to the configured access-control policy.