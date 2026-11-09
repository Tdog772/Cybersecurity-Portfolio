# TryHackMe: Introduction to Security Information and Events Management System

## Overview
Learning the fundamentals of SIEM, including its features and functionality.

## Objectives
- Understand different types of log sources
- Recognize the importance and explore the features of SIEM solutions
- Understand the process behind alerts and alert analysis

## Skills Practiced
- Log management
- Alert analysis
- Suspicious pattern recognition
- Data correlation

## Key Concepts Learned

### Log Sources
Host-Centric and Network-Centric
- Host-Centric include: User action, process execution, registry key/value, and PowerShell execution.
- Network-Centric include: SSH connection, FTP transfer, web traffic, VPN, and network file sharing.
There are hundreds of logs per second from everywhere, humans cannot realistically follow them all.

### Usage of SIEM
SIEM centralizes the thousands of logs, standardizes the format, and correlates the information for analysts to follow.
Main features include:

- Easier management of logs: Centralization, format standardization, and information correlation make logs simpler to manage and follow.
- Real-time alerting: Many rules (natural or added based on the organization and specific tool) check logs for clear  evidence like unknown sources or potentially malicious payloads. These can be immediately alarmed to analysts faster than any human would notice.
- Dashboards: The summary of multiple fields of analysis are found in a SIEM's dashboard. This system increases the speed of responses and increases the effectiveness of an organization's security by several magnitudes.

### Real Examples of Log Sources

#### Windows Machine
Event Viewer contains all the logs each with a unique assigned ID.

#### Linux Machine
Linux OS stores logs under the file direction "/var/log" with several locations that hold more specialized logs.
- /httpd: HTTP Request/Response and error logs
- /auth.log | /secure for authentication-related logs
- /kern for kernel related events

### Alerting Process
Creating detection rules based on frequent malicious activity is essential to SIEM alerts.
Examples:
- 5 failed login attempts within a certain period - Raise alert: Multiple Failed Login Attempts
- Alert set when a USB drive is plugged into any device
- If outbound traffic >25 mb, alert in case of data exfiltration
Main checks for dectection
- EventID - Specific action taken in a log
- Source/Destination - Unusual activity from unknown source or to server
- Commands - After privilege escalation, adversaries may make usage of commands that should be checked
Alert types:
- True Positive: Malicious activity and flagged (the real effort)
- False Positive: Normal activity and flagged (time waster)
- True Negative: Normal activity and ignored (noise)
- False Negative: Malicious activity and ignored (most dangerous)

## Practical Lab Scenario in TryHackMe
<img width="460" height="490" alt="image" src="https://github.com/user-attachments/assets/81304565-c1c4-4300-b4d1-25fdd4cb34b0" />
A typical SIEM dashboard.




## Tools Used
- TryHackMe SIEM Dashboard

## Security Relevance
SIEM and its iterations (Splunk, Microsoft Sentinel) is the basis for the majority of SOC analysts.
Learning how to follow logs to their source, discover their risks, and respond to malicious action are essential skills. 

## Reflection
This room developed my understanding of what SIEM is, how it assists SOC analysts in the understanding of logs, and the simplicity of its dashboard visibility.

## Date Completed

November 9, 2026
