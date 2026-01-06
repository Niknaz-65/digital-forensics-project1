# Network Intrusion Analysis – Web Server Compromise

![Project 1 Cover](digital-forensics-project1-cover.png)

## Overview
Forensic analysis of a simulated network intrusion targeting a vulnerable IIS web server.  
The investigation focuses on reconnaissance activity, exposed credentials, and server misconfiguration leading to unauthorized access.

## Why This Project Matters to SOC Teams
- Demonstrates early-stage intrusion detection through web server artifacts
- Shows how misconfigurations expose credentials and expand attack surface
- Supports investigation of initial access techniques and remediation actions

## Environment
- OS: Linux (attacker), Windows Server (victim)
- Data Sources: IIS logs, web directory listings
- Tools: Dirb, Nmap, Nikto, CyberChef
- Frameworks: DFIR investigation workflow

## Data Collected / Artifacts
- Web server directory enumeration results
- IIS configuration artifacts
- Base64-encoded credential exposure
- User and group account information
- Indicators of Compromise (IOCs)

## Analysis Steps
1. Performed reconnaissance against the IIS server using Dirb and Nmap
2. Identified exposed directories and insecure web configuration
3. Extracted and decoded Base64-encoded credentials
4. Verified user access and privilege implications
5. Assessed server misconfiguration and attack impact

## Findings
- IIS misconfiguration exposed sensitive directories
- Base64-encoded credentials revealed valid user information
- Reconnaissance activity confirmed attacker visibility into server structure
- Misconfigurations increased likelihood of unauthorized access

## Outcome
- Initial access vector identified and documented
- Credential exposure confirmed
- Recommended IIS hardening and access control remediation
- Suggested monitoring for web reconnaissance activity

## Evidence
- Screenshots and artifacts stored in `/images`
- Full investigation available as PDF

## Project Files
- `Digital-Forensics-Project1-Network-Intrusion.pdf`
- `/images`

## Skills Demonstrated
- Network intrusion investigation
- Web server forensics
- Credential exposure analysis
- Reconnaissance detection
- Evidence-based reporting

## Author
**Niknaz Sadehvandi**  
**Cybersecurity Analyst**
