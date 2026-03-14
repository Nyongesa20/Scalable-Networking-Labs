\##Mini-project 02 centralized Services

\##Objective
To introduce centralized networkservices and understand the importance of static IP addressing for shared resources



\##Topology
-A Router as DHCP server
-A layer2 Switch
-3PCs
-a network printer

-a server



\##Configurations summary

DHCP was configured to dynamically assign IP addresses to user devices.

Infrastructure IPs were excluded from the DHCP pool

Printer and server were assigned static IPs to ensure consistent accessibility



\##Observations

-PCs successfully accessed the printer and the server using a fixed IP

-DHCP simplified user device management

-IP exclusions removed IP conflicts



\##Limitations
-All devices reside in a single broadcast domain
-No logical separation between departments



\##Conclusion
This project demonstrates shared resources require stable addressing and highlights the need for network segmentation leading to the introduction of the multiple LANs in the next project

