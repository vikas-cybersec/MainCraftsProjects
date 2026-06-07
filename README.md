# 🔐 🔐 Cybersecurity Internship — Maincrafts Technology 

<div align="center">

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Threat%20Intelligence-blue?style=for-the-badge\&logo=hackaday)
![Status](https://img.shields.io/badge/Task-Completed-success?style=for-the-badge)
![Internship](https://img.shields.io/badge/Maincrafts-Technology-orange?style=for-the-badge)
![Role](https://img.shields.io/badge/Role-Cybersecurity%20Analyst-red?style=for-the-badge)

</div>

---

# 👨‍💻 Internship Details

* **Intern Name:** Teli Vikas
* **Role:** Cybersecurity Analyst Intern
* **Organization:** Maincrafts Technology
* **Duration:** 2 Weeks Internship
* **Date:** May 2025

---

# 📖 Project Overview

This repository contains my **Cybersecurity Threat Intelligence Report** created during my internship at Maincrafts Technology.

The report focuses on analyzing modern cybersecurity threats affecting organizations worldwide during **2024–2025**. It includes:

* Threat Analysis
* Real-world Case Studies
* Attack Impact Assessment
* Risk Evaluation
* Security Recommendations
* Defense Strategies

The objective of this task was to understand evolving cyber threats and explore effective mitigation techniques used by cybersecurity professionals.

---

# 🚨 Threats Analyzed

| # | Threat                           | Severity    | Trend    |
| - | -------------------------------- | ----------- | -------- |
| 1 | AI-Powered Phishing Attacks      | 🔴 Critical | ↑ Rising |
| 2 | Ransomware-as-a-Service (RaaS)   | 🔴 Critical | ↑ Rising |
| 3 | Cloud Security Misconfigurations | 🟠 High     | → Stable |
| 4 | IoT Vulnerabilities              | 🟠 High     | ↑ Rising |
| 5 | Zero-Day Exploits                | 🔴 Critical | ↑ Rising |

---

# 🧠 1. AI-Powered Phishing Attacks

### 🔍 Description

Artificial Intelligence and Large Language Models (LLMs) are enabling attackers to create highly personalized phishing campaigns and deepfake-based scams.

### 📌 Real-World Case Study

**MGM Resorts Deepfake Vishing Attack (2023)**

### 💥 Impact

* Financial losses
* Credential theft
* Operational disruption
* Social engineering attacks

### 🛡️ Defense Strategies

* Multi-Factor Authentication (MFA)
* Security Awareness Training
* Email Security Solutions
* Zero Trust Architecture

---

# 💀 2. Ransomware-as-a-Service (RaaS)

### 🔍 Description

Cybercriminal groups provide ransomware kits and infrastructure to affiliates, making ransomware attacks more accessible.

### 📌 Real-World Case Study

**Change Healthcare Attack (2024)**

### 💥 Impact

* System encryption
* Data theft
* Service disruption
* Financial damage

### 🛡️ Defense Strategies

* Immutable Backups
* Endpoint Detection & Response (EDR)
* Patch Management
* Network Segmentation

---

# ☁️ 3. Cloud Security Misconfigurations

### 🔍 Description

Misconfigured cloud environments expose sensitive organizational data due to insecure storage and excessive permissions.

### 📌 Real-World Case Study

**Microsoft Power Apps Data Exposure**

### 🛡️ Defense Strategies

* Cloud Security Posture Management (CSPM)
* Least Privilege Principle
* Secure IAM Configuration
* Infrastructure-as-Code (IaC) Scanning

---

# 📡 4. IoT Vulnerabilities

### 🔍 Description

Internet of Things (IoT) devices often lack strong security mechanisms and become easy targets for attackers.

### 📌 Real-World Case Study

**Mirai Botnet Attack**

### 💥 Impact

* Massive DDoS attacks
* Internet outages
* Device compromise

### 🛡️ Defense Strategies

* Change Default Credentials
* Firmware Updates
* IoT Network Segmentation
* Device Monitoring

---

# 🔓 5. Zero-Day Exploits

### 🔍 Description

Zero-day vulnerabilities are unknown software flaws exploited before developers release security patches.

### 📌 Real-World Case Study

**MOVEit Transfer Zero-Day (CVE-2023-34362)**

### 💥 Impact

* Data breaches
* Large-scale compromise
* Supply chain attacks

### 🛡️ Defense Strategies

* Behavioral EDR/XDR
* WAF & IPS Protection
* Threat Intelligence Integration
* Attack Surface Reduction

---

# 📊 Key Cybersecurity Statistics

| Metric                           | Value          |
| -------------------------------- | -------------- |
| Global Cybercrime Cost by 2025   | $10.5 Trillion |
| Average Data Breach Cost         | $4.88 Million  |
| Average Ransomware Recovery Cost | $2.73 Million  |
| Average APT Dwell Time           | 204 Days       |

---

# 📁 Repository Structure

```bash id="9lcpj9"
Cybersecurity-Internship/
│
├── README.md
│
├── Task-1/
│   └── Cybersecurity_Threat_Report_Task1_[Teli Vikas].pdf
```

---

# 🛠️ Skills Gained

During this task, I improved my understanding of:

* Threat Intelligence
* Cybersecurity Research
* Risk Assessment
* Incident Analysis
* Security Documentation
* Defensive Cybersecurity Strategies
* Real-World Attack Analysis

---

# 🔭 Future Scope

Future cybersecurity areas highlighted in this report include:

* 🤖 AI vs AI Cyber Warfare
* 🔐 Post-Quantum Cryptography
* 🎭 Deepfake Fraud
* ⚡ Critical Infrastructure Attacks
* 🌐 Nation-State Cyber Threats

---

# 📚 References

* IBM Security — Cost of a Data Breach Report 2024
* CISA Cybersecurity Advisories
* Sophos State of Ransomware 2024
* OWASP Top 10
* MITRE ATT&CK Framework
* Verizon DBIR 2024
* Cloudflare DDoS Threat Report 2024
* NIST Post-Quantum Cryptography Standards

---

## 🧪 Task 2 — Personal Cybersecurity Lab Build

**Objective:** Build a safe and fully isolated personal cybersecurity practice environment to serve as the foundation for all future hands-on tasks.

### 🖥️ Lab Architecture

```text
+--------------------------------------------------+
|           Host System — Windows 10 x64           |
|                                                  |
|   └── VMware Workstation                         |
|         ├── Kali Linux VM (Attacker)             |
|         └── OWASP Juice Shop via Docker (Target) |
|                                                  |
|   Networks:                                      |
|     • VMnet8 NAT       → Internet / Updates      |
|     • VMnet1 Host-Only → Isolated Lab Traffic    |
+--------------------------------------------------+
```

### ⚙️ Lab Components

| Component   | Details                                   |
| ----------- | ----------------------------------------- |
| Host OS     | Windows 10 x64                            |
| Hypervisor  | VMware Workstation                        |
| Attacker VM | Kali Linux (64-bit, 4GB RAM, 8 vCPUs)     |
| Target App  | OWASP Juice Shop via Docker               |
| Target URL  | http://localhost:3000                     |
| Network 1   | VMnet8 — NAT (internet access)            |
| Network 2   | VMnet1 — Host-Only (isolated lab traffic) |

### ✅ Evidence Collected

1. VMware Virtual Network Editor (NAT + Host-Only) — Verified
2. Kali Linux VM — apt update/upgrade + lab folders — Verified
3. Docker installation and service enabled — Verified
4. OWASP Juice Shop running at localhost:3000 — Verified
5. Dual IP configuration (NAT + Host-Only) — Verified
6. Nmap scan — hosts discovered on Host-Only subnet — Verified
7. Burp Suite intercepting HTTP traffic from Juice Shop — Verified
8. Wireshark capturing live packets — Verified

### 🛠️ Tools Validated

* Nmap v7.95 — Network discovery and host scanning
* Burp Suite Community — HTTP interception and proxy
* Wireshark — Live packet capture and analysis
* Docker — Container deployment and management

### 📂 File

📄 Cybersecurity_Lab_Build_Report_Task2_TeliVikas.pdf

---

## 🗂️ Repository Structure

```text
MainCraftsProjects/
├── Week1/
│   ├── Cybersecurity_Threat_Report_Task1_[Teli Vikas]
│   └── README.md
├── Week2/
│   ├── Cybersecurity_Lab_Build_Report_Task2_TeliVikas.pdf
│   └── README.md
└── README.md
```

---

## 🔗 Connect

* 🌐 Organization: Maincrafts Technology
* 💼 LinkedIn: https://www.linkedin.com/in/vikas-teli/
* 🐙 GitHub: https://github.com/vikas-cybersec

---

# ⭐ Acknowledgment

I sincerely thank **Maincrafts Technology** for providing me the opportunity to work on cybersecurity research and enhance my practical understanding of modern cyber threats.

---

# 👨‍💻 Author

## Teli Vikas

Cybersecurity Analyst Intern

### 📫 Connect With Me

* GitHub:https://github.com/vikas-cybersec
* LinkedIn: https://www.linkedin.com/in/vikas-teli/

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

</div>
