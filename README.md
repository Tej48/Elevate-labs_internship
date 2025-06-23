# 🔍 Network Scanning Task – Elevate Labs Internship

This repository contains the documentation and analysis for *Task 1* of the *Cybersecurity Internship* at *Elevate Labs. The task involved scanning a local network for open ports, identifying active services, and assessing potential security risks using industry-standard tools such as **Nmap* and *Wireshark*.

---

## 📄 Task Overview

*Objective:*  
To discover open ports and active devices within the local network and analyze possible security risks using tools like Nmap and Wireshark.

*Tools Used:*
- [Nmap](https://nmap.org/)
- [Wireshark](https://www.wireshark.org/)

*Operating System:* Linux  
*Local IP Range Scanned:* 192.168.183.0/24

---

## 📌 Task Steps

1. ✅ Installed Nmap using terminal.
2. ✅ Determined local IP range using ifconfig.
3. ✅ Executed TCP SYN scan using nmap -sS 192.168.183.0/24.
4. ✅ Noted IP addresses and open ports.
5. ✅ Captured and analyzed packets using Wireshark.
6. ✅ Researched common services found on scanned ports.
7. ✅ Identified potential security risks and recommended mitigations.

---

## 🧠 Key Findings

| Port | Protocol | Service     | Risk Summary |
|------|----------|-------------|--------------|
| 135  | TCP      | msrpc       | DCOM/RPC attack vector |
| 139  | TCP      | netbios-ssn | Malware/lateral movement |
| 445  | TCP      | microsoft-ds| SMB vulnerabilities |

---

## 📎 Files Included

- Network_Scanning_Task_with_Cover.docx: Full task documentation with professional formatting and cover page.

---

## 🛡 Conclusion

This task provided practical exposure to active and passive network scanning techniques, and emphasized the importance of regularly auditing internal systems. Tools like Nmap and Wireshark prove essential for early detection of vulnerabilities in network services.

---

## 📫 Contact

*Author:* Kandi Tejasree  
*Role:* Cybersecurity Intern – Elevate Labs  
*LinkedIn:* [www.linkedin.com/in/kandi-tejasree-30a489348] 

---

> 🚨 *Disclaimer*: All scans were performed in a controlled lab environment. Unauthorized scanning of networks without permission is illegal and unethical.
