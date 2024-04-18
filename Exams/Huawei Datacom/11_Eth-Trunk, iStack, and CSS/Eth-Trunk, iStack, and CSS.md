🔀 Eth-Trunk, iStack, and CSS

Network Reliability
===================

Network reliability refers to the capability of ensuring nonstop network services when a single point or multiple points of failure occur on a device or link. 🔄🔒

Network reliability can be implemented at the card, device, and link levels.

A modular switch, also known as a chassis switch, is a type of network switch that offers greater flexibility, scalability, and redundancy compared to fixed configuration switches. Here's a breakdown of its key characteristics:

Modular Design:
---------------
Unlike fixed switches with a pre-defined number of ports and functionalities, a modular switch consists of a chassis and modular components like line cards, supervisor modules, and power supplies. 🖥️🔌

These modules can be inserted or removed from the chassis as needed, allowing for customization and future expansion.

Benefits:
---------
- Scalability: You can add new modules (e.g., additional line cards) to the chassis to increase the number of ports and handle growing network demands. 📈
- Flexibility: You can choose the specific modules required for your network, such as modules with different port types (fiber optic, copper) or functionalities (routing, security). 🛠️
- Redundancy: Redundant modules (e.g., power supplies, supervisor modules) can be installed to ensure the switch remains operational even if a module fails. This enhances network reliability. 🔁
- Upgradability: As technology evolves, you can upgrade specific modules within the chassis instead of replacing the entire switch, potentially reducing costs. 💡

Components of a Modular Switch:
------------------------------
- Chassis: The mainframe, like the foundation of a building. 🏢
- Power Modules (PSUs): Keep the switch powered, often with redundancy for extra reliability (like backup generators). 🔌⚡
- Fan Modules: The cooling system, ensuring the switch doesn't overheat (like air conditioners). ❄️🌬️
- Main Processing Unit (MPU): The brain of the switch, managing everything (like a CPU in a computer). 🧠💻
- Switch Fabric Unit (SFU): The traffic director, efficiently routing data packets within the switch (like a central hub in a city). 🚦🌐
- Line Processing Units (LPUs): The port managers, handling data traffic on individual switch ports (like individual traffic controllers managing specific lanes). 🚥🔌

Eth-Trunk, also known as Ethernet Link Aggregation (LAG), is a technology used to bundle multiple physical Ethernet links into a single logical link.

- Ethernet link aggregation, also called Eth-Trunk, bundles multiple physical links into a logical link to increase link bandwidth, without having to upgrade hardware. 🤝🔗

Both manual mode and LACP (Link Aggregation Control Protocol) are methods for configuring Eth-Trunk (Ethernet Link Aggregation) on a switch.

Manual mode: An Eth-Trunk is manually created, and its member interfaces are manually configured. LACP is not used for negotiation between the two systems.

LACP mode: A link aggregation mode that uses the LACP protocol. Devices exchange Link Aggregation Control Protocol Data Units (LACPDUs) to ensure that the peer interfaces are member interfaces that belong to the same Eth-Trunk and are on the same device.

In the context of networking, particularly with Huawei switches, "stack" refers to a technology that allows you to connect multiple switches into a single logical unit.

There are two main Huawei stacking technologies: iStack and CSS. 🔄🔒