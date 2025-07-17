# 🔥 Task 2 Report: Basic Firewall Configuration with UFW

## 🎯 Objective
To set up and configure a basic firewall using **UFW (Uncomplicated Firewall)** on a Linux system. The goal was to allow SSH access and deny HTTP traffic.

---

## 🧰 Tools Used
- Ubuntu via Windows Subsystem for Linux (WSL)
- UFW (Uncomplicated Firewall)

---

## ⚙️ Steps Performed

1. **Installed UFW:**
   ```bash
   sudo apt update
   sudo apt install ufw
    sudo ufw enable
   sudo ufw allow ssh
    sudo ufw deny http

   sudo ufw status numbered
Status: active

     To                         Action      From
     --                         ------      ----
[ 1] 22/tcp                     ALLOW IN    Anywhere
[ 2] 80/tcp                     DENY IN     Anywhere
[ 3] 22/tcp (v6)                ALLOW IN    Anywhere (v6)
[ 4] 80/tcp (v6)                DENY IN     Anywhere (v6)<img width="1317" height="874" alt="Screenshot 2025-07-17 215202" src="https://github.com/user-attachments/assets/f05e0b93-2afb-4e6a-8c83-766093288240" />
<img width="1219" height="1060" alt="Screenshot 2025-07-17 215151" src="https://github.com/user-attachments/assets/76cbd899-03de-46f3-9b66-ed80c8399ed8" />
