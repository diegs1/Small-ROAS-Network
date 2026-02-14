This project is a small Router-on-a-Stick (ROAS) topology built in Cisco Packet Tracer. It demonstrates VLAN segmentation and inter-VLAN routing using a single trunk link between a Layer 2 switch and a router.

VLANs
- VLAN 10 – Management
- VLAN 20 – Finance
- VLAN 30 – Engineering
- VLAN 40 – HR

Key Concepts Demonstrated
- VLAN creation and access port assignment
- 802.1Q trunk configuration
- Router subinterfaces
- Inter-VLAN routing
- Default gateway configuration per VLAN

Result
- All hosts within the same VLAN can communicate, and inter-VLAN communication is achieved through router subinterfaces over a single trunk link.

What I Learned
- How trunk links carry multiple VLANs over a single interface
- How router subinterfaces process tagged traffic
- How default gateways allow inter-VLAN communication

Topology

<img width="904" height="698" alt="ROAS-img1" src="https://github.com/user-attachments/assets/f6829efb-1cd1-4700-8527-1ba209418233" />
