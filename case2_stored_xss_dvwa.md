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
