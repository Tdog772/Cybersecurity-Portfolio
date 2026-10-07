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

### <a href="https://www.virustotal.com/" target="_blank" rel="noopener noreferrer">VirusTotal</a>
- An online database of saved domains, IP addresses, and file hashes flagged for malicious behavior.
- Every query tested by over 70 antivirus engines and web scanners.
- Example used: Searched invoice_payment.exe; Found:
  - 52/72 vendors identifying the executable as malicious
  - Many referring to invoice_payment.exe as a Trojan Horse/Spyware

### Common Vulnerabilities and Exposures (CVE)
- List of publicly disclosed vulnerabilities
- Format: CVE-YEAR-NUMBER
  - Ex: CVE-2026-55182
- Common Vulnerability Scoring System (CVSS) measurements
  - Impact: Damage it can cause
  - Complexity: Difficulty of exploitation
  - Availability: Likelihood of action
- PoC (Point of Concepts): Scripts capable of proving the specific compiled vulnerability
- Example sites
  - <a href="https://www.cve.org/">MITRE CVE</a>
  - <a href="https://app.opencve.io/">Open CVE</a>
  - <a href="https://www.cvefind.com/">CVE Find</a> 
 
### Technical Documentation
- Used by every major security tool and platform, should be the first checked material
- Linux manual
  - Command: man [command]:
    - Provides the name, synopsis, description, and options for a specific linux command.
 
### Github 
- Implementing CVE-IDs into search will allow for showing of repositories
- Most often come with exploit PoCs
- Usually faster than official channels

## Tools Used
- Shodan
- VirusTotal
- CVE databases
- Linux CLI

## Reflection
The use of online tools to search and discover known malicious software and sites saves time and resources while making the jobs of threat hunters and security professionals more collaborative and efficient.

## Date Completed

October 7, 2026
