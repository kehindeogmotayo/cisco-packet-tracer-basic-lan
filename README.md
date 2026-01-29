# Day 1: Basic LAN Network – Cisco Packet Tracer

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

## Author
**Kennhacks**  
Aspiring Network & Cybersecurity Professional And an Ethical Hacker
