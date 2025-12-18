# CTF Labs – Ethical Hacking & Exploitation

## Overview
This repository contains **two Capture The Flag (CTF) labs** focused on applying **ethical hacking methodologies** to identify, exploit, and analyze vulnerabilities in a deliberately vulnerable Linux machine. The labs follow a structured penetration testing workflow covering **reconnaissance, enumeration, exploitation, and post-exploitation**.

## Labs Included
- **CTF Lab 1 (Lab 6): Initial Compromise & Enumeration**
- **CTF Lab 2 (Lab 7): Exploitation & Post-Exploitation**



---

## Lab 1: Initial Compromise & Enumeration
**Focus Areas:**
- Network discovery using `netdiscover`
- Service and port scanning with `nmap`
- Web enumeration using `dirb`
- Discovery of exposed backup files
- Password cracking using `fcrackzip` and `rockyou`
- Credential extraction from configuration files
- Initial exploitation of Apache Tomcat using Metasploit

**Key Outcome:**  
Successful access to the system via compromised Tomcat credentials and establishment of a Meterpreter session.

:contentReference[oaicite:1]{index=1}

---

## Lab 2: Exploitation & Post-Exploitation
**Focus Areas:**
- Reuse of compromised credentials for deeper access
- Exploitation of Apache Tomcat using `tomcat_mgr_upload`
- Privilege escalation through misconfigured binaries
- Extraction of `/etc/shadow` hashes
- Password cracking using `John the Ripper`
- Discovery of users, credentials, and root-level access
- Capture of the root flag

**Key Outcome:**  
Complete system compromise demonstrating the impact of weak credentials, poor access controls, and insecure configurations.

:contentReference[oaicite:2]{index=2}

---

## Tools & Techniques Used
- `netdiscover`, `nmap`
- `dirb`, `fcrackzip`
- Metasploit Framework
- `john` (John the Ripper)
- SSH
- Linux privilege escalation techniques

---

## Learning Outcomes
- Practical understanding of penetration testing phases  
- Hands-on experience with real-world attack tools  
- Insight into how small misconfigurations lead to full system compromise  
- Reinforcement of secure system design principles  

---

## Project Type
**Ethical Hacking | Capture The Flag (CTF) | Network & System Security | Academic Labs**

---

## Disclaimer
These labs were conducted in a **controlled academic environment** for learning purposes only.  
Do **not** attempt these techniques on systems without explicit authorization.
