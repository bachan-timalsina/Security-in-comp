# 🔐 Brute Force Attack Simulation – Cyber Security in Computing

This project demonstrates a **brute force attack** against a vulnerable **Windows 7** system using the **Telnet** protocol, performed in a safe and controlled virtual environment. The report was developed as part of the **Cyber Security in Computing (CC5009NI)** module, Autumn 2024–25.

## 📌 Project Summary

This coursework explores how attackers can exploit weak remote access services, like Telnet, through brute force techniques. It also outlines mitigation strategies to prevent such attacks, emphasizing the importance of strong cybersecurity practices.

## 🧠 Key Concepts

- Brute Force Attacks
- Telnet Vulnerability
- Penetration Testing
- Ethical Hacking
- Post-Exploitation Access
- Network Reconnaissance
- Cybersecurity Mitigation Techniques

## 🎯 Aim & Objectives

**Aim:**  
To simulate a brute force attack on a Windows 7 machine using Telnet and demonstrate effective mitigation strategies.

**Objectives:**
- Perform reconnaissance using Bettercap and Nmap
- Execute a brute force attack using Hydra
- Analyze the impact of insecure protocols
- Propose and evaluate multiple mitigation strategies

## 🛠️ Tools Used

| Tool         | Purpose                                      |
|--------------|----------------------------------------------|
| Kali Linux   | Attacker machine with pentesting tools       |
| Windows 7    | Victim machine (vulnerable to brute force)   |
| VirtualBox   | Host for both virtual machines               |
| Bettercap    | Network reconnaissance                       |
| Nmap         | Port scanning and service detection          |
| Hydra        | Brute force password attack tool             |

## 🧪 Attack Demonstration Summary

1. **Reconnaissance:** Identify victim's IP and open ports using Bettercap & Nmap.
2. **Vulnerability Analysis:** Telnet (port 23) was found unprotected and active.
3. **Attack Execution:** Brute force credentials using `hydra` and a custom password list.
4. **Post-Exploitation:** Remote access to victim achieved; attacker lists/view files via Telnet.

## 🛡️ Mitigation Strategies

- ✅ Disable Telnet and use SSH
- ✅ Enable Windows Firewall
- ✅ Enforce strong password policies
- ✅ Enable account lockout policies
- ✅ Monitor logs using tools like OSSEC, Snort, and Splunk
- ✅ Implement Intrusion Prevention Systems (IPS)

## 📚 Case Study Reference

🔍 **Dunkin' Donuts Credential Stuffing Attack**  
Credential reuse and weak password management enabled attackers to access customer accounts and misuse reward points. Highlights the importance of MFA and rate limiting.

## 📁 Folder Structure Suggestion

```bash
.
├── report.pdf
├── screenshots/
│   ├── bettercap.png
│   ├── nmap-scan.png
│   ├── hydra-attack.png
│   └── telnet-access.png
├── password-list.txt
├── README.md
└── references.bib
👨‍💻 Team Members
Bachan Timalsina – ID: 23047401

Satvisha Panta – ID: 23047457

Shrevika Khadka – ID: 23047446

✅ Status
📅 Submitted: 12 May 2025
📝 Word Count: 4009

📜 References
All references cited in the report (e.g., OWASP, Bettercap.org, Medium, Reuters, etc.) can be found at the end of the PDF document or in this BibTeX/Reference file if uploaded.
