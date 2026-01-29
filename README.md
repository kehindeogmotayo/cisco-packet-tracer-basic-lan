# Basic LAN Network – Cisco Packet Tracer

## Overview
This project demonstrates a basic Local Area Network (LAN) built using Cisco Packet Tracer.  
The objective is to understand how devices communicate within the same network using switches, MAC addresses, and ICMP (ping).

## Network Topology
- 1 Switch (Cisco 2960)
- 4 End Devices (PCs)
- Static IP addressing
- Same subnet

## Technologies & Concepts
- Cisco Packet Tracer
- LAN architecture
- Switching
- MAC Addressing
- ICMP (Ping)
- OSI Model (Layers 1–3)

## What Was Implemented
- Connected multiple PCs to a switch
- Assigned static IP addresses
- Verified connectivity using ICMP ping
- Observed packet flow in Simulation Mode

## Packet Flow Explanation
When a PC sends a ping:
1. ICMP Echo Request is generated
2. Encapsulated into an IP packet
3. Encapsulated into an Ethernet frame using MAC addresses
4. Switch forwards frame based on MAC address table
5. Destination PC replies with ICMP Echo Reply

## Files
- `Basic-LAN-ICMP-Packet-Flow.pkt` – Packet Tracer project file

## How to Run
1. Open Cisco Packet Tracer
2. Load the `.pkt` file
3. Switch to Simulation Mode
4. Use the ping command to observe packet flow

## Learning Outcome
This project strengthens foundational networking concepts such as LAN communication, packet encapsulation, and switch-based forwarding.


## Day 2 – Routing & Default Gateway

### Objective
To understand how devices communicate across different networks using a router and default gateway.

### Concepts Covered
- Routing (OSI Layer 3)
- Default Gateway
- ARP Resolution
- Inter-network ICMP communication

### Implementation
- Configured a router with two interfaces
- Assigned IP addresses to separate subnets
- Configured default gateways on end devices
- Verified connectivity using ping
- Observed packet flow in simulation mode

### Key Insight
Hosts decide where to send traffic.  
If the destination is outside the local subnet, packets are forwarded to the default gateway for routing.


## Author
**Kennhacks**  
## Ogidan Kehinde Daniel
Aspiring Network & Cybersecurity Professional And an Ethical Hacker
