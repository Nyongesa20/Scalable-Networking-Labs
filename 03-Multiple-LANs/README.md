# Mini-Project 03: Multiple LANs
## Objective
To separate network devices into multiple LANs and enable communication between them using a router.

## Topology
- 1 Router
- 2 Switches
- 2 LANs
- DHCP for both networks
- Static printer in LAN1

## Configuration Summary
Two router interfaces were configured for two different subnets.
DHCP pools were created for each LAN.
Devices communicated through the router.

## Observations
- Devices in the same LAN communicate directly.
- Devices in different LANs require routing.
- Default gateway is required for inter-LAN communication.

## Limitations Identified
- Router needs multiple physical interfaces.
- Network growth increases hardware complexity.

## Conclusion
This project shows why routers are required between LANs and highlights scalability limitations, leading to the need for dynamic routing in the next project.
