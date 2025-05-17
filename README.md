# 🛡️ Network Penetration Testing on Metasploitable Machine 🛡️

## Project Overview

In this project, I conducted network penetration testing on a Metasploitable virtual machine using Kali Linux. The primary goal was to identify security vulnerabilities and propose remediation techniques. This hands-on exercise simulates real-world cyber threats, providing practical insights into ethical hacking and cybersecurity defenses. For a detailed walkthrough, please refer to the full document.

## Project Objectives

The objectives of this project were to:

* Conduct penetration testing on the Metasploitable machine.
* Perform network scanning and reconnaissance. 🔍
* Enumerate running services. 📊
* Exploit identified vulnerabilities. 💥
* Attempt privilege escalation. 🚀
* Perform password cracking. 🔑
* Analyze security flaws and propose effective remediation strategies. 🛠️

## Project Requirements

This project required the following:

* **Attacking Machine:** Kali Linux 🐧
* **Target Machine:** Metasploitable Machine 🎯

## Tools Used

The following tools were used:

* Nmap (Network scanning) 🗺️
* Metasploit (Exploitation framework) 💣
* John the Ripper (Password cracking) 🔑

For in-depth information on these tools, please see the full report.

## Penetration Testing Steps

Here's a breakdown of the penetration testing steps I followed:

1.  **Network Scanning:** Identifying live hosts and open ports using Nmap.
    * Basic network scan to identify devices and open ports. For example, I used the command: `nmap -v 192.168.203.0/24`.
    * Scanning all port ranges to find hidden ports.
    * Detecting versions of services running on open ports.
    * Detecting the operating systems of devices on the network. 💻
2.  **Reconnaissance:** Gathering detailed information about the target system. 🕵️
3.  **Enumeration:** System information collected (IP address, OS details, MAC address, detected services & ports). 📝
4.  **Exploitation of Services:**
    * Exploiting Anonymous FTP login. 🔓
    * Exploiting Backdoor Command Execution. 🚪
5.  **Privilege Escalation:** Creating a user with root access. 👑
6.  **Cracking Password Hashes:** Cracking the password hash using John the Ripper. 🔓🔑
7.  **Remediations:**
    * Anonymous FTP Login Vulnerability.
    * Backdoor Command Execution.
    * Weak Password Vulnerability.
    * Unpatched Vulnerable Services.
    * Open & Hidden Ports Exposure. 🛠️

For detailed steps and commands, please refer to the full report.

## Key Learnings

Key takeaways from this project include:

* Understanding Ethical Hacking 👨‍💻
* Network Scanning & Reconnaissance Techniques 🔍
* Enumeration & System Information Gathering 📊
* Exploiting System Vulnerabilities 💥
* Privilege Escalation & Password Security 🚀🔑
* Remediation & Security Best Practices 🛡️
* Real-World Cybersecurity Applications 🌐

For a comprehensive understanding of these learnings, please see the complete document.

