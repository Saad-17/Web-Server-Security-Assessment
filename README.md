# Web-Server-Security-Assessment
A hands-on web server security assessment focusing on enumeration and misconfiguration analysis.

# Web Server Security Assessment (Port 80)

## Overview
This project demonstrates a hands-on security assessment of a web server running Apache HTTP Server.
The focus of this assessment is enumeration, misconfiguration analysis, and risk evaluation within a controlled lab environment.

## Target Environment
- Web Server: Apache HTTP Server 2.2.8
- Service: HTTP
- Port: 80
- Environment: Virtual Lab (Educational Purpose Only)

## Methodology
The assessment followed a standard penetration testing methodology:
- Service discovery and version detection
- Web vulnerability scanning
- Directory enumeration
- Manual verification of findings
- Risk analysis and remediation recommendations

## Tools Used
- Nmap
- Nikto
- Dirb

## Key Findings
- Insecure WebDAV configuration
- Directory listing enabled
- Outdated Apache version
- Exposed administrative paths

## Disclaimer
This project was conducted in a controlled lab environment for educational purposes only.
No real-world systems were targeted.

## Screenshots

The following screenshots demonstrate key stages of the assessment process:

- Nmap service and version detection
- Nikto web vulnerability scanning
- Dirb directory enumeration
- WebDAV directory exposure
