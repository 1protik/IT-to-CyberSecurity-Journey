# 📘 Domain 2: Infrastructure
*CompTIA Network+ N10-009 Training Notes*

This section covers routing, switching, wireless, and cabling technologies that form the backbone of network infrastructure.

---

## 🔹 2.1 Static Routing
Static routing uses **manually configured routes** to direct traffic.

| Feature        | Description |
|----------------|-------------|
| Configuration  | Routes are entered manually by an administrator |
| Advantages     | Simple, predictable, secure (no automatic changes) |
| Disadvantages  | Not scalable, requires manual updates |
| Use Cases      | Small networks, specific paths for security or performance |

---

## 🔹 2.1 Dynamic Routing
Dynamic routing uses **routing protocols** to automatically adjust paths.

| Feature        | Description |
|----------------|-------------|
| Configuration  | Routes are learned and updated automatically |
| Advantages     | Scalable, adapts to network changes |
| Disadvantages  | More complex, requires CPU/memory resources |
| Protocols      | RIP, OSPF, EIGRP, BGP |

---

## 🔹 2.1 Routing Technologies
Routing technologies determine how traffic flows across networks.

| Technology     | Description | Example |
|----------------|-------------|---------|
| Distance Vector| Chooses routes based on hop count | RIP |
| Link State     | Builds a full map of the network | OSPF |
| Path Vector    | Used for large-scale routing between ISPs | BGP |

---

## 🔹 2.1 Network Address Translation (NAT)
NAT allows multiple devices to share a single public IP.

| Type           | Description | Example |
|----------------|-------------|---------|
| Static NAT     | One-to-one mapping of private to public IP | Internal server with fixed public IP |
| Dynamic NAT    | Maps private IPs to available public IPs | Pool of public IPs |
| PAT (Port Address Translation) | Many private IPs share one public IP using ports | Home router with ISP connection |

**Benefit:** Conserves IPv4 addresses, adds security by hiding internal IPs.

---

## 🔹 2.2 VLANs and Trunking
Virtual LANs (VLANs) segment networks logically.

| Concept        | Description |
|----------------|-------------|
| VLANs          | Separate broadcast domains within a switch |
| Trunking       | Allows multiple VLANs to travel across a single physical link |
| 802.1Q         | Standard for VLAN tagging |
| Benefits       | Security, performance, logical separation of departments |

---

## 🔹 2.2 Spanning Tree Protocol (STP)
STP prevents **switching loops** in redundant networks.

| Feature        | Description |
|----------------|-------------|
| Problem        | Loops cause broadcast storms and network failure |
| STP Role       | Blocks redundant paths until needed |
| RSTP           | Rapid Spanning Tree Protocol, faster convergence |

---

## 🔹 2.3 Wireless Technologies / Encryption
Wireless networks use different standards and encryption methods.

| Standard | Frequency | Speed/Range |
|----------|-----------|-------------|
| 802.11a  | 5 GHz     | High speed, shorter range |
| 802.11b  | 2.4 GHz   | Slower, longer range |
| 802.11g  | 2.4 GHz   | Faster than b, backward compatible |
| 802.11n  | 2.4/5 GHz | MIMO support, higher throughput |
| 802.11ac | 5 GHz     | Very high speed |
| 802.11ax | 2.4/5 GHz | Wi-Fi 6, improved efficiency |

**Encryption Methods:**
- **WEP** → Weak, outdated  
- **WPA** → Improved security  
- **WPA2** → Strong, widely used  
- **WPA3** → Latest, strongest  

**Authentication Types:**
- Open → No encryption  
- PSK (Pre-Shared Key) → Shared password  
- Enterprise → Centralized authentication (RADIUS)  

---

## 🔹 2.2 Cabling & Connectors *(Optional – skim)*
Cabling provides the physical medium for data transmission.

| Cable Type     | Description | Use |
|----------------|-------------|-----|
| Twisted Pair   | Cat5e, Cat6, Cat6a | Ethernet |
| Fiber Optic    | Single-mode (long distance), Multi-mode (short distance) | Backbone links |
| Coaxial        | Copper core with shielding | Cable broadband |

**Connectors:**
- RJ45 → Ethernet  
- LC/SC/ST → Fiber  

---

## 🔹 2.3 WAN Technologies *(Optional – skim)*
Wide Area Networks connect geographically dispersed sites.

| Technology     | Description | Example |
|----------------|-------------|---------|
| Leased Lines   | Dedicated point-to-point connections | T1/E1 |
| MPLS           | Efficient routing using labels | Enterprise WAN |
| DSL/Cable      | Broadband WAN options | Home/office internet |
| Satellite      | Remote connectivity | Rural/remote areas |
| VPNs           | Secure tunnels over public internet | Site-to-site VPN |

---
