# 🦉 OAttack

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OAttack%20/%20Offensive-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **OAttack** — OWL pentest toolkit — recon, vuln scan, password audit

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OATTACK is a consolidated penetration-testing toolkit that brings reconnaissance, vulnerability scanning, password auditing and web fingerprinting together behind a single interface. It can enumerate subdomains, scan ports with service banners, fingerprint web stacks and inspect SSL/TLS configuration for authorised engagements. Results can be exported to a JSON report for later review or inclusion in a findings package.

---

## ✨ Features

- Domain reconnaissance: subdomain discovery, port scanning and banner collection
- Threaded TCP port scanner with service-banner grabbing
- Web vulnerability scanning for URLs and domains
- Web fingerprinting to identify server technologies
- SSL/TLS inspection of a hostname on a configurable port
- JSON report export of scan results

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OATTACK -r example.com
./OATTACK -v https://example.com
./OATTACK -s example.com --port 443 -o report.json
./OATTACK --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
