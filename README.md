# Firewall Configuration Assignment (Task 4)

## Overview
This project demonstrates basic firewall configuration using Windows Firewall / UFW on Linux. The goal was to block and allow specific ports, test functionality, and understand how firewalls filter network traffic.

---

## Steps Performed

### 1. Open Firewall Configuration Tool
- Windows: Searched for “Windows Defender Firewall with Advanced Security.”
- Linux: Used the terminal with UFW.

### 2. Listed Current Firewall Rules
Viewed existing inbound and outbound rules to understand default settings.

### 3. Added Rule to Block Port 23 (Telnet)
- Windows: Created a new inbound rule → Port → TCP → 23 → Block the connection.
- Linux: `sudo ufw deny 23`

### 4. Tested the Rule
Used Telnet to test:
The connection failed, confirming the block.


### 6. Removed the Test Rule
Deleted the Telnet block rule to restore the original firewall configuration.

### 7. Documented Steps Used
Recorded GUI steps on Windows and commands on Linux.

### 8. Summary of Firewall Filtering
A firewall filters traffic based on rules. It checks each packet and either allows or blocks it depending on defined policies.

---

## Key Concepts
- Firewall rules  
- Inbound vs outbound traffic  
- Port blocking  
- UFW / Windows Firewall  
- Traffic filtering  

---

## Conclusion
This exercise provided hands-on experience with firewall management and taught how ports and traffic can be controlled to secure a system. I learned how to create, test, and remove rules, and gained a deeper understanding of network protection.


