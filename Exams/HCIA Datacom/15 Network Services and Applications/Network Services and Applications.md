# Network Services and Applications

## File Transfer 📁
- **Protocols**: FTP (File Transfer Protocol) and TFTP (Trivial File Transfer Protocol)
- FTP uses separate connections for control (commands) and data transfer.
- TFTP is simpler and uses UDP for data transfer.

## Telnet 💻
- Provides remote access to network devices through a command-line interface.
- Uses TCP port 23.

## DHCP (Dynamic Host Configuration Protocol) ⚙️
- Automatically assigns IP addresses and other network configurations to devices.
- DHCP client sends a DHCP Discover packet to find a DHCP server.
- DHCP server responds with a DHCP Offer packet containing a proposed IP address.
- DHCP client sends a DHCP Request packet to accept the offered IP address.
- DHCP server responds with a DHCP Ack packet to confirm the IP address assignment.
- Benefits: easier network management, efficient IP address allocation.

## HTTP (Hypertext Transfer Protocol) 🌐
- Used for communication between web browsers and web servers.
- Uses TCP port 80.
- Client sends an HTTP request to the server to request a resource (like a web page).
- Server sends an HTTP response containing the requested resource.

## DNS (Domain Name System) 🌐
- Translates domain names (like www.google.com) into IP addresses.

## NTP (Network Time Protocol) Overview ⏰
- If the administrator manually enters commands to change the system time for time synchronization, the workload is heavy and the accuracy cannot be ensured.
- Therefore, the Network Time Protocol (NTP) is designed to synchronize the clocks of devices.