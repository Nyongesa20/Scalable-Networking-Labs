# Mini-Project 05: Router-on-a-Stick (Multi-Floor VLAN Network)
## Objective
To design and implement a segmented network using VLANs across multiple floors and enable communication between departments using Router-on-a-Stick with dynamic IP addressing.

## Topology
1 Router  
2 Switches (representing different floors)  
Multiple PCs across 3 floors  
2 VLANs (Finance and ICT)

## VLAN Design
- VLAN 10 → Finance → 192.168.10.0/24  
- VLAN 20 → ICT → 192.168.20.0/24  

## Configuration Summary
VLANs were created on both switches and assigned to access ports for end devices. A trunk link was configured between the switches to extend VLANs across floors. The main switch was connected to the router using a trunk link. The router was configured using subinterfaces (Router-on-a-Stick) to enable inter-VLAN routing. DHCP was configured on the router to automatically assign IP addresses to devices in each VLAN.

## Observations
Devices in the same VLAN communicated across different floors without requiring routing.  
Devices in different VLANs communicated through the router.  
Trunk links allowed VLAN traffic to traverse between switches.  
DHCP successfully assigned IP addresses dynamically across the network.

## Problems Encountered
- VLAN inconsistencies between switches prevented communication  
- Missing trunk configuration blocked VLAN traffic  
- Incorrect gateway configuration caused inter-VLAN communication failure  

## Troubleshooting Steps
- Verified VLAN configuration using `show vlan brief`  
- Checked trunk links using `show interfaces trunk`  
- Verified router interfaces using `show ip interface brief`  
- Tested connectivity using `ping` and simulation mode  

## Results
- Successful communication within VLANs across multiple floors  
- Successful inter-VLAN communication through the router  
- Automatic IP assignment using DHCP across all devices  

## Limitations Identified
- Single router creates a bottleneck  
- No redundancy (single point of failure)  
- No access control between VLANs  

## Conclusion
This project demonstrates how VLANs can be used to segment a network across multiple floors while maintaining communication using Router-on-a-Stick. It highlights the importance of trunking, proper VLAN configuration, and routing for scalable enterprise network design.
