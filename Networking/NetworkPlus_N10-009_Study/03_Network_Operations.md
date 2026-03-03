# 📘 Domain 3: Network Operations
*CompTIA Network+ N10-009 Training Notes - Professor Messer’s*

This section focuses on monitoring, documentation, policies, and procedures that ensure networks run smoothly and securely.

---

## 🔹 3.1 Monitoring Tools
Monitoring tools help administrators track performance and detect issues.

| Tool/Method   | Description | Example |
|---------------|-------------|---------|
| SNMP          | Simple Network Management Protocol, collects device metrics | Router CPU/memory usage |
| Syslog        | Centralized logging of events | Firewall logs |
| NetFlow/sFlow | Analyzes traffic patterns | Bandwidth usage reports |
| Packet Capture| Examines raw traffic | Wireshark |
| Performance Baselines | Normal operating metrics for comparison | Average latency, throughput |

**Key Notes:**
- Monitoring provides **early detection** of problems.
- Logs and baselines are critical for **troubleshooting**.

---

## 🔹 3.2 Network Documentation
Documentation ensures consistency and helps with troubleshooting.

| Document Type | Description | Example |
|---------------|-------------|---------|
| Network Diagram | Visual map of devices and connections | Topology chart |
| Asset Inventory | List of hardware/software | Switches, routers, licenses |
| IP Addressing Plan | Organized allocation of IPs | Subnet chart |
| Change Management | Records of modifications | Firewall rule updates |
| Policies & Procedures | Rules for operation | Security policy |

**Key Notes:**
- Documentation reduces downtime.
- Essential for audits and compliance.

---

## 🔹 3.3 Organizational Policies
Policies define how networks are managed and secured.

| Policy Type   | Description | Example |
|---------------|-------------|---------|
| Acceptable Use| Defines proper use of IT resources | No personal downloads |
| Security Policy| Protects data and systems | Password complexity rules |
| BYOD Policy   | Rules for personal devices | Require MDM software |
| Remote Access | Guidelines for VPN usage | MFA required |
| Incident Response | Steps for handling breaches | Escalation procedures |

---

## 🔹 3.4 Disaster Recovery & Business Continuity
Plans ensure operations continue during outages or disasters.

| Concept       | Description | Example |
|---------------|-------------|---------|
| Backup Strategy | Regular data copies | Daily incremental backups |
| Redundancy    | Duplicate systems for failover | Dual power supplies |
| Business Continuity | Processes to maintain operations | Alternate work sites |
| Disaster Recovery | Steps to restore systems | Restore from backups |

**Key Notes:**
- Recovery Time Objective (RTO) → How quickly systems must be restored.
- Recovery Point Objective (RPO) → How much data loss is acceptable.

---

## 🔹 3.5 Remote Access Methods
Remote access allows users to connect securely from outside the network.

| Method        | Description | Example |
|---------------|-------------|---------|
| VPN           | Encrypted tunnel over public internet | Site-to-site VPN |
| SSL VPN       | Uses HTTPS for secure access | Remote worker login |
| RDP           | Remote Desktop Protocol | Windows remote access |
| SSH           | Secure shell for command-line access | Linux server management |

**Key Notes:**
- Always use **encryption** and **authentication**.
- Remote access must comply with **security policies**.

---
