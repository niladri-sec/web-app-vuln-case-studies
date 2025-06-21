# 🛡️ Web Application Vulnerability Case Studies – Bug Bounty Report

This project showcases real-world vulnerability recreations based on publicly disclosed bug bounty reports. All exploits were reproduced in intentionally vulnerable test environments such as DVWA and OWASP Juice Shop.

Created and documented by Niladri Dalal.

---

## 🎯 Objective

To demonstrate hands-on offensive security knowledge through the recreation of common web application vulnerabilities like IDOR and XSS using safe testing platforms. Each case study includes reproduction steps, screenshots, impact analysis, and mitigation techniques.

---

## 🧰 Tools & Platforms Used

- 💻 DVWA (Damn Vulnerable Web Application)
- 🛒 OWASP Juice Shop
- 🕵️ Burp Suite Community Edition
- 🌐 Web browser DevTools
- 📷 Screenshots for visual documentation

---

## 📚 Case Studies

### 1️⃣ Insecure Direct Object Reference (IDOR) – Juice Shop  
Reproduction of an IDOR vulnerability that allows unauthorized access to another user's order data by tampering with the order ID.  
🔗 [Read the case](case1_idor_juice_shop.md)

### 2️⃣ Stored Cross-Site Scripting (XSS) – DVWA  
Simulation of a stored XSS attack by injecting a malicious script into the application, leading to execution in victim browsers.  
🔗 [Read the case](case2_stored_xss_dvwa.md)

---

## 📸 Screenshots Preview

| Case | Description               | Image                                 |
|------|---------------------------|----------------------------------------|
| IDOR | Tampered order ID         | ![](screenshots/idor_steps.png)       |
| XSS  | Malicious input injected  | ![](screenshots/xss_payload.png)      |
| XSS  | Alert triggered           | ![](screenshots/xss_output.png)       |

---

## 📌 Disclaimer

All vulnerabilities were tested in isolated and intentionally vulnerable lab environments. This project is strictly for educational purposes. Do not use these techniques on live or unauthorized systems.

---

## 👤 Author

**Niladri Dalal**  
Cyber Security Consultant | VAPT | AppSec | GRC  
📧 Email: niladri.dalal98@gmail.com  
🔗 LinkedIn: [niladri-dalal](https://www.linkedin.com/in/niladri-dalal-70744b1a2/)  
🔗 GitHub: [github.com/your-username](https://github.com/your-username)
