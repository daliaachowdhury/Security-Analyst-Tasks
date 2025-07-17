# 🛡️ Task 4: Research Report on Common Network Security Threats

## 🎯 Objective
To study and present a research-based report on common network security threats such as **Denial of Service (DoS) attacks**, **Man-in-the-Middle (MITM)** attacks, and **Spoofing**, along with examples and mitigation techniques.

---

## 🔐 1. Denial of Service (DoS) Attack

### 📌 Description:
A **DoS attack** is designed to make a machine or network resource unavailable to its intended users by flooding it with traffic or sending information that triggers a crash.

### ⚙️ How It Works:
- The attacker sends a **huge volume of traffic** to overwhelm a system or network.
- Legitimate users are denied access because the server is too busy or down.

### 🔥 Real-World Example:
- In 2016, the **Dyn DNS** attack using the **Mirai Botnet** took down major websites like Twitter, Netflix, and Reddit by flooding DNS servers.

### 🛡️ Mitigation:
- Use firewalls and intrusion detection systems.
- Implement **rate-limiting** on servers.
- Use **cloud-based DDoS protection services** like Cloudflare or AWS Shield.

---

## 🕵️ 2. Man-in-the-Middle (MITM) Attack

### 📌 Description:
An attacker secretly intercepts and possibly alters communication between two parties who believe they are directly communicating with each other.

### ⚙️ How It Works:
- The attacker positions themselves between the victim and the server.
- They can eavesdrop or modify messages in real-time.

### 🔥 Real-World Example:
- An attacker on a public Wi-Fi network intercepting login credentials using tools like **Ettercap** or **Wireshark**.

### 🛡️ Mitigation:
- Always use **HTTPS** and **SSL/TLS encryption**.
- Avoid using public Wi-Fi for sensitive tasks.
- Use **VPNs** for secure tunneling.

---

## 🌀 3. Spoofing Attacks

### 📌 Description:
**Spoofing** is when an attacker masquerades as a trusted entity by falsifying data to gain access or spread malware.

### Types of Spoofing:
- **IP Spoofing:** Faking an IP address to bypass firewalls.
- **Email Spoofing:** Sending fake emails that appear to come from legitimate sources.
- **DNS Spoofing:** Redirecting users to malicious websites.

### 🔥 Real-World Example:
- **Email spoofing** is widely used in phishing attacks to steal user credentials or deliver malware.

### 🛡️ Mitigation:
- Use **email authentication protocols** like SPF, DKIM, and DMARC.
- Deploy **anti-spoofing filters** and **firewalls**.
- Verify all sensitive communications.

---

## 🧠 Summary Table

| Threat Type      | Impact                         | Real-World Use Case         | Prevention Method                  |
|------------------|--------------------------------|-----------------------------|------------------------------------|
| DoS Attack       | System crashes, downtime       | Dyn DNS/Mirai Botnet        | Firewalls, rate limiting, DDoS protection |
| MITM Attack      | Data interception, theft       | Public Wi-Fi interception   | Encryption, HTTPS, VPN             |
| Spoofing         | Data theft, redirecting traffic| Email/DNS/IP spoofing       | Authentication protocols, firewalls |

---

## ✅ Conclusion

Understanding these threats is crucial for any security analyst. Preventing them requires a combination of **technical defenses**, **vigilance**, and **user awareness**. As cyber threats evolve, so should our strategies to detect, prevent, and respond.

---

## 👩‍💻 Author

**Dalia Chowdhury**  
Security Analyst Intern  
<img width="1188" height="544" alt="Screenshot 2025-07-17 223416" src="https://github.com/user-attachments/assets/009672d0-25e6-484b-866b-eeaabf5b3ebd" />
<img width="1456" height="1097" alt="Screenshot 2025-07-17 223003" src="https://github.com/user-attachments/assets/491cc9e1-8863-462e-8916-682cc3095a44" />
