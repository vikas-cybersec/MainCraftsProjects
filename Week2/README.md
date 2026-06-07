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

### Author

**Vikas Bhati**
B.Tech Computer Science & Engineering (Cyber Security)
Silver Oak University, Ahmedabad
