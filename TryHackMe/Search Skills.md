# TryHackMe: Search Skills

## Overview
Introduction to multiple online sites and specialized tools to prepare for threat hunting and virus detection.

## Objectives
- Efficiently search the internet.
- Use specialized services and technical documentation

## Skills Practiced
- Open Source Intelligence (OSINT)
- Specialized Search Engines

## Key Learning

### <a href="https://www.shodan.io/" target="_blank" rel="noopener noreferrer">Shodan</a>
- An online tool that continuously searches internet-connected devices, servers, and networks to see what is running and its location.
- Contains query filters to narrow down searches by country, port, organization, and/or hostname.
- TryHackMe Example: Apache servers (a widely used open-source web server technology) to find IP address: 185.243.115.47.
  - Domain related: tryhackme.thm
  - Region: Amsterdam, Netherlands
  - Ports: 22 (Secure Shell/SSH), 80 (Hypertext Transfer Protocol/HTTP), 443 (HTTP Secure/HTTPS), 8080 (Alt HTTP)
  - ASN (Autonomous System Number): AS14061

### VirusTotal
- An online database of saved domains, IP addresses, and file hashes flagged for malicious behavior.
- Every query tested by over 70 antivirus engines and web scanners.
- Example used: 
