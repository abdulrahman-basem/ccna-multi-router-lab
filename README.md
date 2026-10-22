
# CCNA Multi-Router VLAN Lab

## Overview
A hands-on Cisco Packet Tracer project built to practice CCNA networking concepts, routing, VLAN configuration, and connectivity troubleshooting.

## Network Topology
- 2 Routers: R0 and R1
- 3 Switches: SW0, SW1, and SW2
- 3 PCs: PC0, PC1, and PC2
- 3 LAN networks connected through two routers

## IP Addressing

| Device | Interface | IP Address |
|---|---|---|
| R0 | G0/0.10 | 192.168.1.1/24 |
| R0 | G0/1.20 | 192.168.2.1/24 |
| R0 | G0/2 | 10.0.0.1/30 |
| R1 | G0/1.30 | 192.168.3.1/24 |
| R1 | G0/2 | 10.0.0.2/30 |
| PC0 | NIC | 192.168.1.10/24 |
| PC1 | NIC | 192.168.2.20/24 |
| PC2 | NIC | 192.168.3.10/24 |

## Concepts Practiced
- VLANs: VLAN 10 (SALES), VLAN 20 (HR), VLAN 30 (IT)
- 802.1Q trunking
- Router-on-a-Stick
- Static routing
- IPv4 addressing and subnetting
- Cisco IOS CLI
- Ping testing and troubleshooting

## Verification
End-to-end connectivity was tested using ICMP ping between PCs on different LANs.

## Project File
`CCNA_Multi_Router_VLAN_Lab_Final.pkt`

## Learning Goals
Practice network configuration, routing between LANs, and troubleshooting in Cisco Packet Tracer.
