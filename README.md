<div align="center">

```text
  ██╗     ██╗   ██╗███╗   ███╗██╗██████╗ ██████╗ ███████╗███╗   ██╗
  ██║     ██║   ██║████╗ ████║██║██╔══██╗██╔══██╗██╔════╝████╗  ██║
  ██║     ██║   ██║██╔████╔██║██║██║  ██║██████╔╝█████╗  ██╔██╗ ██║
  ██║     ██║   ██║██║╚██╔╝██║██║██║  ██║██╔══██╗██╔══╝  ██║╚██╗██║
  ███████╗╚██████╔╝██║ └──═╝██║██║██████╔╝██║  ██║███████╗██║ ╚████║
  ╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚═╝══════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝
```

  <p align="center">
    <code><strong>[ SYSTEM ARCHITECTURE: CYBER OPERATIONS // THREAT INTEL // OFFENSIVE RECON ]</strong></code>
  </p>

  <p align="center">
    <a href="https://github.com/lumidren">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=16&pause=1000&color=00FF66&background=0D111700&center=true&vCenter=true&width=750&lines=root%40lumidren-soc%3A~%23+nmap+-sC+-sV+--script%3Dvuln+target.corp;root%40lumidren-soc%3A~%23+wazuh-agent+-t+T1003.001+-a+HOST_ISOLATE+%5B%3C5s%5D;root%40lumidren-soc%3A~%23+python3+cipher_engine.py+--encrypt+blowfish-cbc+--stix2.1;root%40lumidren-soc%3A~%23+shadowsurface+-d+target.com+--passive-crtsh;%5BSTATUS%5D+AUTONOMOUS+SOC+PIPELINE+ACTIVE+%E2%80%A2+ZERO-TOUCH+DEFENSE+ENGAGED" alt="Terminal Typing SVG" />
    </a>
  </p>

  <p align="center">
    <a href="https://www.linkedin.com/in/lumidren/">
      <img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/lumidren?tab=repositories">
      <img src="https://img.shields.io/badge/REPOSITORIES-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="mailto:contact@lumidren.dev">
      <img src="https://img.shields.io/badge/PGP_ENCRYPTED_EMAIL-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/lumidren">
      <img src="https://img.shields.io/badge/SECURITY_CLEARANCE-LEVEL_5-00FF66?style=flat-square" alt="Clearance" />
    </a>
  </p>

</div>

---

### 🖥️ `neofetch --user lumidren`

```bash
               .,-:;//+++/++/:.-.              USER        : lumidren
           :+++++++++++++++++++++++/`          HOST        : E-JUST Cyber-Range [Egypt-Japan Univ of Sci & Tech]
         /+++++++++++++++++++++++++++/         KERNEL      : CyberOps / Autonomous IR / Detection Engineering
       `+++++++++++++++++++++++++++++++`       SHELL       : /bin/zsh (Wazuh SIEM, Shuffle SOAR, Python, CTI)
      .+++++++++++++++++++++++++++++++++       FRAMEWORKS  : MITRE ATT&CK • NIST CSF • OWASP Top 10 • STIX 2.1
     `+++++++++++++++++++++++++++++++++++`     CORE_CIPHER : Blowfish-CBC (256-bit) / Custom CTI Graph Models
     /+++++++++++++++++++++++++++++++++++/     PRIMARY_EXP : Zero-Touch Incident Containment & EASM Discovery
     /+++++++++++++++++++++++++++++++++++/     ACTIVE_IPS  : 127.0.0.1 (Loopback Preserved on Quarantine)
     `+++++++++++++++++++++++++++++++++++`     UPTIME      : 24/7/365 Continuous Threat Validation
      .+++++++++++++++++++++++++++++++++       STATUS      : OPERATIONAL [Threat Hunting & Pipeline Automation]
       `+++++++++++++++++++++++++++++++`
         /+++++++++++++++++++++++++++/
           :+++++++++++++++++++++++/`
               .,-:;//+++/++/:.-.
```

---

## 🚀 Key Projects & Systems Portfolio

### 🛡️ 1. Cyber Operations & SOC Automation (Blue Team)

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/lumidren/autonomous-soc-soar-pipeline">
          ⚡ AutoSOC-SOAR: Zero-Touch Incident Response
        </a>
      </h3>
      <p>
        <img src="https://img.shields.io/badge/SIEM-Wazuh%204.7-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/SOAR-Shuffle-green?style=flat-square" />
        <img src="https://img.shields.io/badge/MTTR-<5s-red?style=flat-square" />
      </p>
      <p>
        An enterprise-grade autonomous detection, threat intelligence enrichment, and instant endpoint containment pipeline that cuts incident response time by over 99%.
      </p>
      <ul>
        <li><strong>MITRE-Mapped Detections:</strong> High-fidelity rules for LSASS memory dumps (<code>T1003.001</code>), Ransomware canary triggers (<code>T1486</code>), and Unix Reverse Shells (<code>T1059.004</code>).</li>
        <li><strong>Autonomous Containment:</strong> Dynamically applies kernel/firewall quarantine rules while strictly preserving SIEM telemetry channels.</li>
        <li><strong>Full Containerization:</strong> Docker Compose multi-node cluster with real-time Discord/Slack ChatOps cards.</li>
      </ul>
      <p>👉 <a href="https://github.com/lumidren/autonomous-soc-soar-pipeline"><strong>View Repository</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/lumidren/CyberPulse-SOC-Suite">
          📡 CyberPulse SOC Suite
        </a>
      </h3>
      <p>
        <img src="https://img.shields.io/badge/Platform-SIEM%20%2B%20SOAR-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Framework-MITRE%20ATT%26CK-red?style=flat-square" />
        <img src="https://img.shields.io/badge/Language-Python-yellow?style=flat-square" />
      </p>
      <p>
        Full-lifecycle Security Operations Center platform integrating telemetry correlation, threat intelligence APIs, and real-time metrics dashboards.
      </p>
      <ul>
        <li><strong>Continuous Validation:</strong> Correlates endpoint alerts with behavioral threat signatures.</li>
        <li><strong>Automated Triage:</strong> Ingests live threat feeds and calculates composite risk indices.</li>
        <li><strong>Operational Dashboard:</strong> Unified visualization layer for incident timelines and response tracking.</li>
      </ul>
      <p>👉 <a href="https://github.com/lumidren/CyberPulse-SOC-Suite"><strong>View Repository</strong></a></p>
    </td>
  </tr>
</table>

---

### 🔐 2. Threat Intelligence, Cryptography & Offensive Security

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/lumidren/CIPHER">
          🗝️ CIPHER: Encrypted Threat Intelligence Platform
        </a>
      </h3>
      <p>
        <img src="https://img.shields.io/badge/Crypto-Blowfish%20CBC-darkred?style=flat-square" />
        <img src="https://img.shields.io/badge/Standard-STIX%202.1-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Backend-Flask-lightgrey?style=flat-square" />
      </p>
      <p>
        A secure, custom-built Cyber Threat Intelligence (CTI) platform built from scratch for SOC analysts to manage, encrypt, correlate, and graph IOCs.
      </p>
      <ul>
        <li><strong>Zero-Trust Data Security:</strong> Symmetric Blowfish CBC encryption for confidential IOC data stores.</li>
        <li><strong>Automated Intel Ingestion:</strong> Multi-engine lookups via VirusTotal & AbuseIPDB APIs.</li>
        <li><strong>Graph & Standards:</strong> Interactive IOC relationship mapping with automated export to <strong>STIX 2.1</strong> and TAXII formats.</li>
      </ul>
      <p>👉 <a href="https://github.com/lumidren/CIPHER"><strong>View Repository</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/lumidren/shadowsurface-recon-framework">
          🔍 ShadowSurface: EASM & OSINT Framework
        </a>
      </h3>
      <p>
        <img src="https://img.shields.io/badge/Focus-CEH%20v12-red?style=flat-square" />
        <img src="https://img.shields.io/badge/Type-Attack%20Surface%20Mgmt-purple?style=flat-square" />
        <img src="https://img.shields.io/badge/Reports-HTML%20%2B%20JSON-teal?style=flat-square" />
      </p>
      <p>
        Automated External Attack Surface Management (EASM) and reconnaissance framework aligned with Certified Ethical Hacker (CEH) methodologies.
      </p>
      <ul>
        <li><strong>Passive OSINT:</strong> Subdomain discovery via Certificate Transparency logs (<code>crt.sh</code>) with zero packet noise.</li>
        <li><strong>Hygiene Audits:</strong> Evaluates SPF/DMARC mail spoofing vulnerabilities, exposed management ports, and missing HTTP headers (HSTS, CSP).</li>
        <li><strong>Algorithmic Risk Scoring:</strong> Generates quantified posture grades and interactive dark-mode HTML dashboards.</li>
      </ul>
      <p>👉 <a href="https://github.com/lumidren/shadowsurface-recon-framework"><strong>View Repository</strong></a></p>
    </td>
  </tr>
</table>

---

### 💻 3. Software Engineering, WebGL & Campus Applications

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/lumidren/crystal-collector">
          💎 Crystal Collector: 3D WebGL Arcade Engine
        </a>
      </h3>
      <p>
        <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square&logo=react" />
        <img src="https://img.shields.io/badge/3D%20Graphics-Three.js-000000?style=flat-square&logo=three.js" />
        <img src="https://img.shields.io/badge/Physics-WebGL-orange?style=flat-square" />
      </p>
      <p>
        A fast-paced interactive 3D browser game featuring 4 multi-stage levels, dynamic stamina management, obstacle collision physics, and real-time lighting.
      </p>
      <p>👉 <a href="https://github.com/lumidren/crystal-collector"><strong>View Repository</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/lumidren/E-JUST-Campus-App">
          🏛️ E-JUST Campus Application
        </a>
      </h3>
      <p>
        <img src="https://img.shields.io/badge/Institution-E--JUST-red?style=flat-square" />
        <img src="https://img.shields.io/badge/Type-Campus%20Ecosystem-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-Full--Stack-success?style=flat-square" />
      </p>
      <p>
        Comprehensive campus service application designed for students and faculty at the Egypt-Japan University of Science and Technology (E-JUST).
      </p>
      <p>👉 <a href="https://github.com/lumidren/E-JUST-Campus-App"><strong>View Repository</strong></a></p>
    </td>
  </tr>
</table>

---

## 🛠️ Comprehensive Technical Arsenal

<table align="center" width="100%">
  <tr>
    <td width="25%" valign="top">
      <h4>🛡️ Blue Team & SOC</h4>
      <ul>
        <li>Wazuh SIEM / Indexer</li>
        <li>Shuffle SOAR Engine</li>
        <li>Sysmon & Linux Auditd</li>
        <li>TheHive & Cortex</li>
        <li>MISP & OpenCTI</li>
        <li>Zeek & Suricata IDS</li>
        <li>Sigma Detection Rules</li>
        <li>YARA Signatures</li>
      </ul>
    </td>
    <td width="25%" valign="top">
      <h4>⚔️ Offensive & Recon</h4>
      <ul>
        <li>OSINT & Footprinting</li>
        <li>Certificate Transparency</li>
        <li>Nmap & Masscan</li>
        <li>Burp Suite Professional</li>
        <li>Metasploit Framework</li>
        <li>BloodHound & Active Directory</li>
        <li>LinPEAS / WinPEAS</li>
        <li>Wireshark / Packet Analysis</li>
      </ul>
    </td>
    <td width="25%" valign="top">
      <h4>💻 Languages & Core</h4>
      <ul>
        <li>Python 3.x (FastAPI, Flask)</li>
        <li>PowerShell 5.1 / 7+</li>
        <li>Bash / Shell Scripting</li>
        <li>JavaScript (ES6+)</li>
        <li>React.js & Three.js</li>
        <li>HTML5 / CSS3 / Tailwind</li>
        <li>SQL (PostgreSQL, MySQL)</li>
        <li>JSON / YAML / XML</li>
      </ul>
    </td>
    <td width="25%" valign="top">
      <h4>☁️ Infra & Standards</h4>
      <ul>
        <li>Docker & Docker Compose</li>
        <li>Linux (Ubuntu, Debian, Kali)</li>
        <li>Windows Server / AD DC</li>
        <li>Git & GitHub CI/CD</li>
        <li>MITRE ATT&CK Framework</li>
        <li>NIST CSF & SP 800-61</li>
        <li>STIX 2.1 & TAXII</li>
        <li>OWASP Top 10</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📊 Live GitHub Activity & Statistics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lumidren&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lumidren&layout=compact&theme=tokyonight&hide_border=true" width="49%" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=lumidren&theme=tokyonight&hide_border=true" width="98%" />
</div>

---

## 🤝 Let's Connect & Collaborate

<div align="center">

  <a href="https://www.linkedin.com/in/lumidren/">
    <img src="https://img.shields.io/badge/LinkedIn-Lumidren-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/lumidren">
    <img src="https://img.shields.io/badge/GitHub-lumidren-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:contact@lumidren.dev">
    <img src="https://img.shields.io/badge/Email-Get_In_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

</div>

---

<div align="center">
  <sub><code>[ root@lumidren-secops ] :: SYSTEM_INTEGRITY=SECURE :: © Lumidren • E-JUST</code></sub>
</div>
