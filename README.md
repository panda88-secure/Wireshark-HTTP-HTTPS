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
![HTTP Capture](./screenshots/http-credentials.png)

### 🔐 HTTPS Traffic – Encrypted
![HTTPS Capture]([./screenshots/https-encrypted.png](https://github.com/panda88-secure/Wireshark-HTTP-HTTPS/blob/main/HTTPS%20ENCRYPTED%20.png)

---

## 📥 Project Report (PDF)
📄 [Download Full Report](./Wireshark_Report.pdf)

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

