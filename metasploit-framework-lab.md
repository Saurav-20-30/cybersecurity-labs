# 💣 Metasploit Framework Lab (TryHackMe)

This document covers my hands-on learning of the **Metasploit Framework**, focusing on exploitation workflow, payloads, and post-exploitation concepts.

---

## 🧠 Introduction
Metasploit is one of the most widely used **penetration testing frameworks**, enabling attackers and security professionals to exploit known vulnerabilities in a controlled environment.

---

## 🧩 Core Components

### 🖥️ msfconsole
- Primary command-line interface
- Used to search, configure, and run modules

### 💥 Exploit
- Code that takes advantage of a vulnerability

### 📦 Payload
- Code executed after successful exploitation

#### Types of Payloads
- **Singles:** Self-contained payloads
- **Staged:** Delivered in multiple parts

### 🧬 Encoders
- Obfuscate payloads
- Help bypass signature-based antivirus detection

---

## 🔍 Metasploit Workflow

### 🔎 Searching Module
   -  **search apache**

### ℹ️ Viewing Module Info
   -   **info <module_name>**

### ⚙️ Setting Parameters
- `RHOSTS` – Target IP
- `LHOST` – Attacker IP
- `set` – Set locally
- `setg` – Set globally

---

## 🧭 Metasploit Contexts

- `msf6 >` → General console
- `msf6 exploit(...) >` → Exploit context
- `meterpreter >` → Post-exploitation shell
- OS shell → Full system access

---

## ⚔️ Exploitation
  - **exploit**
Successfully executed exploitation after configuring correct parameters.

---

## 🛠️ Practical Skills Gained
- Tab completion
- Payload management
- Clearing configurations
- Understanding Metasploit filesystem structure

---

## 🎓 Learning Outcomes
- Understood exploit–payload relationship
- Gained real-world Metasploit experience
- Improved penetration testing workflow knowledge

---

## 🧪 Lab Platform
- **TryHackMe**


## 🔗 Lab link
 -   ( TryHackMe | Metasploit: Introduction https://share.google/s4b8VAaobfOXrnKAE)
 
## 📄 Detailed Report (PDF)
[View Full PDF Report](reports/metasploit.pdf)
