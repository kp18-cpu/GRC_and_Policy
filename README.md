# Information Security & Policy Lab Portfolio

This repository contains a comprehensive collection of lab exercises and reports from my Information Security and Policy coursework. It demonstrates a practical understanding of various security frameworks, compliance requirements, incident response, and critical policy implementations within an organizational context.

## Labs & Projects Overview:

Each document within this portfolio showcases hands-on experience and a strong grasp of information security principles and their legal implications.

### 1. Security Concepts and Policies (Lab: Computing Security Concepts and Problems)
* **Acceptable Use Policy (AUP):** Explored and defined key aspects of an AUP, including asset ownership, network access restrictions (e.g., prohibition of VPNs, Tor, cloud sharing, WiFi adapters on company servers), and privacy expectations (e.g., continuous monitoring, company's right to access employee systems).
* **Exploitation Policy:** Understood policies regarding employee exploitation of resources, consequences of suspicious activities (immediate termination, legal action), and responsible system usage.
* **Disaster Recovery & Business Continuity:** Identified crucial aspects of disaster recovery planning, including key personnel (Senior Information Analyst, HR Manager, IT Specialist, Legal Advisors, External Managers, Crucial Contractors) and essential data for backup (client data, supply chain information, insider management, legal policies, ongoing projects, tax records). Non-essential data like temporary logs, cache, and user preferences were identified as not critical for backup.

### 2. Cryptography Fundamentals (Lab: Cryptography)
* **Apple vs. FBI Case Study:** Analyzed the differing perspectives on privacy vs. national security in the Apple-FBI case, discussing the potential market and trust implications for Apple if user privacy were compromised. Reflected on how flexibility in systems (like Android's vault apps) can introduce vulnerabilities.
* **Australian Encryption Laws:** Examined Australia's stance on encryption, arguing that companies should not be forced to create backdoors due to the inherent risk to network security. Connected this to the broader concept of technology's dual use (e.g., Tor network, blockchain for privacy vs. illegal activities).
* **Philosophical Cryptography ("To Serve Man"):** Explored the concept of hidden meanings in communication, drawing parallels to how cryptography conceals true messages, emphasizing the need for deep analysis beyond surface-level information.
* **Email Encryption with OpenPGP:** Practiced email encryption and digital signing using Thunderbird and OpenPGP, understanding the role of public and private keys in ensuring confidentiality and integrity.

### 3. Data Privacy Regulations (In-Class Exercises: Oregon, GDPR, HIPAA, FERPA, GLBA, Data Breach Policy)
* **Oregon Consumer Privacy Act:** Identified consumer information protected by the act, including biometric data used for identification. Understood the applicability of the law based on business operations within Oregon and revenue derived from selling consumer data.
* **GDPR Compliance (Croissant, Inc.):** Outlined critical GDPR compliance activities, including personal data collection, behavioral tracking, and sharing with third parties. Emphasized purpose limitation, consent requirements, and transparency in data handling. Proposed data encryption and access control for security.
* **HIPAA Compliance (HIPAASecureIsUs, Inc.):** Evaluated compliance with HIPAA Security and Privacy Rules. Identified violations such as storing PHI in plain text, insufficient backup plans, lack of robust password policies, and unauthorized sharing of patient information. Proposed solutions including encryption, regular password changes, backup procedures, and enhanced access controls.
* **FERPA Compliance:** Understood FERPA's role in protecting student education records and the implications of making such information publicly accessible. Learned when it is permissible for school officials to access student records (legitimate educational interest) and the importance of written consent for disclosure.
* **GLBA Compliance:** Examined key questions for WISP (Written Information Security Plan) compliance under GLBA, covering data breach response, system inventory, secure disposal of decommissioned systems, protection of PII, and third-party vendor assessment.
* **Wisconsin Data Breach Policy:** Summarized the Wisconsin statute requiring entities to notify individuals of unauthorized acquisition of personal information. Defined "personal information" protected by the statute (e.g., SSN, driver's license, financial account numbers, DNA, biometric data).

### 4. Incident Response & Security Tools (Lab: Exploits and Exploiting, Lab: Attacks and Mitigation)
* **Incident Response Capabilities:** Researched and compared various cybersecurity companies' incident response services, highlighting their strengths in areas like forensic investigation, threat intelligence, and global reach (e.g., FireEye, Cisco).
* **Ransomware & Data Breach Response:** Emphasized the importance of a response plan, data backup, privilege control, network segmentation, and readiness testing for ransomware incidents.
* **Metasploit Framework:** Used Metasploit for vulnerability exploitation and post-exploitation. Demonstrated setting up listeners, executing payloads (e.g., `windows/x64/meterpreter/reverse_tcp`), and gathering system information (`sysinfo`, `idletime`, `arp`, `ifconfig`, `netstat`, `route`, `shell`).
* **Keystroke Sniffing:** Employed `keyscan_start` and `keyscan_dump` to capture user keystrokes, demonstrating a critical offensive technique for credential harvesting.
* **Netcat (ncat):** Utilized `ncat` for basic network communication, including setting up listeners and transferring text.
* **Hping3:** Explored `hping3` for crafting custom TCP/IP packets to test firewalls, perform advanced port scanning, and even encapsulate data for transfer. Demonstrated ICMP and UDP modes, and observed how firewalls respond.
* **Scapy:** Used Scapy for advanced packet crafting and manipulation, illustrating its capabilities in sending custom ICMP and TCP packets.

### 5. Cybersecurity in Action (Movie Analysis)
* **"Blackhat" (2015) Analysis:** Explored various cybersecurity concepts depicted in the movie, such as infrastructure protection (power grids, transit networks via PLCs), sponsored cyber threats (nation-state actors), malware design and deployment (infected USBs, hypervisor bootkits, rootkits, backdoors), network intrusion and lateral movement, insider threats (RFID badge cloning, fingerprint copying), and operational security (anti-forensics, proxy bouncing, burner devices). Also noted the use of Kali Linux as a hacking tool.

## Demonstrated Skills:

* **Policy Development & Analysis:** Ability to interpret and apply complex regulatory frameworks (GDPR, HIPAA, FERPA, GLBA, MA Data Protection Laws, PIPEDA, NY SHIELD Act) to real-world scenarios.
* **Incident Response Lifecycle:** Understanding of preparation, detection, analysis, containment, eradication, and recovery phases of incident response.
* **Vulnerability Assessment & Exploitation:** Practical experience with penetration testing tools like Metasploit, Ncat, Hping3, and Scapy for identifying and exploiting system weaknesses.
* **Digital Forensics Fundamentals:** Core knowledge of digital evidence handling, data acquisition (disk imaging, memory acquisition), and artifact analysis (Registry, system logs).
* **System Hardening:** Understanding of password policies, firewall configuration (stateful packet inspection), and user/group management for securing systems.
* **Threat Intelligence & Analysis:** Ability to analyze various cyber threats (malware types, social engineering, DoS/DDoS) and their impact.
* **Legal & Ethical Considerations:** Awareness of the legal ramifications of data breaches and the ethical responsibilities in cybersecurity investigations.

This repository reflects my commitment to mastering the multifaceted domain of Information Security and Policy, integrating theoretical knowledge with practical application.
