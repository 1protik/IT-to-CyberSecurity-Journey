# 📘 Domain 1: Networking Concepts - Professor Messer’s
*CompTIA Network+ N10-009 Training Notes*

This repository provides written summaries of key networking concepts, so learners can study without watching the videos.

---

## 🔹 1.1 Understanding the OSI Model
The OSI (Open Systems Interconnection) Model is a **conceptual framework** that standardizes how data is transmitted across networks. It divides communication into **seven layers**, each with a specific role.

| Layer        | Function                                | Examples              |
|--------------|-----------------------------------------|-----------------------|
| Application  | Interfaces with user applications       | HTTP, FTP, SMTP       |
| Presentation | Data formatting, encryption, compression| SSL/TLS, JPEG         |
| Session      | Manages sessions between devices        | NetBIOS, RPC          |
| Transport    | Reliable delivery, error checking       | TCP, UDP              |
| Network      | Routing, logical addressing             | IP, ICMP              |
| Data Link    | MAC addressing, switching               | Ethernet, PPP         |
| Physical     | Hardware, signals, cables               | Fiber, Copper         |

**Key Notes:**
- OSI is **theoretical**, TCP/IP is **practical**.
- Each layer depends on the one below it.
- Useful for **troubleshooting** network issues.

---

## 🔹 1.2 Networking Devices
Networking devices are the **building blocks** of communication.

- **Router** → Connects different networks, routes traffic using IP addresses.  
- **Switch** → Connects devices within a LAN, forwards traffic based on MAC addresses.  
- **Hub** → Broadcasts data to all connected devices (inefficient, mostly obsolete).  
- **Bridge** → Connects two network segments, filters traffic.  
- **Access Point (AP)** → Provides wireless connectivity.  
- **Firewall** → Controls traffic based on security rules.  

---

## 🔹 1.2 Networking Functions
Networking functions describe how devices handle traffic.

- **Forwarding** → Moving data between devices.  
- **Filtering** → Blocking or allowing traffic based on rules.  
- **Segmentation** → Dividing networks for performance/security.  
- **Collision Domains** → Areas where data collisions can occur.  
- **Broadcast Domains** → Areas where broadcast traffic is received.  

---

## 🔹 1.3 Designing the Cloud
Cloud computing introduces new design principles.

- **Elasticity** → Resources scale up/down as needed.  
- **On-demand** → Services available instantly.  
- **Measured Service** → Usage is tracked and billed.  
- **Resource Pooling** → Shared infrastructure across users.  

---

## 🔹 1.3 Cloud Models
Cloud computing offers **flexible, scalable resources**.

| Model | Description                  | Example              |
|-------|------------------------------|----------------------|
| IaaS  | Infrastructure as a Service  | AWS EC2, Azure VMs   |
| PaaS  | Platform as a Service        | Google App Engine    |
| SaaS  | Software as a Service        | Gmail, Office 365    |

**Deployment Types:**
- **Public Cloud** → Shared infrastructure (AWS, Azure).  
- **Private Cloud** → Dedicated to one organization.  
- **Hybrid Cloud** → Mix of public + private.  

---

## 🔹 1.4 Introduction to IP
IP (Internet Protocol) provides logical addressing for devices.

- **IPv4** → 32-bit addresses (e.g., 192.168.1.1).  
- **IPv6** → 128-bit addresses (e.g., 2001:db8::1).  
- **Subnetting** → Dividing networks into smaller segments.  
- **CIDR Notation** → e.g., 192.168.1.0/24.  

---

## 🔹 1.4 Common Ports
| Port | Protocol | Use                  |
|------|----------|----------------------|
| 20/21| FTP      | File transfer        |
| 22   | SSH      | Secure remote login  |
| 25   | SMTP     | Email sending        |
| 53   | DNS      | Domain name resolution|
| 80   | HTTP     | Web traffic          |
| 443  | HTTPS    | Secure web traffic   |

---

## 🔹 1.4 Other Useful Protocols
Beyond TCP and UDP, other protocols support networking.

- **DHCP** → Assigns IP addresses dynamically.  
- **DNS** → Resolves domain names to IPs.  
- **SNMP** → Network monitoring and management.  
- **NTP** → Time synchronization across devices.  

---

## 🔹 1.4 Network Communication
Network communication involves encapsulation and addressing.

- **Encapsulation** → Wrapping data with headers at each layer.  
- **Decapsulation** → Removing headers at the destination.  
- **MAC vs IP** → MAC for local delivery, IP for routing across networks.  

---

## 🔹 1.5 Wireless Networking
Wireless networking uses **radio frequencies** to connect devices.

- **Standards:** 802.11a/b/g/n/ac/ax (Wi-Fi generations).  
- **Frequencies:** 2.4 GHz (longer range, slower) vs 5 GHz (shorter range, faster).  
- **Security:** WEP (weak), WPA/WPA2 (stronger), WPA3 (latest).  
- **SSID:** Network name broadcast by AP.  
- **Channels:** Avoid overlap to reduce interference.  

---
