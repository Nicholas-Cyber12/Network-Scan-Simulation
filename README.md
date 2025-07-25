# Network Scan Simulation - Nmap Practice

**Author**: Nicholas Mabaso

## Description
This project simulates a basic cybersecurity task: discovering hosts and open services within a small office network using Nmap. It demonstrates foundational knowledge of network reconnaissance, a key skill in penetration testing and vulnerability assessment.

## Objectives
- Identify active hosts
- Discover open ports
- Determine running services
- Practice safe enumeration techniques

## Tools
- Nmap
- Windows CMD / Git Bash / Linux Terminal

## Commands Used
```bash
# Ping scan entire subnet
nmap -sP 192.168.0.0/24

# SYN scan + service detection
nmap -sS -sV 192.168.0.105

# OS detection and aggressive scan
nmap -A 192.168.0.105

# Output Samples
Full network scan saved to scans/full-network-scan.txt

Targeted host scan saved to scans/targeted-scan.txt

# Report
Find the analysis in reports/nmap-analysis-report.md
