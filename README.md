# Enterprise Multi-Area OSPF Network

## Project Overview
This project demonstrates an enterprise network using **Open Shortest Path First (OSPF)** dynamic routing with multiple areas in Cisco Packet Tracer.

The network connects a core router and two branch routers using OSPF Area 0 and Area 1, enabling communication between different LAN networks.

## Objectives
- Configure multi-area OSPF routing.
- Understand OSPF backbone Area 0.
- Establish OSPF neighbor relationships.
- Advertise LAN networks dynamically.
- Verify routing table entries.
- Test communication between different network segments.

## Network Topology

**Devices used:**
- 3 × Cisco 2911 Routers
- 3 × Cisco 2960 Switches
- 6 × PCs
- Cisco Packet Tracer

## IP Addressing

| Network | IP Address |
|---|---|
| R1–R2 Serial | 10.0.12.0/30 |
| R1–R3 Serial | 10.0.13.0/30 |
| Area 0 LAN | 192.168.10.0/24 |
| Area 1 LAN | 192.168.20.0/24 |

## OSPF Area Design

- **Area 0:** Backbone network connecting R1 and R2.
- **Area 1:** Branch network connecting R1 and R3.
- **R1:** Area Border Router (ABR).

## Technologies Used
- Cisco Packet Tracer
- Cisco IOS CLI
- OSPF Dynamic Routing
- IPv4 Addressing
- Subnetting
- Serial WAN Connections

## Verification Commands

```cisco
show ip interface brief
show ip ospf neighbor
show ip route
show ip route ospf
ping 192.168.20.10
```

## Learning Outcomes
- Practical understanding of multi-area OSPF.
- Router configuration and troubleshooting.
- Dynamic route advertisement.
- Inter-area communication.
- Enterprise network design.

## Author
Andrews GnanaSelvin D

GitHub: https://github.com/Andrewsdavid2005
LinkedIn: https://www.linkedin.com/in/andrews-gnana-selvin-d

## Project Status
Implementation and connectivity testing should be confirmed before marking the project complete.
