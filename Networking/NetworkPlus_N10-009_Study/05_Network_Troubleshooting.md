# 📘 Domain 5: Network Troubleshooting
*CompTIA Network+ N10-009 Training Notes - Professor Messer’s*

This section covers troubleshooting methodologies, common issues, and tools used to diagnose and resolve network problems.

---

## 🔹 5.1 Troubleshooting Methodology
A structured approach ensures efficient problem resolution.

| Step            | Description | Example |
|-----------------|-------------|---------|
| Identify Problem | Gather information, define symptoms | User reports no internet |
| Establish Theory | Hypothesize possible causes | Cable unplugged, DHCP issue |
| Test Theory      | Verify with testing | Ping gateway |
| Establish Plan   | Decide on corrective action | Replace cable, restart DHCP |
| Implement Solution | Apply fix | Reconnect cable |
| Verify Functionality | Confirm system works | User can browse web |
| Document Findings | Record issue and resolution | Update helpdesk ticket |

---

## 🔹 5.2 Interface Issues / Hardware Issues
Problems at the physical or interface level.

| Issue           | Description | Example |
|-----------------|-------------|---------|
| Interface Errors| CRC errors, collisions | Faulty NIC |
| Duplex Mismatch | One side full, other half duplex | Slow performance |
| Speed Mismatch  | Different link speeds | 1 Gbps vs 100 Mbps |
| Hardware Failure| Device malfunction | Dead switch port |
| Cable Problems  | Damaged or miswired cables | Broken RJ45 connector |

**Key Notes:**
- Always check **physical connections first**.
- Use LEDs and link lights for quick diagnostics.

---

## 🔹 5.3 Switching Issues / Routing and IP Issues
Problems at Layer 2 and Layer 3.

| Issue           | Description | Example |
|-----------------|-------------|---------|
| Switching Loops | Redundant paths without STP | Broadcast storm |
| VLAN Misconfig  | Incorrect VLAN assignment | User in wrong VLAN |
| Routing Issues  | Incorrect routes or missing entries | No path to destination |
| IP Conflicts    | Duplicate IP addresses | Two hosts with same IP |
| DHCP Problems   | Failure to assign IPs | Client stuck with APIPA (169.254.x.x) |

---

## 🔹 5.4 Performance Issues / Wireless Issues
Performance problems can be wired or wireless.

| Issue           | Description | Example |
|-----------------|-------------|---------|
| High Latency    | Delay in communication | Slow VoIP calls |
| Jitter          | Variable delay | Choppy video stream |
| Packet Loss     | Dropped packets | Poor gaming experience |
| Bandwidth Saturation | Excessive traffic | File transfer hogging link |
| Wireless Interference | Overlapping channels, devices | Microwave interference |
| Weak Signal     | Distance from AP | Low Wi-Fi bars |
| Authentication Failures | Incorrect credentials | WPA2 password mismatch |

---

## 🔹 5.5 Software Tools / Command Line Tools / Basic Network Device Commands
Tools and commands for diagnosing issues.

| Tool/Command    | Description | Example |
|-----------------|-------------|---------|
| Ping            | Tests connectivity | `ping 8.8.8.8` |
| Traceroute      | Shows path to destination | `tracert google.com` |
| ipconfig/ifconfig | Displays IP configuration | `ipconfig /all` |
| nslookup/dig    | DNS query tools | `nslookup example.com` |
| netstat         | Shows active connections | `netstat -an` |
| arp             | Displays ARP table | `arp -a` |
| telnet/ssh      | Tests port connectivity | `telnet server 80` |
| Syslog          | Centralized logging | Router logs |
| Packet Capture  | Analyzes traffic | Wireshark |

**Key Notes:**
- CLI tools are essential for **quick diagnostics**.
- Combine multiple tools for deeper troubleshooting.

---
