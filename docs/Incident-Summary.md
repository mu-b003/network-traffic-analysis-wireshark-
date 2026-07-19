# Incident Summary

## Overview

This project focuses on analyzing normal network activity generated inside an isolated virtual laboratory using Wireshark.

No malicious activity was intentionally introduced. Instead, different types of legitimate traffic were generated to practice packet analysis and protocol identification.

---

## Traffic Generated

- ICMP Ping
- HTTP Requests
- DNS Queries
- SSH Session
- TCP Connections
- ARP Requests

---

## Key Findings

- Successful communication between Kali Linux and Ubuntu Server.
- Apache web server responded correctly to HTTP requests.
- SSH traffic was encrypted using SSHv2.
- DNS queries successfully resolved public domains.
- ICMP Echo Requests and Replies confirmed network connectivity.
- ARP packets resolved MAC addresses before IP communication.

---

## Security Observations

- SSH provided encrypted remote access.
- HTTP traffic remained unencrypted and visible.
- DNS traffic exposed requested domain names.
- ARP traffic demonstrated Layer 2 address resolution.

---

## Conclusion

The packet capture successfully demonstrates how common network protocols appear in Wireshark and provides hands-on experience in network traffic analysis.

This lab strengthens essential SOC Analyst skills, including packet inspection, protocol identification, endpoint analysis, conversation tracking, and Wireshark filtering.
