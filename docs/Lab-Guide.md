# Lab Guide

## Objective

The purpose of this lab is to capture and analyze network traffic using Wireshark by generating common network protocols in an isolated virtual environment.

---

## Lab Environment

| Component | Description |
|-----------|-------------|
| Hypervisor | VMware Workstation |
| Attacker Machine | Kali Linux |
| Target Machine | Ubuntu Server |
| Packet Analyzer | Wireshark |
| Web Server | Apache2 |
| Remote Access | OpenSSH |

---

## Network Configuration

| Device | IP Address |
|--------|------------|
| Kali Linux | 192.168.81.128 |
| Ubuntu Server | 192.168.81.129 |

Network Range:

```
192.168.81.0/24
```

---

## Services Enabled

- Apache2
- OpenSSH Server

---

## Traffic Generated

- ICMP (Ping)
- HTTP (curl)
- HTTP (wget)
- DNS (nslookup)
- SSH
- TCP
- ARP

---

## Capture Information

- Interface: ens33
- Capture Tool: Wireshark
- File Format: PCAPNG

---

## Expected Learning Outcomes

- Capture live network traffic.
- Understand packet flow.
- Analyze network protocols.
- Apply Wireshark filters.
- Identify endpoints and conversations.
- Practice SOC network investigations.
