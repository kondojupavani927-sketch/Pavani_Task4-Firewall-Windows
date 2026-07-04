# Task 4: Setup and Use Firewall on Windows

**Name:** Pavani Kondoju  
**Date:** 04-04-2026  
**Task:** Block port 23 using Windows Firewall inbound rule

## Objective
Learn to configure Windows Defender Firewall to block/allow network traffic.

## Steps Done
1. Opened Windows Firewall with Advanced Security `wf.msc`
2. Created Inbound Rule to block TCP port 23 - Telnet
3. Tested with command: `telnet localhost 23` → Got "blocked by rule" error
4. Verified port 80 still works: `telnet localhost 80` → Connected
5. Deleted rule for cleanup

## Screenshots
All screenshots with captions are in the Word document: `Pavani_Telnet_Firewall_Lab.docx`

## Commands Used
`telnet localhost 23` - Test blocked port
`telnet localhost 80` - Test allowed port

## Conclusion
Learned how firewall inbound rules work and how to block specific ports for security.
