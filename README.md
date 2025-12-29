# dns-icmp-incident-analysis-## DNS & ICMP Incident Analysis

This repository contains a simulated cybersecurity incident report analyzing DNS and ICMP traffic.
The incident involved repeated DNS failures due to an unreachable UDP port 53, identified using tcpdump.

### Skills Demonstrated
- Network traffic analysis
- DNS troubleshooting
- ICMP error interpretation
- Incident documentation

This project is based on a training scenario and does not involve real production systems.

### Sample tcpdump Output

```text
IP 192.51.100.15.XXXXX > 203.0.113.2.53: UDP, length 36
ICMP 203.0.113.2 udp port 53 unreachable
