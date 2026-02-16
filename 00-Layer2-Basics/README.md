##Mini Project 00: Layer 2 Basics
objective
understand basic communication using Switch only

##Topology
-1Layer 2 switch
-2PCs
-Single Subnet
-Static IP addressing

##Configurations
All PCs were manually assigned IP addresses within the same subnet.
No default gateway was configured because no router exists in this topology

##Observations
-Devices successfully communicated using ICMP(ping)
-The switch forwarded frames using MAC addresses
-IP addressing was required for identification but not for switching decisions

##Limitations
-Manual IP assignment is time consuming
-High risk of IP conflicts
-Network is not scalable

##Conclusion
This project demonstrates why layer 2 networking alone is insufficient for growing networks and establishes the need for automated IP addressing which leads to DHCP in the next project
