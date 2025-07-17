# 🛠️ Task 1 Report: Basic Network Scanning with Nmap

## 🎯 Objective
The goal of this task was to perform a basic network scan using **Nmap** to identify open ports and running services on a local or public machine.

---

## 🧰 Tools Used
- Nmap v7.97 (Windows + WSL)
- Terminal (CMD + Ubuntu WSL)

---

## ⚙️ Steps Performed

1. **Installed Nmap:**
   - On Windows via the official `.exe` installer.
   - Verified installation using `nmap --version`.

2. **Scanned Localhost:**
   ```bash
   nmap -sV 127.0.0.1

3. Scanned External Host (ScanMe):

bash

Edit
nmap -sV scanme.nmap.org -oN nmap_scan_results.txt

4.Captured and analyzed output

Identified open ports and services.

Saved output to nmap_scan_results.txt.

Took screenshots for documentation.

📄 Key Output Summary
pgsql

Edit
PORT     STATE SERVICE       VERSION
135/tcp  open  msrpc         Microsoft Windows RPC
445/tcp  open  microsoft-ds?
2869/tcp open  http          Microsoft HTTPAPI httpd 2.0
3306/tcp open  mysql         MySQL 8.0.40
5432/tcp open  postgresql    PostgreSQL DB 9.6.0 or later
🧠 Analysis of Ports
Port	Service	Description
135	Microsoft RPC	Used by Windows for Remote Procedure Call services.
445	SMB (microsoft-ds)	Handles file sharing in Windows (SMB).
2869	HTTP	Common for UPnP devices or HTTP APIs.
3306	MySQL	Database service port; vulnerable if exposed.
5432	PostgreSQL	Another database port; security risk if unprotected.

📸 Supporting Files
nmap_scan_results.txt – Output of external scan

screenshot1.png – Nmap results terminal screenshot

✅ Task Outcome
Successfully identified open ports and services on both localhost and public server. Findings were documented with explanations and saved for review.

🧑‍💻 Author
Dalia Chowdhury
Security Analyst Intern
GitHub: github.com/daliaachowdhury


