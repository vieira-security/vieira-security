# Hi, my name is Gabriel Vieira. Welcome to my profile! 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-vieira-de-sousa-330b55249/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contato.gabrielvieira21@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-990000?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/legacy.sousa)

* 🎓 Computer Science student at **Universidade Presbiteriana Mackenzie**.
* 🛡️ Transitioning into **DevSecOps**, combining a solid background in **information security, infrastructure, and log analysis** with automation and secure development practices.
* 🎯 **Currently seeking a junior DevSecOps role / internship**, where I can apply security integrated into the development lifecycle — from infrastructure as code to secure pipeline automation.
* ⚙️ My edge: I understand both the *security side* (logs, authentication, network events, hardening) and the *automation side* (scripting, pipelines, data), which lets me treat security as part of the delivery flow, not a bolted-on step.

## 🛠️ Skills & Tools:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash Script](https://img.shields.io/badge/bash_script-%234EAA25.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)

* 🛡️ **Security & Infrastructure (core domain):** log analysis, intrusion detection, access control, TCP/IP networking (IPv4/IPv6, DNS, DHCP, firewalls), Linux hardening.
* ⚙️ **DevSecOps & Automation (building up):** Bash/Python for security automation, Docker (container fundamentals), Git/GitHub, integrating security practices into CI/CD pipelines, SAST/DAST (studying), IaC (studying).
* 📊 **Data & Scripting (supporting skillset):** Python (pandas, NumPy), SQL (joins, aggregations, subqueries, CTEs), ETL and anomaly detection — skills I apply to process logs and security events at scale.

## 💼 Featured Project:

### 🛡️ [Security Analytics as a Data Product — Anomaly Detection in Access Logs](https://github.com/vieira-security/security-analytics)

End-to-end pipeline that turns **raw web access logs into a prioritized queue of suspicious IPs**, combining automation, data, and security.

* **Pipeline:** raw Nginx logs (~9k lines) → regex-based ETL → SQLite (fact + dimension modeling) → analytical SQL (CTEs, JOINs, subqueries) → feature matrix per IP.
* **Detection:** robust z-score (median/MAD) + Isolation Forest, combined into an explainable 0–100 risk score.
* **Results against planted ground truth:** 100% recall, 91.7% precision. Key insight: 93% of failed logins occurred outside business hours — a single cheap alert rule would cover most of the observed risk.
* **Delivery:** interactive Streamlit dashboard with per-IP drill-down + static reports.

*Stack: Python · pandas · scikit-learn · SQL · Streamlit · Plotly*

## 📁 Other Experience and Projects:

* 🔍 **Log Analyzer (Python):** a script for analyzing access logs on Linux servers, detecting suspicious patterns and intrusion attempts, with automated reporting.
* 🌐 **Network Port Scanner (Python & Scapy):** a tool for scanning local network ports, implementing SYN scan techniques and banner grabbing for service fingerprinting.
* 🏛️ **IT Infrastructure & Security Intern (CEAGESP):** technical support for over 500 users, connectivity troubleshooting, hardware/software deployment, and security policy enforcement — hands-on experience with the operations that DevSecOps environments run on.

## 📚 Currently Learning / Certifications in Progress:

![Coursera](https://img.shields.io/badge/Coursera-%230056B3.svg?style=for-the-badge&logo=Coursera&logoColor=white)

* 🛡️ **Google Cybersecurity Professional Certificate** (Coursera);
* 🌐 **Cisco NetAcad** — Networking and Cybersecurity;
* 🎯 **TryHackMe Tracks:** *SOC Level 1* and *Offensive Security* (Pre-Security completed);
* ⚙️ **Next up:** secure CI/CD fundamentals (GitHub Actions/GitLab CI), Docker/Kubernetes security, Infrastructure as Code (Terraform) with a security focus.
