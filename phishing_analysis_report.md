# Phishing Email Analysis Report

## Task 2 - Cyber Security Internship
**Analyst:** Nithin K R  
**CIN ID:** FIT/MAY26/CS8770  
**Date:** 29 May 2026  

---

## Sample Email Details
- **From:** security-alert@paypa1.com
- **Subject:** URGENT: Your Account Has Been Suspended!
- **Suspicious URL:** http://paypal-secure-login.xyz/verify

---

## Phishing Indicators Found

### 1. Domain Spoofing
- Used `paypa1.com` (number 1) instead of `paypal.com`
- Tricks users who don't read carefully

### 2. Urgency & Fear Tactics
- "PERMANENTLY DELETED within 24 hours"
- Forces victim to act without thinking

### 3. Suspicious Links
- URL: `paypal-secure-login.xyz`
- Not official PayPal domain
- Uses `.xyz` TLD to appear legitimate

### 4. Sensitive Information Request
- Asking for credit card number and password
- Legitimate companies NEVER ask this via email

### 5. Spelling/Grammar Errors
- "Departement" instead of "Department"
- Sign of non-professional/foreign attacker

### 6. Generic Greeting
- "Dear Valued Customer" instead of real name
- Mass-sent phishing campaign indicator

### 7. Email Header Red Flags
- SPF: FAIL
- DKIM: FAIL  
- DMARC: FAIL
- Originating IP from suspicious location

---

## Risk Assessment
| Risk Level | Reason |
|-----------|--------|
| 🔴 HIGH | Multiple spoofing indicators |
| 🔴 HIGH | Credential harvesting attempt |
| 🟡 MEDIUM | Could fool non-technical users |

---

## Recommended Actions
1. Do NOT click any links
2. Do NOT provide any information
3. Mark as spam/phishing in email client
4. Report to Anti-Phishing Working Group (reportphishing@apwg.org)
5. Report to actual PayPal at phishing@paypal.com
6. Delete the email immediately

---

## Key Learnings
- Always check sender domain carefully
- Legitimate companies never ask for passwords via email
- Check SPF/DKIM/DMARC in email headers
- Urgent language is a major red flag
