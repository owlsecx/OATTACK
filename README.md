<div align="center">

# 🦉 OAttack

**Pentest Toolkit**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

*Part of the [OwlSec](https://owlsec.org) Toolkit*
```
██████╗  █████╗ ████████╗████████╗ █████╗  ██████╗██╗  ██╗
██╔═══██╗██╔══██╗╚══██╔══╝╚══██╔══╝██╔══██╗██╔════╝██║ ██╔╝
██║   ██║███████║   ██║      ██║   ███████║██║     █████╔╝
██║   ██║██╔══██║   ██║      ██║   ██╔══██║██║     ██╔═██╗
╚██████╔╝██║  ██║   ██║      ██║   ██║  ██║╚██████╗██║  ██╗
 ╚═════╝ ╚═╝  ╚═╝   ╚═╝      ╚═╝   ╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
         Recon | Vuln Scan | Password Audit | Web Fingerprint
```

</div>

---

## 📌 Overview

**OAttack** is a pentest toolkit designed for authorized security assessments. It covers the full assessment workflow — from reconnaissance and vulnerability scanning to password auditing and web fingerprinting.

---

## 🖥️ Menu Options

| Option | Module | Description |
|--------|--------|-------------|
| `[1]` | Recon | Subdomain enumeration, port scan, banner grabbing |
| `[2]` | Vuln Scanner | HTTP headers, SSL issues, misconfigurations |
| `[3]` | Password Audit | Hash cracking, strength analysis, default credentials |
| `[4]` | Web Fingerprint | CMS, WAF, and tech stack detection |
| `[5]` | SSL/TLS Checker | Certificate info, expiry, weak config detection |
| `[H]` | Help | Show help page |
| `[0]` | Exit | Quit OAttack |

---

## 🔍 Module Details

### 1. Recon
- Subdomain enumeration via wordlist + certificate logs
- TCP port scan with service banner grabbing
- Hostname resolution and reverse DNS lookup
- Open service and version identification

### 2. Vuln Scanner
- HTTP security header checks (CSP, HSTS, X-Frame-Options)
- Detects exposed directory listings and backup files
- Identifies default error pages leaking server info
- Checks for open redirect and CORS misconfigurations

### 3. Password Audit
- Wordlist-based hash cracking (MD5, SHA1, SHA256)
- Password strength analyser with scoring
- Default credential list for common services
- Dictionary matching only — no active brute-force

### 4. Web Fingerprint
- CMS detection (WordPress, Joomla, etc.)
- WAF identification
- Technology stack fingerprinting

### 5. SSL/TLS Checker
- Certificate details and expiry dates
- Weak cipher and protocol detection

---

## ⚙️ Requirements

- Linux (any distro)
- The tool is pre-built — no Python installation needed

---

## ⚠️ Legal Disclaimer

> **THIS TOOL IS FOR EDUCATIONAL AND AUTHORIZED AUDIT PURPOSES ONLY.**  
> Unauthorized use against systems you do not own or have written permission to test is illegal and unethical.  
> Always obtain written consent before testing.  
> The developer is not responsible for any misuse.

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

> 🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
