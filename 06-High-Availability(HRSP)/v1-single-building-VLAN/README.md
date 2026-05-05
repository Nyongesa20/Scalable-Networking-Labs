# Mini-Project 06: High Availability (HSRP)

## Objective
To eliminate single points of failure by introducing redundancy using HSRP.

## Topology
2 Routers  
1 Switch  
Multiple VLANs  

## Configuration Summary
Two routers were configured with HSRP to share a virtual IP address. One router acted as active while the other remained standby.

## Observations
Traffic flows through the active router.
When the active router fails, the standby router takes over.
Devices continue communicating without interruption.

## Results
Successful failover achieved with minimal disruption.

## Limitations Identified
No traffic control between VLANs  
No load balancing  
Switch remains a single point of failure  

## Conclusion
HSRP ensures high availability by providing redundancy at the gateway level, preventing network downtime during router failure.
