Inter-VLAN Communication
=======================

- PCs on the same network segment in the same VLAN can directly communicate with each other without the need for Layer 3 forwarding devices. This communication mode is called Layer 2 communication. 🖥️🌐

- Inter-VLAN communication belongs to Layer 3 communication, which requires Layer 3 devices.

- Common Layer 3 devices: routers, Layer 3 switches, firewalls, etc. 🌐🔌🔥

Inter-VLAN communication methods:
--------------------------------

1. Router Physical Interfaces:

   - Simple setup for small networks. 🏢🌐
   - Separate physical interface per VLAN on router.
   - More cables and router resources needed for many VLANs.

2. Router Sub-interfaces:

   - Single physical interface with sub-interfaces for each VLAN.
   - More efficient resource usage than separate interfaces.
   - Slightly more complex configuration.

3. VLAN Interfaces (on some switches):

   - Create routing interfaces directly on the switch (if supported).
   - Eliminates the need for a separate router (potentially).
   - Not all switches support this, and functionality can vary.