# Analyze-a-Phishing-Email-Sample.

# Network Port Scanner using Nmap

# Objective
Scan local network to identify open ports and services.

# Tools Used
- Nmap
- Wireshark (optional)
- 
# Command Used
nmap -sS 192.168.1.0/24

# Output
PORT     STATE SERVICE
80/tcp   open  http
22/tcp   open  ssh

# Risks Identified 
- Open ports expose services
- Possible unauthorized access




# Scan Report

## Network Range
192.168.1.0/24

## Findings
- Device 1: Port 80 (HTTP) open
- Device 2: Port 22 (SSH) open

## Risk Analysis
- HTTP is insecure
- SSH may be vulnerable to brute force

## Conclusion
Network has open ports that need monitoring.

