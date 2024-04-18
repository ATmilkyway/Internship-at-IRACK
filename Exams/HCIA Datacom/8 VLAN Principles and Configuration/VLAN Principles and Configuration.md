VLAN tag
========

IEEE 802.1Q defines a 4-byte VLAN tag for Ethernet frames, which allows switches to identify the VLAN membership of received frames. 🏷️

Frame Header Inspection:
------------------------
The switch examines the frame header, which contains various fields including the source and destination MAC addresses. 🔍

VLAN Tag Identification:
------------------------
Within the frame header, the switch looks for the presence of a 4-byte VLAN tag. This tag is typically inserted by the originating switch or device before transmitting the frame. 🔄

IEEE 802.1Q is a networking standard that defines how Virtual LANs (VLANs) can be implemented on Ethernet networks. It achieves this through a system of VLAN tagging for Ethernet frames. 🌐

![802.1Q](./8021q.png)

VLAN Assignment Methods
-----------------------
- Interface-based VLAN Assignment
- MAC Address-based VLAN Assignment

Interface Types
---------------
- Access interface
- Trunk interface
- Hybrid interface