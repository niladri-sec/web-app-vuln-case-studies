# 🔓 Case Study 1: Insecure Direct Object Reference (IDOR) – Juice Shop

## 📋 Vulnerability Summary

- Platform: OWASP Juice Shop
- Reproduced From: HackerOne write-up (based on IDOR in e-commerce apps)

## 🧪 Steps to Reproduce

1. Log in as a normal user.
2. Navigate to `/#/order-history`.
3. Use browser DevTools → Network tab.
4. Observe GET request for `/rest/orders/<orderId>`.
5. Change the ID to another number.
6. You can now access another user’s order data.

## 🧠 Impact

- Data exposure across multiple user accounts.
- Violates user privacy.
- Could escalate to full account compromise.

## 🛠️ Remediation

- Implement authorization checks on all sensitive resources.
- Never rely on client-side logic to enforce access controls.
- Use session tokens or ownership checks server-side.

## 🖼️ Screenshot

![IDOR Exploit](screenshots/idor_steps.png)
