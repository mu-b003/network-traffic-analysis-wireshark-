# Wireshark Analysis

## Capture File Properties

| Item | Value |
|------|-------|
| File Size | 280 KB |
| Total Packets | 1370 |
| Capture Duration | 10 Minutes 58 Seconds |
| Average Packets/Second | 2.1 |
| Average Bit Rate | 2835 bits/s |

---

## Protocol Hierarchy

The captured traffic contained the following protocols:

- IPv4
- TCP
- SSH
- HTTP
- DNS
- ICMP
- ARP

TCP represented the largest percentage of captured traffic due to the SSH session and HTTP communication.

---

## Endpoints

Most active hosts:

| IP Address | Description |
|------------|-------------|
| 192.168.81.128 | Kali Linux |
| 192.168.81.129 | Ubuntu Server |

Additional external IP addresses were observed during DNS and system connectivity operations.

---

## Conversations

The largest communication occurred between:

```
192.168.81.128

↓

192.168.81.129
```

Statistics:

- Approximately 1121 packets
- Approximately 197 KB
- Duration approximately 503 seconds

---

## Display Filters

### ICMP

Used to analyze Ping requests and replies.

---

### HTTP

Displayed GET requests and HTTP responses.

---

### DNS

Displayed domain name resolution traffic.

---

### TCP

Displayed connection establishment, data transfer, and connection termination.

---

### SSH

Displayed encrypted SSHv2 communication and key exchange.

---

### ARP

Displayed address resolution requests and responses within the local network.
