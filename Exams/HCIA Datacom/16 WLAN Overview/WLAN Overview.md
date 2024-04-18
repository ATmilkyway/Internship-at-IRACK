# WLAN Basics (Wireless Local Area Network) 📶

- Uses radio waves (2.4 GHz or 5 GHz) to transmit data instead of cables.
- Offers mobility to users within the coverage area. 🚶‍♂️📡

## WLAN Devices 📶

- **Access Point (AP) 📡**: Connects wireless devices to a wired network.
- **Wireless Router 🌐**: Combines the functionalities of an access point and a router.
- **Network Switch 🔀**: Connects wired devices like routers and access points.
- **PoE Switch (Power over Ethernet) ⚡**: Provides power and data over a single cable to PoE-enabled devices like access points.
- **Wireless Network Controller (AC) 🎛️**: Manages and controls multiple access points in a centralized manner (applicable to enterprise deployments).
- **Station (STA) 📱**: Refers to any device connecting to a WLAN (e.g., laptop, smartphone).

## WLAN Networking Architectures 🏢

- **Fat AP Architecture 🏠**: A standalone access point that manages its own configuration.
- **AC + Fit AP Architecture 🏢**: A network controller manages and configures multiple access points (Fit APs).
- **Agile Distributed Architecture 🌐**: A central AP unit manages remote units (RUs) for wider coverage.

## WLAN Working Process 🔄

1. **AP Onboarding**: The access point obtains an IP address, discovers a controller (AC), and establishes a connection with it.
2. **WLAN Service Configuration Delivery**: The controller delivers WLAN service configurations (e.g., SSID, security settings) to the access point.
3. **STA Access**: Stations discover the WLAN SSID broadcast by the access point, connect to the network, and obtain an IP address (often through DHCP).
4. **WLAN Service Data Forwarding**: Data packets are transmitted between stations and the wired network. This can be done through a central controller (tunnel forwarding) or directly between the accesspoint and the wired network (local forwarding).

## WLAN Security 🔒

- WLAN security protocols like WPA/WPA2 are used to encrypt data packets and prevent unauthorized access.
- Access authentication methods like PSK (pre-shared key) and 802.1X ensure only authorized users can access the network. 🔐