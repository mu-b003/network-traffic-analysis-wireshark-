# Network Traffic Analysis Report

## Project Information

| Item | Value |
|------|-------|
| Project | Network Traffic Analysis with Wireshark |
| Analyst | Mubarak Bashr |
| Environment | Isolated Virtual Lab |
| Hypervisor | VMware Workstation |
| Analysis Tool | Wireshark |
| Capture Format | PCAPNG |

---

# Executive Summary

This project demonstrates practical network traffic analysis using Wireshark in an isolated virtual environment. Network traffic was intentionally generated between a Kali Linux machine and an Ubuntu Server to analyze common protocols and understand normal network behavior.

The captured traffic included ICMP, HTTP, DNS, SSH, TCP, and ARP communications. Each protocol was examined using Wireshark's built-in analysis tools and display filters.

---

# Lab Environment

| Component | Description |
|-----------|-------------|
| Attacker Machine | Kali Linux |
| Target Machine | Ubuntu Server |
| Web Server | Apache2 |
| Remote Access | OpenSSH |
| Packet Analyzer | Wireshark |

---

# Network Configuration

| Device | IP Address |
|----------|------------|
| Kali Linux | 192.168.81.128 |
| Ubuntu Server | 192.168.81.129 |

Network Range

```
192.168.81.0/24
```

---

# Traffic Generation

The following activities were performed to generate network traffic:

- System update
- Apache service verification
- SSH service verification
- ICMP Ping
- HTTP requests using curl
- Multiple HTTP requests
- DNS lookups
- HTTP download using wget
- SSH login session

---

# Capture Statistics

| Metric | Value |
|--------|-------|
| File Name | network-analysis.pcapng |
| File Size | 280 KB |
| Capture Duration | 10 Minutes 58 Seconds |
| Total Packets | 1370 |
| Average Packets per Second | 2.1 |
| Average Bit Rate | 2835 bits/s |

---

# Protocol Analysis

The captured traffic contained the following protocols:

- IPv4
- TCP
- SSH
- HTTP
- DNS
- ICMP
- ARP

TCP represented the majority of the captured traffic because of SSH communication and HTTP requests.

---

# Endpoint Analysis

Most Active Hosts

| IP Address | Description |
|------------|-------------|
| 192.168.81.128 | Kali Linux |
| 192.168.81.129 | Ubuntu Server |

Additional external IP addresses appeared during DNS resolution and Ubuntu connectivity checks.

---

# Conversation Analysis

The largest communication occurred between the Kali Linux machine and the Ubuntu Server.

| Source | Destination |
|---------|-------------|
| 192.168.81.128 | 192.168.81.129 |

Conversation Statistics

- Approximately 1121 packets
- Approximately 197 KB transferred
- Approximately 503 seconds

---

# Display Filters Used

## ICMP

Verified successful Ping communication between the two virtual machines.

---

## HTTP

Displayed HTTP GET requests and server responses generated using curl and wget.

---

## DNS

Displayed DNS queries and responses for:

- github.com
- bitpluss.com

---

## TCP

Displayed:

- TCP Handshake
- Data Transfer
- Connection Termination

---

## SSH

Displayed SSHv2 encrypted communication including:

- Protocol Exchange
- Key Exchange
- New Keys
- Encrypted Packets

---

## ARP

Displayed MAC address resolution within the local network before IP communication.

---

# Findings

- Network connectivity was successfully verified.
- Apache server responded correctly to HTTP requests.
- SSH communication was fully encrypted.
- DNS queries resolved public domains successfully.
- ARP traffic confirmed Layer 2 communication.
- Wireshark successfully captured and categorized all generated traffic.

---

# Skills Demonstrated

- Network Traffic Analysis
- Packet Capture
- Wireshark
- Protocol Analysis
- TCP/IP
- HTTP Analysis
- DNS Analysis
- ICMP Analysis
- SSH Analysis
- ARP Analysis
- Endpoint Analysis
- Conversation Analysis
- Linux Administration
- Ubuntu Server
- Kali Linux
- VMware Workstation
- SOC Investigation
- Blue Team Fundamentals

---

# Conclusion

This project provided practical experience in capturing and analyzing network traffic using Wireshark. It demonstrates the ability to identify common network protocols, inspect packet exchanges, analyze endpoint communications, and apply display filters to investigate network activity.

The skills demonstrated in this project align with the daily responsibilities of a Security Operations Center (SOC) Analyst and provide a strong foundation for network-based security investigations.
