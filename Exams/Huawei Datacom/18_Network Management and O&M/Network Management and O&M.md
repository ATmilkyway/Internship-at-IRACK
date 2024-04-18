# Network Management and O&M Concepts 🖥️🔧

Network administrators ensure networks function properly through configuration management, performance management, fault management, security management, and accounting management.

## Traditional Network Management

- Involves manual configuration through CLI (Command Line Interface) or web interfaces on individual devices.

## SNMP (Simple Network Management Protocol)

- A widely used protocol for network management on TCP/IP networks.
- Enables a central network management station (NMS) to monitor and manage network devices.
- Devices run an agent process that communicates with the NMS using SNMP messages.
- Management Information Bases (MIBs) define the data structure for SNMP messages.
- SNMPv1, SNMPv2c, and SNMPv3 offer varying levels of security.

## Huawei iMaster NCE

- A platform for intelligent network O&M, integrating management, control, analysis, and AI functions.
- Manages traditional devices through CLI/SNMP and SDN (Software-Defined Networking) devices through NETCONF/YANG.
- Uses Telemetry for real-time data collection and performs intelligent data analysis for proactive O&M.

## NETCONF and YANG

- NETCONF is a protocol for managing network device configurations.
- YANG is a data modeling language that defines the structure of NETCONF data.
- Together, they enable automated and standardized network configuration management.

## Telemetry

- A technology for high-speed, real-time data collection from network devices.
- Devices push data (like interface statistics) to collectors at regular intervals.

### Key Takeaways

- Network management has evolved from manual CLI to intelligent platforms like iMaster NCE.
- SNMP provides a basic framework for network monitoring and management.
- NETCONF/YANG offer standardized and automated network configuration.
- Telemetry enables real-time data collection for proactive network management.