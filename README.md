# Campus Network Design & Implementation

A modern campus network designed and implemented in **Cisco Packet Tracer** (CNDC lab project).

## Overview
A hierarchical star topology that connects multiple departments (IT, Computer Science, Administration, etc.) to a central server room. The network uses DHCP for automatic IP assignment and EIGRP for dynamic routing.

## Key Features
- **Routing:** EIGRP (Autonomous System 1) across subnets 192.168.1.0 to 192.168.6.0
- **DHCP:** Central DHCP server (192.168.1.2) with IP helper addresses on router interfaces
- **Services:** DNS (192.168.1.3), HTTP web server (192.168.1.4) and FTP server with authentication (192.168.1.5)
- **Hardware:** Cisco 2621XM routers and Cisco 2960 switches

## Files
- `Campus-Network.pkt` - Packet Tracer project file (open with Cisco Packet Tracer)
- `PROJECT REPORT.pdf` - Full project report
- `Project Structure.png` - Network topology diagram

## Authors
- M Arbaaz Hussain
- Syed Hussain
