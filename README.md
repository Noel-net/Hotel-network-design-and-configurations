# Hotel-network-design-and-configurations
This a network configuration for a small hotel with 1 building and 3 different floors with 3 different departments on each floor. The requirements were to design the network in a way that all departments across the hotel can communicate. 
I configure OSPF as my routing protocol and inter-vlan routing on each router.
VLAN management is configured on Layer 2 switches and all port assignments as per VLAN.
A trunk port is configured on the interface between switches and routers to allow the passage of different VLANs on the same interface.
