# Network Traffic Analysis with Wireshark

## Overview

This project demonstrates practical network traffic analysis using **Wireshark** in an isolated virtual laboratory. Traffic was intentionally generated between a Kali Linux machine and an Ubuntu Server to capture and analyze common network protocols such as ICMP, HTTP, DNS, SSH, TCP, and ARP.

The objective of this lab is to practice packet capture, protocol analysis, endpoint identification, conversation analysis, and packet filtering using Wireshark.

---

## Objectives

- Capture live network traffic.
- Generate different types of network traffic.
- Analyze captured packets.
- Identify network protocols.
- Examine conversations between hosts.
- Practice Wireshark display filters.
- Understand normal network behavior.

---

## Lab Environment

| Component | Details |
|----------|---------|
| Hypervisor | VMware Workstation |
| Attacker Machine | Kali Linux |
| Target Machine | Ubuntu Server |
| Packet Analyzer | Wireshark |
| Web Server | Apache2 |
| Remote Access | OpenSSH |

---

## Network Information

| Device | IP Address |
|---------|------------|
| Kali Linux | 192.168.81.128 |
| Ubuntu Server | 192.168.81.129 |

---

## Generated Traffic

- ICMP (Ping)
- HTTP (curl & wget)
- DNS (nslookup)
- SSH
- TCP
- ARP

---

## Wireshark Analysis

The captured traffic was analyzed using:

- Capture File Properties
- Protocol Hierarchy
- Endpoints
- Conversations
- Display Filters

### Filters Used

```
icmp
http
dns
tcp
arp
ssh
```

---

## Skills Demonstrated

- Wireshark
- Packet Capture
- Network Traffic Analysis
- TCP/IP
- HTTP Analysis
- DNS Analysis
- ICMP Analysis
- SSH Analysis
- ARP Analysis
- Protocol Hierarchy
- Endpoint Analysis
- Conversation Analysis
- Linux Administration
- Ubuntu Server
- Kali Linux

---

## Project Structure

```
captures/
docs/
report/
screenshots/
README.md
LICENSE
DISCLAIMER.md
```

---

## Author

**Mubarak Bashr**

Cybersecurity Student | SOC Analyst (Blue Team)

---

## License

This project is licensed under the MIT License.
