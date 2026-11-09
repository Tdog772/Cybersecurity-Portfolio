# TryHackMe: Introduction to System Information and Events Management System

## Overview
Learning the fundamentals of SIEM, including its features and functionality.

## Objectives
- Understand different types of log sources
- Recognize the importance and explore the features of SIEM solutions
- Understand the process behind alerts and alert analysis

## Skills Practiced
- g

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
- Event Viewer contains 


## Tools Used

## Security Relevance
SIEM and its iterations (Splunk, Microsoft Sentinel) is the basis for the majority of SOC analysts.
Learning how to follow logs to their source, discover their risks, and respond to malicious action are essential skills. 

## Reflection

## Date Completed

November 9, 2026
