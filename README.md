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
# 🛡️ Cybersecurity Lab – Phishing Email Analysis (Task 2)

This repository contains the analysis and report for **Task 2: Analyze a Phishing Email Sample** as part of the **Cybersecurity Internship** at **Elevate Labs**.

## 📌 Objective

To analyze a suspicious phishing email and identify key indicators of a phishing attack using various open-source tools.

---

## 🧪 Tools Used

- [PhishTank](https://www.phishtank.com/)
- [MXToolbox](https://mxtoolbox.com/)
- [VirusTotal](https://www.virustotal.com/)
- [WHOIS Lookup](https://whois.domaintools.com/)

---

## 🔍 Analysis Summary

The phishing email analyzed was crafted to impersonate the **SMBC Bank** and used tactics such as:
- **Spoofed email address** (`noreply@smbc-cardnb.club`)
- **Suspicious link** redirecting to a phishing domain
- **Urgent language** prompting the user to verify their account
- **Mismatched URL** that does not belong to the legitimate SMBC domain

---

## 📥 Sample Email Content

```text
Subject: [Important] Your SMBC Card Account Needs Immediate Attention

From: noreply@smbc-cardnb.club

Dear Customer,

We have detected suspicious activity in your account and have temporarily suspended access for your protection.

👉 Verify My Account: https://smbc-cardnb.club

Failure to act within 24 hours may result in permanent account suspension.

Thank you for your cooperation,  
SMBC Card Security Team

---

## 📫 Contact

*Author:* Kandi Tejasree  
*Role:* Cybersecurity Intern – Elevate Labs  
*LinkedIn:* [www.linkedin.com/in/kandi-tejasree-30a489348] 

---

> 🚨 *Disclaimer*: All scans were performed in a controlled lab environment. Unauthorized scanning of networks without permission is illegal and unethical.
> 
