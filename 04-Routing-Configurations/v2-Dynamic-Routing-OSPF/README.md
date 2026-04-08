# Mini-Project 04 (v2): OSPF with Centralized Router
## Objective
To implement dynamic routing using OSPF in a network with a centralized core router.

## Topology
3 Routers
2 Switches
2 LANs
Centralized core router

## Configuration Summary
OSPF was configured on all routers in Area 0.
Routers exchanged routing information dynamically through the core router.

## Observations
Routers formed neighbor relationships automatically.
Routes were learned dynamically without manual configuration.
The core router acted as a backbone for communication.

## Limitations Identified
Core router becomes critical (single point of failure).
Requires redundancy in real-world networks.

## Conclusion
This design reflects enterprise network architecture and demonstrates the power of OSPF in scalable environments.
