# Nmap Scan Analysis Report

## Objective
To perform a host discovery and scan open services on the internal network.

## Summary
- Total Hosts Scanned: 256 (192.168.0.0/24)
- Live Hosts Found: 7
- Services Detected:
  - SSH
  - HTTP
  - SMB
  - RDP

## Key Observations
- Host 192.168.0.105 had 4 open ports including port 22 (SSH) and 3389 (RDP), which should be evaluated for proper configuration and hardening.
- Device 192.168.0.110 is running an outdated FTP service.

## Recommendations
- Disable unused services
- Patch outdated software
- Restrict SSH/RDP access to internal IPs only
