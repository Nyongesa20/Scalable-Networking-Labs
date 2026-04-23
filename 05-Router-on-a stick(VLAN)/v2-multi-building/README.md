# Mini-Project 05: Multi-Building VLAN + OSPF Network
## Objective
To connect multiple buildings with VLAN-based networks and enable communication using dynamic routing (OSPF).

## Topology
3 Routers (2 edge, 1 core)  
2 Switches  
Multiple VLANs across buildings  

## Configuration Summary
Each building used Router-on-a-Stick for VLAN routing. Routers were interconnected using /30 networks. OSPF was configured to dynamically share routes between routers.

## Observations
VLANs operate within buildings.
Routing enables inter-building communication.
OSPF automatically updates routing tables.

## Limitations Identified
No redundancy  
No access control  
Central router is a single point of failure  

## Conclusion
This project demonstrates enterprise-level networking by combining VLAN segmentation and dynamic routing across multiple locations.

## Note on Design Approach
This project extends the VLAN concept beyond a single building to a multi-building environment.

At this stage, inter-building communication required the use of routing. OSPF was introduced to enable communication between different networks.

This was an exploratory implementation to understand how VLAN-based networks interact across routers.

A more structured and detailed implementation of OSPF is covered separately under the Routing Configurations project.
