# 🧪 Personal Cybersecurity Lab Build — Task 2

---

# 👨‍💻 Internship Details

* **Intern Name:** Teli Vikas
* **Role:** Cybersecurity Analyst Intern
* **Organization:** Maincrafts Technology
* **Duration:** 2 Weeks Internship
* **Date:** May 2025

---

# 📖 Project Overview

This repository contains my **Personal Cybersecurity Lab Build Report** created during my internship at Maincrafts Technology.

The objective of this task was to design and deploy a fully isolated cybersecurity practice environment that can safely support vulnerability assessment, penetration testing, network analysis, web application security testing, and future cybersecurity learning activities.

The lab was built using virtualization, containerization, and industry-standard cybersecurity tools to simulate a realistic security testing environment.

---

# 🎯 Objective

Build a secure and isolated personal cybersecurity lab capable of supporting:

* Ethical Hacking Practice
* Vulnerability Assessment
* Network Scanning
* Web Application Testing
* Packet Analysis
* Security Research
* Future Cybersecurity Projects

---

# 🖥️ Lab Architecture

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

---

# ⚙️ Lab Components

| Component             | Details               |
| --------------------- | --------------------- |
| Host Operating System | Windows 10 x64        |
| Hypervisor            | VMware Workstation    |
| Attacker Machine      | Kali Linux 64-bit     |
| RAM Allocated         | 4 GB                  |
| CPU Allocated         | 8 vCPUs               |
| Target Application    | OWASP Juice Shop      |
| Deployment Method     | Docker Container      |
| Network 1             | VMnet8 NAT            |
| Network 2             | VMnet1 Host-Only      |
| Target URL            | http://localhost:3000 |

---

# 🔧 Technologies Used

### VMware Workstation

Used to create and manage virtual machines while maintaining complete isolation from the host operating system.

### Kali Linux

Served as the primary attacker machine and provided a professional penetration testing environment.

### Docker

Used to deploy OWASP Juice Shop in an isolated containerized environment.

### OWASP Juice Shop

A deliberately vulnerable web application designed for web security testing and learning.

---

# 🛠️ Tools Validated

## 🔍 Nmap v7.95

### Purpose

Network discovery and host enumeration.

### Activities Performed

* Host Discovery
* Network Scanning
* Port Enumeration
* Service Detection

### Result

Successfully discovered active hosts on the isolated lab network.

---

## 🌐 Burp Suite Community Edition

### Purpose

Web application traffic interception and analysis.

### Activities Performed

* HTTP Request Interception
* Response Analysis
* Proxy Configuration
* Traffic Inspection

### Result

Successfully intercepted and analyzed Juice Shop traffic.

---

## 📡 Wireshark

### Purpose

Packet capture and network traffic analysis.

### Activities Performed

* Live Packet Capture
* Protocol Inspection
* Network Monitoring
* Traffic Analysis

### Result

Successfully captured and analyzed network packets.

---

## 🐳 Docker

### Purpose

Container deployment and management.

### Activities Performed

* Docker Installation
* Container Deployment
* Service Management
* Juice Shop Hosting

### Result

Successfully deployed OWASP Juice Shop.

---

# ✅ Evidence Collected

| #  | Evidence Item                               | Status     |
| -- | ------------------------------------------- | ---------- |
| 1  | VMware Virtual Network Editor Configuration | ✅ Verified |
| 2  | NAT Network Configuration                   | ✅ Verified |
| 3  | Host-Only Network Configuration             | ✅ Verified |
| 4  | Kali Linux Installation                     | ✅ Verified |
| 5  | Kali Linux Update & Upgrade                 | ✅ Verified |
| 6  | Docker Installation                         | ✅ Verified |
| 7  | OWASP Juice Shop Deployment                 | ✅ Verified |
| 8  | Dual IP Configuration                       | ✅ Verified |
| 9  | Nmap Host Discovery Scan                    | ✅ Verified |
| 10 | Burp Suite HTTP Interception                | ✅ Verified |
| 11 | Wireshark Packet Capture                    | ✅ Verified |

---

# 🔐 Security Benefits of the Lab

The cybersecurity lab provides:

* Safe Testing Environment
* Isolated Attack Surface
* Practical Security Training
* Controlled Vulnerability Assessment
* Secure Experimentation
* Realistic Attack Simulation

This setup prevents accidental impact on production systems while allowing hands-on learning.

---

# 📁 Repository Structure

```bash
MainCraftsProjects/
│
├── README.md
│
├── Week1/
│   ├── Cybersecurity_Threat_Report_Task1_[Teli Vikas].pdf
│   └── README.md
│
├── Week2/
│   ├── Cybersecurity_Lab_Build_Report_Task2_[Teli Vikas].pdf
│   └── README.md
```

---

# 🛠️ Skills Gained

During this task, I improved my understanding of:

* VMware Virtualization
* Linux Administration
* Docker Containerization
* Network Configuration
* Web Application Security
* Nmap Scanning
* Burp Suite Usage
* Wireshark Analysis
* Cybersecurity Lab Design
* Security Testing Methodologies

---

# 🔭 Future Scope

This lab environment will be used for future activities including:

* Vulnerability Assessment
* Penetration Testing
* Web Application Security Testing
* Active Directory Labs
* Security Monitoring
* Digital Forensics
* Malware Analysis
* Capture The Flag (CTF) Challenges

---

# 📚 References

* OWASP Juice Shop Documentation
* Kali Linux Documentation
* VMware Workstation Documentation
* Docker Documentation
* Nmap Official Guide
* Wireshark Documentation
* Burp Suite Documentation
* OWASP Testing Guide

---

# ⭐ Acknowledgment

I sincerely thank **Maincrafts Technology** for providing me with the opportunity to gain practical cybersecurity experience and build a professional cybersecurity lab environment for hands-on learning.

---

# 👨‍💻 Author

## Teli Vikas

Cybersecurity Analyst Intern

### 📫 Connect With Me

* GitHub: https://github.com/vikas-cybersec
* LinkedIn: https://www.linkedin.com/in/vikas-teli/

---

### ⭐ If you found this project useful, consider giving it a star!

