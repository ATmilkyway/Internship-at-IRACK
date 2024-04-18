# WAN (Wide Area Network) 🌍

A network that spans a large geographical area, connecting geographically distant LANs (Local Area Networks).

## PPP (Point-to-Point Protocol) 🔄

A data link layer protocol used for establishing connections over serial links. It provides user authentication, error detection, and data compression.

### PPP Components

- **LCP (Link Control Protocol)**: Establishes and configures the link.
- **NCP (Network Control Protocol)**: Negotiates network layer parameters (e.g., IP address).
- **PAP (Password Authentication Protocol)**: Simple username/password authentication.
- **CHAP (Challenge Handshake Authentication Protocol)**: More secure three-way handshake authentication with encryption.
- **PPPoE (PPP over Ethernet)**: Encapsulates PPP frames within Ethernet frames, enabling PPP functionality over Ethernet connections. It's commonly used for broadband internet access where users authenticate with a service provider.

### PPPoE Session Stages

1. **Discovery**: Client broadcasts a request, server responds with an offer, client selects a server and confirms a session.
2. **Session**: PPP negotiation (LCP, authentication, NCP) occurs.
3. **Termination**: Client or server sends a PADT packet to disconnect.

The document also provides configuration examples for:

- Enabling PAP/CHAP authentication on PPP links.
- Configuring a PPPoE client on a Huawei router.
- Configuring a PPPoE server on a Huawei router, including address pool creation and user authentication.