# 🔐 Wazuh SOC Lab

## 📌 Project Overview

This project demonstrates a complete SOC (Security Operations Center) lab using Wazuh SIEM.

The lab includes a Wazuh server (Ubuntu) and a Windows 10 agent to simulate real-world security monitoring.

---

## 🧱 Architecture

* 🐧 Ubuntu 22.04 → Wazuh Server (Manager + Indexer + Dashboard)
* 🪟 Windows 10 → Wazuh Agent
* 🌐 Web Interface → HTTPS Dashboard

---

## ⚙️ Installation

### 1. Install Wazuh on Ubuntu

```bash
sudo apt update && sudo apt install curl -y
curl -sO https://packages.wazuh.com/4.7/wazuh-install.sh
sudo bash wazuh-install.sh -a
```

---

### 2. Access Dashboard

```
https://<server-ip>:443
User: admin
Password: <generated-password>
```

---

### 3. Install Windows Agent

* Download Wazuh agent
* Configure manager IP
* Start service

---

## 🧪 Tests Performed

### 🔴 Failed Login Detection

* Enabled Windows auditing (auditpol)
* Generated failed login attempts
* Detected in Wazuh (Event ID 4625)

### 🟠 Privilege Escalation Attempt

* Triggered privileged operation
* Detected alert:

> Failed attempt to perform a privileged operation

### 🟡 Log Monitoring

* Real-time logs collected from Windows agent

---

## 📸 Screenshots

### 🔐 Login

![Login](screenshots/login.png)

### ✅ Health Check

![Health](screenshots/health-check.png)

### 📊 Dashboard

![Dashboard](screenshots/dashboard-overview.png)

### 💻 Agent Connected

![Agent](screenshots/agent-connected.png)

### 🚨 Security Alerts

![Alerts](screenshots/security-alerts.png)

---

## 📊 Results

* ✅ Wazuh deployed successfully
* ✅ Agent connected and monitored
* ✅ Security events detected in real-time
* ✅ SOC environment fully functional

---

## 🧠 Skills Gained

* SIEM (Wazuh)
* Log Analysis
* Windows Security Monitoring
* Cybersecurity Basics

---

## 🚀 Future Improvements

* Add Sysmon for advanced logging
* Add Linux agents
* Simulate real cyber attacks (Brute force, PowerShell attacks)

---

## 👨‍💻 Author

* Ilyas Elouarrari
