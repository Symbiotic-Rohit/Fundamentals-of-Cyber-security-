# Fundamentals-of-Cyber-security-
Based on the requirements for **Task - 1 (Foundation & Environment Setup)**, here is a comprehensive template for your GitHub repository's **README.md** file and a structure for your **Linux Cheat-sheet**. This content is designed to help you document your progress and fulfill the deliverables mentioned in the sources.

### GitHub Repository: `Cybersecurity-Foundation-Lab`

#### **README.md Template**

```markdown
# Cybersecurity Foundation & Lab Environment Setup

## Objective
The objective of this project is to build a strong fundamental understanding of cybersecurity, networking, and cryptography, while successfully configuring a professional hacking lab environment.

## 1. Cybersecurity Basics
Research and documentation on core security principles:
*   **CIA Triad:** Detailed analysis of Confidentiality, Integrity, and Availability.
*   **Threat Landscapes:** Documentation on Phishing, Malware, DDoS, SQL Injection, Brute Force, and Ransomware.
*   **Attack Vectors:** Study of Social Engineering, Wireless Attacks, and Insider Threats.

## 2. Lab Environment Setup
Step-by-step guide on the virtualization and configuration of the testing environment:
*   **Hypervisor:** Installation of VirtualBox/VMware.
*   **Attacker Machine:** Deployment of **Kali Linux**.
*   **Target Machines:** Deployment of **Metasploitable2** or **DVWA** (Damn Vulnerable Web App).
*   **Networking:** Configuration of a private lab network using a **Host-Only Adapter** for safety and isolation.

## 3. Linux Fundamentals
Mastery of the Linux command line essential for security professionals:
*   **File System Navigation:** `cd`, `ls`, `pwd`.
*   **Permissions:** Managing access with `chmod` and `chown`.
*   **Package Management:** Using `apt` and `dpkg` to manage software.
*   **Networking Commands:** Using `ifconfig`, `ping`, `netstat`, and `traceroute` for diagnostics.

## 4. Networking Essentials
Documentation on how data moves across networks:
*   **OSI Model:** Layers and specific functions.
*   **TCP/IP Suite:** Core protocols and their roles.
*   **Web Traffic:** Deep dive into DNS and HTTP/HTTPS.
*   **Addressing:** Practical understanding of IP Addressing, Subnetting, and NAT.

## 5. Cryptography Basics
Exploration of secure communication methods:
*   **Encryption:** Symmetric vs. Asymmetric Encryption methods.
*   **Hashing:** Understanding MD5 and SHA256 integrity checks.
*   **Digital Security:** Implementing Digital Certificates and SSL/TLS.
*   **Hands-on:** Documentation of encrypting/decrypting messages using **OpenSSL**.

## 6. Tool Familiarization
Practical application and notes on industry-standard tools:
*   **Wireshark:** Network packet capture and analysis.
*   **Nmap:** Network scanning and service discovery.
*   **Burp Suite:** Web application proxy and vulnerability testing.
*   **Netcat:** Networking debugging and data transfer.

## Deliverables
- [ ] **Lab Setup Report:** Screenshots of Kali, Metasploitable, and Wireshark captures.
- [ ] **Linux Cheat-sheet:** Comprehensive command reference (see `LINUX_CHEATSHEET.md`).
- [ ] **5-min Video Walkthrough:** Demonstration of the lab setup and connectivity.

---
*Credits: Curriculum provided by ApexPlanet (www.apexplanet.in)*.
```

### **Linux Cheat-sheet Content (`LINUX_CHEATSHEET.md`)**

You can include this as a separate file in your repository:

*   **Navigation:** `pwd` (print working directory), `ls -la` (list all files with details), `cd [dir]` (change directory).
*   **File Operations:** `mkdir` (make directory), `rm -rf` (recursive force remove), `cp` (copy), `mv` (move/rename).
*   **Permissions:** `chmod 755 [file]` (set read/write/execute), `chown user:group [file]` (change owner).
*   **System/Network:** `ifconfig` (view IP), `netstat -tuln` (view active ports), `top` (process monitor), `traceroute [host]` (trace path to host).
*   **Package Management:** `sudo apt update` (update repos), `sudo apt install [package]` (install tool).

By organizing your repository this way, you fulfill the specific "GitHub Repo with notes & Linux cheat-sheet" deliverable required for Task - 1.
