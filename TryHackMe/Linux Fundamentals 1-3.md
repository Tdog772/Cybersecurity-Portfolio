# TryHackMe: Linux Fundamentals 1-3

## Overview
Developing the basics of Linux Operating System, commands, terminal control, SSH protocol, 

## Objectives
- Learn essential -> advanced commands
- Master command control in Linux terminal
- Logging in through SSH
- Develop Linux directory navigation

## Skills Practiced
- File Navigation
- User Discovery
- Remote Access
  
## Key Concepts Learned

### Essential Command List
- <i>whoami</i>: tells you who you are on the system
- <i>echo</i> [text]: output specific text applied
- <i>ls</i>: list what is in the current folder
- <i>cd</i> [directory]: change directory
  - <i>cd ..</i> : return to previous directory
- <i>cat</i> [file]: show contents of a file
- <i>pwd</i>: print working directory
- <i>find -name</i> [file]: search for files by name
- <i>grep</i> [text] [file]: searches inside file for text

### Combining Commands
- [command] & [command]: runs two commands at once, better for commands that take lonnger
- [command] && [command]: waits for first command to complete before running the subsequent command
- [command] > [file]: take output of command and send it to a file, overwrites anything in the file
- [command] >> [file]: take output of command send it to a file without overwriting

### Secure Socket Shell (SSH)
Protocol that lets devices talk securely over a network. <br>
Requires the IP address and account information of the remote device (username/password). <br>
Example command - ssh [username]@192.168.10.1 <br>
Enter the password and accept 

### Arguments
Extra options to a command appended usually with a hyphen. <br>
Examples: 
- <i>ls -a</i>: list hidden files/folders
- [command]<i>--help</i>: list all possible argument options for a command
- <i>man</i> [command]: full manual style report of a command

### File management commands
- <i>touch</i> [new file name]: create a new file
- <i>mkdir</i> [new folder name]: create a new folder
- <i>rm -R</i> [file name]: remove a file
- <i>cp</i> [file name] [file name]: copy first file to the next
- <i>mv</i> [file name] [file name]:

### Common Directories
Form example: /home/tryhackme/Documents
- /etc: commonplace location for Linux system and programs files
- /var: stores data that services and app write to or read 
  - includes /log
- /root: home directory of root user
- /tmp: stores temporary data, usually only accessed once or twice

### Permissions
Certain users can access certain files and folders.
ls -l lists a directory's files and which groups can:
- r: read (open)
- w: write (make changes)
- x: execute (run, specific to apps and scripts)
A file can have a specific owner, but a <b>group</b> of users can be assigned with specific permissions.
<i>su</i> is used to switch user as long as you have access and the password associated with the username.

## Tools Used
- Linux Terminal
- TryHackMe Lab Machine
- TryHackMe AttackBox

## Security Relevance
Linux OS is used in the majority of servers and tools worldwide. Understanding how to manage, navigate, and secure a Linux system is essential for a number of tools (Splunk, Wireshark, nnamp, Snort, etc) and rapid scripting. <br>
SSH is a foundational method of encrypted remote access.

## Reflection

## Date Completed

November 9, 2026
