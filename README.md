# Task 4: Configure Firewall Rules

## Objective
To configure and test basic firewall rules to block and allow network traffic.

## Tool Used
Windows Defender Firewall with Advanced Security

## Steps Performed
1. Opened Windows Firewall using wf.msc
2. Navigated to Inbound Rules
3. Created new rule to block TCP port 23 (Telnet)
4. Applied rule to Domain, Private, and Public
5. Named rule "Block Telnet Port 23"
6. Tested rule (telnet not available but rule created)
7. Deleted rule to restore original configuration

## Rule Details
Port Blocked: 23  
Protocol: TCP  
Action: Block connection  

## Outcome
Learned how firewall filters inbound traffic and blocks specific ports to improve security.
