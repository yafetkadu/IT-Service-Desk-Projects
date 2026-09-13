# 🛠️ IT Service Desk Projects & Incident Management

![Platform](https://img.shields.io/badge/Platform-Service%20Desk-blue)
![Role](https://img.shields.io/badge/Role-IT%20Support%20Specialist-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Executive Summary
This repository documents real-world IT service desk incident resolutions, user support tickets, and technical troubleshooting workflows. Each ticket demonstrates structured problem-solving across network infrastructure, identity management, hardware asset deployment, and system configuration.

---

## 🛠️ Core Skills & Technologies Demonstrated
* **Identity & Access Management:** Active Directory, secure identity verification, password resets.
* **Networking & Protocols:** TCP/IP, DNS (`nslookup`, `ipconfig /flushdns`), DHCP, server ping testing.
* **System & Infrastructure Admin:** Domain Controllers (`DC01`), Exchange email servers, Windows settings, RDP.
* **Service Desk Operations:** Cost-conscious hardware triage, root-cause isolation, ticket escalation workflows.

---

## 📋 Incident Log & Video Demonstrations

### 1️⃣ Incident: Need Temporary Password Reset After Vacation
* **Category:** Active Directory / IAM
* **Impact:** High
* **Summary:** Performed strict user identity verification prior to issuing a password reset, following security protocols to prevent unauthorized access before sending temporary login credentials.
* **Video Demonstration:** [Watch Silent Screen Recording on Loom](https://www.loom.com/share/b08baa35d78149a5b80adc2bd9e20bb2)

---

### 2️⃣ Incident: Customer Agent Laptop is Dead (Remote Worker)
* **Category:** Hardware Triage & Provisioning
* **Impact:** Critical
* **Summary:** Conducted routine triage to rule out simple charger or power issues and save hardware replacement costs. After confirming hardware failure, provisioned a new laptop on IPv4, assigned a network hostname, and initiated shipping to the user's verified address.
* **Video Demonstration:** [Watch Silent Screen Recording on Loom](https://www.loom.com/share/fb3ff4879b4a47fda137ee5120970c76)

---

### 3️⃣ Incident: Unable to Log In to PCs - Office-wide Outage
* **Category:** Network / Infrastructure
* **Impact:** Critical
* **Summary:** Inquired if the issue affected multiple users to isolate local workstation failure vs. infrastructure failure. Identified root cause at the Domain Controller (`DC01`) in the server room and executed a controlled reboot to restore authentication across the office.
* **Video Demonstration:** [Watch Silent Screen Recording on Loom](https://www.loom.com/share/2a30f33cf8aa4b1cb1c42e9c302fe79f)

---

### 4️⃣ Incident: Inbox Has Gone Quiet Since Yesterday
* **Category:** Application & Network Troubleshooting
* **Impact:** Medium / High
* **Summary:** RDP'd to user's machine to isolate an Exchange mail connectivity error. Systematic OSI troubleshooting ruled out physical network failure (internal web access worked) and DNS caching issues (`ping`, `nslookup`, `ipconfig /flushdns`). Resolved the issue at the application layer by executing an in-app software repair/reinstall.
* **Video Demonstration:** [Watch Silent Screen Recording on Loom](https://www.loom.com/share/783ac8e5909c44749b9947b3d8360bf8)

---

## ✍️ Author
**Yafet Befkadu**  
[LinkedIn](https://linkedin.com) | [Email](mailto:yafetbefkadu@gmail.com)
