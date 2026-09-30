# Network Scanning — Evidence Summary

Target: localhost / 127.0.0.1.

Command: `nmap -sV -sC -p- --min-rate=1000 -T4 localhost`

Observed services in the supplied evidence:
- 2024/tcp — tcpwrapped
- 2025/tcp — tcpwrapped
- 8080/tcp — HTTP, Python SimpleHTTPServer 0.6

The 8080 service was deliberately started for the exercise. Full findings and recommendations are in `Network_Scanning_Report.docx`.
