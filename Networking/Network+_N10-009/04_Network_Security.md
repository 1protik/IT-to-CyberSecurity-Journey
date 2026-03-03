# 📘 Domain 4: Network Security
*CompTIA Network+ N10-009 Training Notes*

This section covers security concepts, technologies, and practices to protect networks from threats and vulnerabilities.

---

## 🔹 4.1 Security Concepts / Authentication / Security Technologies
Security concepts form the foundation of protecting networks.

| Concept            | Description | Example |
|--------------------|-------------|---------|
| Confidentiality    | Ensuring data is only accessible to authorized users | Encryption |
| Integrity          | Ensuring data is not altered | Hashing |
| Availability       | Ensuring systems are accessible when needed | Redundant servers |
| Least Privilege    | Users only get the access they need | Role-based access control |
| Defense in Depth   | Multiple layers of security | Firewall + IDS + Antivirus |

**Authentication Methods:**
- Passwords → Basic authentication  
- Multifactor → Combines two or more methods (e.g., password + SMS code)  
- Biometrics → Uses physical traits (fingerprint, facial recognition)  
- Certificates → Digital certificates for identity verification  

**Security Technologies:**
- **Firewalls** → Control traffic based on rules  
- **VPNs** → Secure tunnels over public internet  
- **Proxy Servers** → Intermediary for requests, web filtering  
- **IDS/IPS** → Detect and prevent malicious traffic  
- **SIEM** → Centralized log analysis and correlation  

---

## 🔹 4.1 Segmentation Enforcement
Segmentation divides networks into smaller, controlled sections.

| Technique      | Description | Example |
|----------------|-------------|---------|
| VLANs          | Logical separation of broadcast domains | Departmental VLANs |
| Subnets        | IP-based segmentation | 192.168.1.0/24 vs 192.168.2.0/24 |
| DMZ            | Isolated zone for public-facing servers | Web server in DMZ |
| Microsegmentation | Fine-grained isolation | Virtualized environments |

**Benefits:**
- Limits attack surface  
- Improves performance  
- Enforces security boundaries  

---

## 🔹 4.2 Denial of Service / VLAN Hopping / ARP & DNS Poisoning / Social Engineering / Malware
Common threats and vulnerabilities that target networks.

| Threat              | Description | Example |
|---------------------|-------------|---------|
| Denial of Service (DoS/DDoS) | Flooding a system with traffic | Botnet attack |
| VLAN Hopping        | Exploiting trunk misconfigurations to access other VLANs | Double-tagging attack |
| ARP Poisoning       | Spoofing ARP messages to redirect traffic | Man-in-the-Middle |
| DNS Poisoning       | Corrupting DNS cache to redirect users | Fake banking site |
| Social Engineering  | Manipulating people to gain access | Phishing emails |
| Malware             | Malicious software | Viruses, worms, ransomware |

**Key Notes:**
- Technical defenses must be paired with **user awareness training**.  
- Many attacks exploit **misconfigurations** or **human error**.  

---

## 🔹 4.3 Device Security / Security Rules
Securing devices and enforcing rules ensures consistent protection.

| Control        | Description | Example |
|----------------|-------------|---------|
| Hardening      | Removing unnecessary services, patching | Disable unused ports |
| Access Control | Restricting who can use devices | RBAC policies |
| Security Rules | Firewall/ACL rules to control traffic | Block inbound Telnet |
| Logging        | Recording events for auditing | Syslog server |
| Updates        | Regular patching of firmware/software | Monthly updates |

**Best Practices:**
- Default deny → Block all traffic unless explicitly allowed  
- Principle of least privilege → Users/devices only get required access  
- Regular audits → Verify compliance with policies  

---

## 🔹 4.4 Physical Security *(Optional – skim)*
Physical measures protect hardware and facilities.

| Control        | Description | Example |
|----------------|-------------|---------|
| Locks          | Restrict access | Server room |
| Badges         | Identify authorized personnel | Employee ID cards |
| CCTV           | Surveillance cameras | Monitoring entrances |
| Guards         | Human security presence | Data center security |
| Environmental Controls | Protect against hazards | Fire suppression, HVAC |

---
