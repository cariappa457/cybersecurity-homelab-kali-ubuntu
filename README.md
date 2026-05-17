# cybersecurity-homelab-kali-ubuntu
Hands-on cybersecurity lab for vulnerability assessment, network scanning, web enumeration, packet analysis, and log monitoring using Kali Linux and Ubuntu Server.
# Cybersecurity Homelab Project

## Overview
Built a virtualized cybersecurity lab using Kali Linux and Ubuntu Server in VMware. This project simulates real-world penetration testing and security monitoring scenarios.

## Lab Architecture
Kali Linux (Attacker)
↓
Nmap / Nikto / Gobuster / SSH / Wireshark
↓
Ubuntu Server (Target)
↓
Apache Logs + SSH Authentication Logs

## Tools Used
- Nmap
- Nikto
- Gobuster
- Wireshark
- SSH
- VMware Workstation
- Kali Linux
- Ubuntu Server

## Activities Performed

### 1. Network Reconnaissance
Performed service and port discovery:

```bash
nmap -sV TARGET_IP
```

### 2. SSH Enumeration
Verified remote access and privilege escalation.

### 3. Web Vulnerability Assessment
Performed web scanning using Nikto.

### 4. Directory Enumeration
Discovered hidden directories using Gobuster.

### 5. Traffic Analysis
Captured and analyzed traffic using Wireshark.

### 6. Log Analysis
Reviewed:
- /var/log/auth.log
- /var/log/apache2/access.log

## Key Findings
- Open SSH service discovered
- Apache version disclosure
- Missing HTTP security headers
- Directory exposure discovered
- Successful attack activity observed in logs

## Skills Demonstrated
- Linux administration
- Network scanning
- Vulnerability assessment
- Web enumeration
- Security log analysis
- Basic incident investigation
