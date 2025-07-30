# 🛡️ Wireshark Lab – HTTP vs HTTPS Traffic Analysis

## 📄 Project Overview
This project demonstrates how sensitive data (like usernames and passwords) is exposed when using HTTP, and how HTTPS protects such data using encryption.  
Using **Wireshark**, I captured and compared both types of traffic to simulate a real SOC investigation scenario.

---

## 🧪 Lab Summary

| Protocol | Data Visibility             | Risk      |
|----------|-----------------------------|-----------|
| HTTP     | Username & Password visible | 🔴 High   |
| HTTPS    | Data encrypted               | 🟢 Secure |

---

## 🧰 Tools Used
- **Wireshark**
- **Browser** (tested on `testphp.vulnweb.com` and `example.com`)

---

## 📸 Screenshots

### 🔓 HTTP Traffic – Credentials Visible
![HTTP Capture] (https://github.com/panda88-secure/Wireshark-HTTP-HTTPS/blob/main/HTTPS%20PLAIN%20TEXT.png)

### 🔐 HTTPS Traffic – Encrypted
![HTTPS Capture](https://github.com/panda88-secure/Wireshark-HTTP-HTTPS/blob/main/HTTPS%20ENCRYPTED%20.png)

---

## 📥 Project Report (PDF)
📄 [Download Full Report](https://github.com/panda88-secure/Wireshark-HTTP-HTTPS/blob/main/wireshark%20report.pdf)

Includes:
- Step-by-step lab process  
- Findings and screenshots  
- Security recommendations (TLS, HSTS, secure cookies)

---

## ✅ Recommendations
- Enforce **HTTPS (TLS 1.2+)** on all websites  
- Use **HSTS** to prevent fallback to HTTP  
- Enable **HttpOnly** and **Secure flags** on cookies  
- Monitor traffic regularly using tools like Wireshark  ``

---

## 🏁 Status
✅ Completed | 🕵️ SOC & Compliance Ready | 📂 Uploaded: July 2025

---
---

## 🙋‍♀️ About Me
**Swarupa Pawbake**  
- Entry-Level SOC Analyst | VAPT | CEH (Pursuing)  
- Hands-on with Splunk, Wazuh, Nessus, Burp Suite  
- 🌐 Connect with me on [LinkedIn](www.linkedin.com/in/swarupa-pawbake-58443a2a7) 

