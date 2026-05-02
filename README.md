# Cisco Packet Tracer Network Simulation

Simulation of a private and public network connection between three homes using Cisco Packet Tracer.

The project implements a complete network scenario with private LANs, router configuration, NAT, DHCP, port forwarding, static routes, and RIPv2 dynamic routing.

## Project Overview

This project represents a network infrastructure composed of three different home networks connected through routers and public/private addressing.

The goal of the simulation is to show how multiple private networks can communicate with each other and access shared/public services through proper routing and address translation.

## Main Features

- Three interconnected home networks
- Private and public IP addressing
- NAT configuration
- DHCP service for automatic IP assignment
- Port forwarding
- Static routes
- RIPv2 routing protocol
- Router and end-device configuration
- Connectivity testing through Packet Tracer simulation tools

## Repository Structure


Cisco-Packet-Tracer-NetworkSimulation/
├── README.md
├── packet-tracer/
│   └── House_Project.pkt
├── docs/
│   └── IOS-command-log.txt
└── assets/
    └── house-background.png


## Files Description

| File | Description |
|---|---|
| `packet-tracer/House_Project.pkt` | Main Cisco Packet Tracer simulation file |
| `docs/IOS-command-log.txt` | IOS commands used to configure routers and network devices |
| `assets/house-background.png` | Background image used in the Packet Tracer topology |
| `README.md` | Project documentation |

## Network Technologies Used

### NAT

Network Address Translation is used to allow devices with private IP addresses to communicate through public network segments.

### DHCP

DHCP is configured to automatically assign IP addresses, subnet masks, gateways, and other network parameters to end devices.

### Port Forwarding

Port forwarding is used to make specific internal services reachable from outside the private network.

### Static Routing

Static routes are configured manually to define specific paths between different networks.

### RIPv2

RIPv2 is used as a dynamic routing protocol to exchange routing information between routers.

## How to Open the Project

1. Install Cisco Packet Tracer.
2. Clone or download this repository.
3. Open the file:


packet-tracer/House_Project.pkt


4. Inspect the topology, router configurations, IP addressing, and simulation behavior.

## How to Test the Network

Inside Cisco Packet Tracer, you can test the network by:

- Sending ICMP packets between PCs
- Using the `ping` command from end devices
- Checking router routing tables
- Verifying DHCP address assignment
- Testing NAT and port forwarding behavior
- Inspecting packet flow in Simulation Mode

Useful IOS commands:


show ip route
show ip interface brief
show running-config
show ip nat translations
show ip protocols
ping <destination-ip>
traceroute <destination-ip>


## Project Goals

The main goals of this project are:

- Design a realistic small network scenario
- Configure communication between multiple private networks
- Apply routing concepts in a practical environment
- Use NAT and port forwarding to connect private and public networks
- Practice Cisco IOS commands
- Verify network behavior through Packet Tracer simulation

## Requirements

- Cisco Packet Tracer
- Basic knowledge of:
  - IP addressing
  - Subnetting
  - Routers and switches
  - Static routing
  - NAT
  - DHCP
  - RIPv2

## Author

Created by **Camillo Nicoletti**.

## License

This project is intended for educational purposes.
