# Mini-Project 04 (v1): Static Routing
## Objective
To enable communication between multiple LANs connected via different routers using static routing.

## Topology
2 Routers
2 Switches
2 LANs
Router-to-router link

## Configuration Summary
Router interfaces were configured with IP addresses.
Static routes were added to enable communication between networks.

## Observations
Routers only know directly connected networks by default.
Static routes are required for remote network communication.
Traffic follows manually defined paths.

## Limitations Identified
Routes must be configured manually on each router.
Not scalable for large networks.
Changes require manual updates on all routers.

## Conclusion
Static routing works for small networks but becomes inefficient as the network grows,
leading to the need for dynamic routing.
