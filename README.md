This project is a small Router-on-a-Stick (ROAS) topology built in Cisco Packet Tracer. It demonstrates VLAN segmentation and inter-VLAN routing using a single trunk link between a Layer 2 switch and a router.

VLANs
- VLAN 10 – Management
- VLAN 20 – Finance
- VLAN 30 – Engineering
- VLAN 40 – HR

Each VLAN contains three hosts and is assigned its own subnet.

Key Concepts Demonstrated
- VLAN creation and access port assignment
- 802.1Q trunk configuration
- Router subinterfaces
- Inter-VLAN routing
- Default gateway configuration per VLAN

Result
- All hosts within the same VLAN can communicate, and inter-VLAN communication is achieved through router subinterfaces over a single trunk link.
