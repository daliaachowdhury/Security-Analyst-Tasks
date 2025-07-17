# Task 3: Vulnerability Scanning using Nmap

## 🔍 Objective
Perform a basic vulnerability scan using Nmap’s built-in vulnerability detection scripts and save the results.

## 🧰 Tools Used
- Nmap 7.94SVN
- OS: Windows 10 (with WSL Ubuntu)

## 🛠️ Command Used
```bash
nmap -vv --script vuln -p 22,80,9929,31337 scanme.nmap.org -oN vuln_scan.txt
📄 Output
The scan was performed on scanme.nmap.org targeting 4 ports.

Script: vuln scanned for various known vulnerabilities like:

CSRF

XSS

WordPress detection

JSONP

Scan completed successfully and saved to vuln_scan.txt.<img width="1860" height="1045" alt="Screenshot 2025-07-17 220956" src="https://github.com/user-attachments/assets/74f7286f-d644-45b7-8c0a-43e5c1a6de48" />
