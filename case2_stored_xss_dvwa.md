# 💥 Case Study 2: Stored Cross-Site Scripting (XSS) – DVWA

## 📋 Vulnerability Summary

- Platform: Damn Vulnerable Web App (DVWA) – Medium Security
- Type: Stored XSS

## 🧪 Steps to Reproduce

1. Log in to DVWA as any user.
2. Go to “Stored XSS” under the XSS tab.
3. Enter payload:
   ```html
   <script>alert('XSS')</script>
4. Submit and refresh the page.
5. The alert will pop up showing execution of the payload

## 🧠 Impact
Payload is stored in the backend and executed in every visitor’s browser.
Can lead to session hijacking, phishing, or privilege escalation.

## 🛠️ Remediation
Sanitize inputs using frameworks like OWASP ESAPI.
Escape output on render.
Use Content Security Policy (CSP) to reduce risk
