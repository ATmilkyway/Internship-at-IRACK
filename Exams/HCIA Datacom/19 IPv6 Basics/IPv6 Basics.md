# IPv6 Overview 🌐

- IPv4 address exhaustion necessitates a move to IPv6.
- IPv6 offers a vastly larger address space, hierarchical allocation, simplified headers, security features, mobility support, and enhanced QoS.

## IPv6 Address Configuration

- An IPv6 address is 128 bits long, typically represented with colons separating hexadecimal segments (e.g., 2001:DB8::3234:5678).
- It consists of a network prefix and an interface ID.
- Common address types include:
  - Global Unicast Address (GUA): routable on the public internet.
  - Unique Local Address (ULA): non-routable on the public internet but unique within an organization.
  - Link-Local Address (LLA): used for communication on a single link.

## Typical IPv6 Configuration Examples

- Basic configurations involve enabling IPv6, setting interface addresses (manual or automatic - SLAAC/DHCPv6), and potentially static routes.
- Neighbor Discovery Protocol (NDP) is crucial for address resolution and Duplicate Address Detection (DAD).

The document showcases configuration examples for a small IPv6 network with static addresses, DHCPv6 server, SLAAC, and static routes.