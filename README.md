# Mustafa Ahmed Gomaa

Cybersecurity & Networks undergraduate at Egypt-Japan University of Science and Technology (EJUST, '27).  
Focused on Blue Team operations, detection engineering, threat intelligence, and applied cryptography.

[LinkedIn](https://www.linkedin.com/in/lumidren/) · [TryHackMe](https://tryhackme.com/p/MustafaGomaa) · [Email](mailto:mustafagomaa.edu@gmail.com)

---

### Background

I spend most of my time working on network telemetry, building security utilities, and analyzing adversary techniques. During the summer of 2026, I interned in the Security Operations Center (SOC) at Commercial International Bank (CIB Egypt), triaging production alerts, correlating multi-source logs, and following threat-hunting playbooks across enterprise SIEMs.

Currently researching Explainable AI (XAI) applied to IoT device behavioral anomaly detection for my undergraduate thesis.

---

### Projects & Research

#### [CIPHER](https://github.com/lumidren) — SOC Threat Intelligence Platform (2025)
A full-stack threat intelligence platform built to assist analysts with IOC enrichment and campaign tracking.
* **Architecture:** Flask backend exposing REST endpoints; lightweight vanilla JS frontend.
* **Enrichment:** Integrated VirusTotal and AbuseIPDB APIs for automated IP, domain, and file hash reputation scoring.
* **Data Standards:** Native STIX 2.1 JSON export for intelligence sharing with external platforms.
* **Visualization:** Interactive D3.js force-directed graph mapping relationships between indicators, threat actors, and infrastructure.
* **Security:** Implemented Blowfish encryption for sensitive intelligence cached at rest.

#### GUARDIAN — Explainable IoT Anomaly Detection (2025–2027)
*Undergraduate Thesis: Explainable Behavioral Identity for IoT Security Monitoring.*
* **Detection Engine:** Unsupervised Isolation Forest model trained on 60 statistical network features extracted per 10-second sliding window.
* **Edge Target:** Profiled and optimized for deployment on a Raspberry Pi 4 edge device.
* **Explainability:** Built a natural language generation (NLG) module that converts multi-feature anomaly vectors into concise, readable summaries for Tier-1 analysts rather than raw anomaly scores.
* **Mitigation:** Graduated enforcement tiers (packet throttling, VLAN quarantine, dynamic ACL pushes).

#### Secure Cloud Portal — Scratch Cryptography (2026)
A client-server secure communications portal written in pure Python without external cryptographic dependencies:
* Handcrafted implementation of the **ChaCha20** stream cipher following RFC 7539 (state matrix initialization, 20 rounds of column and diagonal quarter-round operations).
* Implemented the **ElGamal** public-key cryptosystem over finite fields for key exchange, modular exponentiation, and prime-order subgroup operations.

#### SOC Simulation & Attack Analysis Labs (2025–2026)
Hands-on investigation of 50+ enterprise attack scenarios across TryHackMe and virtualized lab environments:
* Analyzed attack telemetry covering brute force, spear-phishing, Pass-the-Hash / PsExec lateral movement, and DNS exfiltration.
* Authored Splunk SPL queries and tuned QRadar rule thresholds to filter baseline noise.
* Correlated multi-stage alerts to MITRE ATT&CK Enterprise tactics and techniques.

---

### Experience

* **Student Intern — IT & Systems** · *EJUST* (Aug 2026 – Present)  
  Worked on campus network administration, server maintenance, and internal software integration. Developed an AI academic advisor and contributed to campus navigation architecture.
* **SOC Summer Intern** · *Commercial International Bank (CIB Egypt)* (Jun 2026 – Jul 2026)  
  Participated in live enterprise banking SOC operations: alert triage, log correlation, incident documentation, and threat intelligence workflows.

---

### Technical Skills

* **SIEM & Monitoring:** Splunk (SPL, alert pipelines), IBM QRadar (AQL, offense analysis, rule tuning), FortiSIEM, FortiAnalyzer, ELK Stack
* **Networking & Protocols:** TCP/IP, Subnetting (VLSM), 802.1Q VLANs, NAT, OSPF, BGP, ACLs, AAA/RADIUS, IPSec VPN, Firewall architecture
* **Inspection & Security Tools:** Wireshark, Snort IDS, Nmap, Cisco Packet Tracer, EVE-NG
* **Languages & Scripting:** Python (automation, telemetry parsing, socket programming), Bash, JavaScript
* **Operating Systems:** Linux (Kali, Ubuntu), Windows Server, Active Directory fundamentals
* **Frameworks:** MITRE ATT&CK, Cyber Kill Chain, Diamond Model, STIX 2.1

---

### Certifications & Training

* **Fortinet:** Fortinet Certified Associate — FortiSIEM (2026)
* **Fortinet:** Fortinet Certified Associate — FortiAnalyzer (2026)
* **TryHackMe:** SOC Level 1 Path (2026)
* **TryHackMe:** Security Engineer Path (2026)
* **Cisco:** Cybersecurity Engineer — Infrastructure & Security (DEPI, 2025)
* **Cisco:** Cisco CyberOps Associate (NTI, 2025)
* **Cisco:** Cisco CCNP ENCOR (NTI, 2025)
* **Cisco:** Cisco CCNA — Routing & Switching (NTI, 2023)
* **Other:** Vulnerability Analyst & Penetration Tester (DEPI), HCIA Security (Huawei/NTI), Ethical Hacking (NTI)