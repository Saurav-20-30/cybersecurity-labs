# 🛡️ Vulnerabilities 101 & Web Application Security (TryHackMe)

This document summarizes my hands-on learning from the **TryHackMe Vulnerabilities 101 and Web Application Security labs**, focusing on understanding vulnerabilities, risk scoring, and real-world exploitation.

---

## 🔍 What is a Vulnerability?
A vulnerability is a **weakness or flaw** in a system, application, or configuration that can be exploited by an attacker.

### Key Terms
- **Vulnerability:** The weakness itself
- **Exploit:** The method or code used to take advantage of the weakness
- **PoC (Proof of Concept):** Demonstration that exploitation is possible

---

## 🧩 Categories of Vulnerabilities

### 🖥️ Operating System Vulnerabilities
- Found in the OS itself
- Often lead to **privilege escalation**

### ⚙️ Misconfiguration-Based
- Incorrect settings expose sensitive data
- Example: Publicly accessible admin panels

### 🔑 Weak or Default Credentials
- Use of default usernames/passwords
- Easily exploited by attackers

### 🧠 Application Logic Flaws
- Poorly designed authentication or authorization logic
- Example: Login bypass using cookies

### 👤 Human-Factor Vulnerabilities
- Target users instead of systems
- Example: Phishing attacks

---

## 📊 Risk Scoring Systems

### CVSS (Common Vulnerability Scoring System)
- Free and open-source
- Static severity scoring
- Introduced in 2005

### VPR (Vulnerability Priority Rating)
- Risk-based and dynamic
- Updates based on real-world threat activity

---

## 🗂️ Vulnerability Databases

### 🏛️ NVD (National Vulnerability Database)
- Official repository of CVEs
- CVE format: CVE-YYYY-XXXX

### 💣 Exploit-DB
- Contains real-world exploit code
- Maintained by Offensive Security (OffSec)

---

## 💥 Practical Exploitation Example

### 🔎 Information Gathering
- Tool used: **Nmap**
- Identified application version: *Online Book Store v1.0*

### 📚 Research
- Found exploit on Exploit-DB
- Vulnerability: **Unauthenticated Remote Code Execution (RCE)**

### ⚔️ Exploitation
- Exploit executed successfully
- Flag captured: `THM{ACKME_ENGAGEMENT}`

---

## 🌐 Web Application Security Findings

### 🔐 Identification & Authentication Failure
- Unlimited login attempts
- No rate limiting or account lockout

### 🔑 Cryptographic Failures
- Credentials sent in cleartext
- Risk of Man-in-the-Middle attacks

### 💉 Injection (SQL Injection)
- Login bypass using `' OR 1=1 --`
- Input not properly sanitized

### 🚪 Broken Access Control
- Access to `/admin` directory without authorization

### ⚙️ Security Misconfiguration
- Software version disclosure via headers

---

## 🔎 IDOR (Insecure Direct Object Reference)

### Vulnerability
- Predictable `user_id` parameter in URL

### Attack
- Manual parameter manipulation
- Accessed another user’s data

### Flag
- `THM{IDOR_EXPLORED}`

---

## 🎓 Learning Outcomes
- Understood real-world vulnerability categories
- Learned risk prioritization techniques
- Performed reconnaissance and exploitation
- Gained practical web security experience

---

## 🧪 Lab Platform
- **TryHackMe**
  
## 🔗lab link
 (TryHackMe | Vulnerabilities 101 https://share.google/vIUFWBRHarKe9EnoK)
 
## 📄 Detailed Report (PDF)
[View Full PDF Report](vulnerabilities-101.pdf)
