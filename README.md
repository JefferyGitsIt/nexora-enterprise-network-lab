# Nexora Technologies - Enterprise Network Lab

A hands-on Cisco Packet Tracer project documenting network design,
configuration, security, and troubleshooting for Nexora Technologies,
a fictional company.

**Project status:** In progress  
**Completed:** Lab 01-02  - Basic LAN Connectivity and Network Design
**Environment:** Cisco Packet Tracer simulation

## Project Overview

This project starts with a small working LAN and gradually expands
into a company network with departmental VLANs, routing, network
services, external connectivity, and access controls.

Each lab documents configuration steps, verification results,
troubleshooting, and lessons learned.

## Learning Objectives

- Build and test Ethernet networks.
- Plan IP addressing and practice subnetting.
- Configure Cisco switches and routers through the CLI.
- Create departmental VLANs and configure trunk links.
- Route traffic between VLANs.
- Configure DHCP and basic DNS services.
- Configure default routes and NAT/PAT.
- Apply access control lists and basic device security.
- Diagnose network connectivity problems.
- Document configurations and test results.

## Current Lab Environment

| Device | Role | IP Address |
|---|---|---|
| NEX-R01 | Cisco 2911 router | 192.168.10.1/24|
| NEX-SW01 | Cisco 2960 Layer 2 switch | 192.168.10.2/24 |
| NEX-PC01 | Workstation | 192.168.10.11/24 |
| NEX-PC02 | Workstation | 192.168.10.12/24 |

Both PCs connect to NEX-SW01 using copper straight-through cables.
Connectivity has been verified in both directions with 0% packet loss.

## Lab Roadmap

The sequence may be adjusted as the project develops.

| Lab | Topic | Status |
|---|---|---|
| 01 | [Basic LAN Connectivity](lab/01-basic-lan-connectivity.md) | Completed |
| 02 | [Network Design and IP Address Planning](lab/02-network-design-and-ip-planning.md) | Completed |
| 03 | [Basic Device Configuration and Secure Management](lab/03-basic-device-configuration-and-secure-management.md) | Completed |
| 04 | Departmental VLANs and Access Ports | Planned |
| 05 | Trunking and Inter-VLAN Routing | Planned |
| 06 | DHCP and Basic DNS Services | Planned |
| 07 | Simulated ISP Connectivity and NAT/PAT | Planned |
| 08 | Access Control Lists and Network Security | Planned |
| 09 | Controlled Network Troubleshooting | Planned |
| 10 | Final Verification and Documentation | Planned |

## Related Projects

- [Active Directory Homelab](https://github.com/JefferyGitsIt/active-directory-homelab)
- [Windows Server Backup and Disaster Recovery](https://github.com/JefferyGitsIt/windows-server-backup-disaster-recovery)

This Packet Tracer simulation is separate from the Hyper-V environment
used in the related projects.
