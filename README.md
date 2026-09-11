# Mustafa Ahmed Gomaa (`lumidren`)

<p align="left">
  <a href="https://github.com/lumidren">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&pause=1200&color=38BDF8&center=false&vCenter=true&width=650&lines=%E2%86%92+SOC+Analyst+T1+%7C+Incident+Detection+%26+Response;%E2%86%92+Enterprise+Banking+SOC+Intern+%40+CIB+Egypt;%E2%86%92+SIEM+Engineering+%28Splunk%2C+QRadar%2C+FortiSIEM%29;%E2%86%92+XAI+for+IoT+Behavioral+Anomaly+Detection;%E2%86%92+Pure+Python+Cryptography+%28ChaCha20+%2B+ElGamal%29" alt="Typing Prompt" />
  </a>
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/lumidren/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://tryhackme.com/p/MustafaGomaa" target="_blank">
    <img src="https://img.shields.io/badge/TryHackMe-A22846?style=flat-square&logo=tryhackme&logoColor=white" alt="TryHackMe" />
  </a>
  <a href="mailto:mustafagomaa.edu@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=lumidren&label=PROFILE%20VIEWS&color=0284c7&style=flat-square" alt="Profile Views" />
</p>

> [!NOTE]
> **Cybersecurity & Networks undergraduate** at Egypt-Japan University of Science and Technology (EJUST, '27).  
> Focused on Blue Team operations, detection engineering, threat intelligence, and applied cryptography. Formerly interned in live enterprise banking SOC operations at **CIB Egypt**.

---

### 🔬 Projects & Research

#### [CIPHER](https://github.com/lumidren) — SOC Threat Intelligence Platform
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3.js&logoColor=white)
![STIX 2.1](https://img.shields.io/badge/STIX-2.1-blueviolet?style=flat-square)
![Blowfish](https://img.shields.io/badge/Encryption-Blowfish-0284c7?style=flat-square)

A full-stack threat intelligence platform built to assist analysts with IOC enrichment and adversary campaign tracking.
* **Architecture:** Flask backend exposing REST endpoints; modular vanilla JS frontend.
* **Enrichment:** Automated IP, domain, and hash reputation scoring via **VirusTotal** and **AbuseIPDB** APIs.
* **Data Standards:** Native **STIX 2.1** JSON export for seamless threat sharing with external MISP/TIP systems.
* **Visualization:** Interactive **D3.js** force-directed graph mapping relationships between indicators, threat actors, and infrastructure.
* **Storage:** Secured cached threat intelligence at rest using **Blowfish** symmetric block cipher.

<br>

#### GUARDIAN — Explainable IoT Anomaly Detection
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Isolation Forest](https://img.shields.io/badge/ML-Isolation%20Forest-10b981?style=flat-square)
![XAI](https://img.shields.io/badge/XAI-NLG%20Summaries-8b5cf6?style=flat-square)
![Raspberry Pi](https://img.shields.io/badge/Deploy-Raspberry%20Pi%204-C51A4A?style=flat-square&logo=raspberry-pi&logoColor=white)

*Undergraduate Thesis: Explainable Behavioral Identity for IoT Security Monitoring.*
* **Detection Engine:** Unsupervised **Isolation Forest** model trained on **60 statistical network features** extracted per 10-second sliding window.
* **Edge Target:** Profiled and optimized for lightweight deployment on a **Raspberry Pi 4** edge tap.
* **Explainability:** Implemented a rule-guided Natural Language Generation (NLG) module that converts multi-feature anomaly vectors into concise, readable summaries for Tier-1 analysts rather than raw floating-point anomaly scores.
* **Mitigation:** Graduated enforcement tiers (packet throttling, VLAN quarantine, dynamic ACL pushes).

<br>

#### Secure Cloud Portal — Scratch Cryptography
![Python](https://img.shields.io/badge/Pure_Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ChaCha20](https://img.shields.io/badge/Cipher-ChaCha20-0284c7?style=flat-square)
![ElGamal](https://img.shields.io/badge/Asymmetric-ElGamal-059669?style=flat-square)
![Zero Dependencies](https://img.shields.io/badge/Crypto-Zero%20Dependencies-64748b?style=flat-square)

A client-server secure communications portal written from scratch in Python with zero external cryptographic libraries:
* **Symmetric Stream Cipher:** Handcrafted implementation of **ChaCha20** following RFC 7539 specifications (state matrix initialization, 20 rounds of column and diagonal quarter-round operations).
* **Asymmetric Cryptosystem:** Implemented **ElGamal** over finite fields for key exchange, modular exponentiation, and prime-order subgroup operations.

<br>

#### SOC Simulation & Attack Analysis Labs
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![IBM QRadar](https://img.shields.io/badge/IBM_QRadar-052FAD?style=flat-square&logo=ibm&logoColor=white)
![ELK](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-FF6600?style=flat-square)

Hands-on investigation of 50+ enterprise attack scenarios across virtualized lab environments and TryHackMe paths:
* Analyzed attack telemetry covering brute force, spear-phishing, Pass-the-Hash / PsExec lateral movement, and DNS exfiltration.
* Authored custom Splunk SPL queries and tuned QRadar rule thresholds to filter baseline noise.
* Correlated multi-stage alerts to MITRE ATT&CK Enterprise tactics and techniques.

---

### 🛠️ Technical Matrix

| Domain | Technologies & Tooling |
| :--- | :--- |
| **SIEM & Monitoring** | ![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white) ![IBM QRadar](https://img.shields.io/badge/IBM_QRadar-052FAD?style=flat-square&logo=ibm&logoColor=white) ![FortiSIEM](https://img.shields.io/badge/FortiSIEM-C82127?style=flat-square&logo=fortinet&logoColor=white) ![FortiAnalyzer](https://img.shields.io/badge/FortiAnalyzer-C82127?style=flat-square&logo=fortinet&logoColor=white) ![ElasticSearch](https://img.shields.io/badge/ElasticSearch-005571?style=flat-square&logo=elasticsearch&logoColor=white) |
| **Network & Telemetry** | ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![Snort](https://img.shields.io/badge/Snort_IDS-211A4F?style=flat-square&logo=snort&logoColor=white) ![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square&logo=nmap&logoColor=white) ![Cisco](https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white) `EVE-NG` |
| **Languages & Tooling** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Systems & Platforms** | ![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white) `Active Directory` |
| **Networking Protocols**| `TCP/IP` `Subnetting (VLSM)` `802.1Q VLANs` `OSPF` `BGP` `NAT` `IPSec VPN` `Dynamic ACLs` `AAA/RADIUS` |
| **Security Frameworks** | `MITRE ATT&CK` `Cyber Kill Chain` `Diamond Model` `STIX 2.1` `Digital Forensics` |

---

### 💼 Experience

* **Student Intern — IT & Systems** · *Egypt-Japan University of Science & Technology (EJUST)*  
  *(Aug 2026 – Present · Alexandria, Egypt)*  
  Active Directory administration, campus network operations, and internal software integration. Developed an AI-powered Academic Advisor system and contributed to campus navigation architecture.

* **SOC Summer Intern** · *Commercial International Bank (CIB Egypt)*  
  *(Jun 2026 – Jul 2026 · Alexandria, Egypt)*  
  Participated in enterprise banking Tier-1 SOC operations: monitored telemetry, triaged security alerts, analyzed log events across production SIEMs, and shadowed senior analysts on threat intelligence workflows.

---

### 📜 Certifications & Training

* **Fortinet:** Fortinet Certified Associate — FortiSIEM (2026) · FortiAnalyzer (2026)
* **TryHackMe:** SOC Level 1 Path (2026) · Security Engineer Path (2026)
* **Cisco:** Cybersecurity Engineer (DEPI, 2025) · CyberOps Associate (NTI, 2025) · CCNP ENCOR (NTI, 2025) · CCNA (NTI, 2023)
* **Other:** Vulnerability Analyst & Penetration Tester (DEPI) · HCIA Security (Huawei/NTI) · Ethical Hacking (NTI)

---

<p align="center">
  <sub><code>[ SYSTEM: OPERATIONAL ]</code> · <code>[ CLEARANCE: LEVEL-1 BLUE TEAM ]</code> · <code>[ STATUS: ACTIVE ]</code></sub>
</p>