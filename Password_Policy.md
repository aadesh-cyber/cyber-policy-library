# 🔐 Password Policy

**Purpose:**  
This policy defines the minimum standards and best practices for password creation, management, and protection across all systems and services owned or operated by [Organization Name].

---

## 1. Scope  
This policy applies to:
- All employees, contractors, consultants, interns, and third-party users
- Any systems, platforms, applications, or endpoints requiring authentication
- Cloud, on-premise, and hybrid environments

---

## 2. Policy Requirements

### 🔑 2.1 Password Creation
- Must be **at least 12 characters long**
- Must include **uppercase, lowercase, numbers, and special characters**
- Should **not contain dictionary words or personal identifiers** (e.g., name, birthday)
- Passphrases (e.g., `Purple-Lion-Dances-7!`) are encouraged for memorability and strength

### 🔁 2.2 Password Expiry & Rotation
- Passwords must be changed **every 180 days**
- Users may **not reuse the last 5 passwords**
- Forced resets apply after suspected compromise or phishing incidents

### 🔄 2.3 Multi-Factor Authentication (MFA)
- MFA is **mandatory** for:
  - Admin accounts
  - Remote access/VPN
  - Cloud services (e.g., AWS, Microsoft 365)
  - Access to critical or sensitive systems

### 🚫 2.4 Prohibited Password Practices
- No password sharing under any circumstances
- Do not write down passwords on paper or sticky notes
- Avoid storing plaintext passwords in browsers, spreadsheets, or notepads
- Do not use “default” credentials (e.g., `admin/admin`) on any device or application

---

## 3. Password Storage & Transmission

- Passwords must be stored **only using secure, salted cryptographic hashing algorithms** (e.g., SHA-256 + salt, bcrypt)
- Passwords must **never be transmitted in plaintext**
- Tools like password managers (e.g., Bitwarden, 1Password) are **approved for secure storage**

---

## 4. Enforcement

Violations of this policy may result in disciplinary action, including:
- Account suspension
- Mandatory security awareness training
- Escalation to HR or Legal depending on the severity of the incident

---

## 5. Roles & Responsibilities

| **Role**             | **Responsibility**                                      |
|----------------------|----------------------------------------------------------|
| IT Security Team     | Enforce password policies via GPOs, MFA, and monitoring |
| End Users            | Comply with secure password creation and usage          |
| HR & Onboarding Team | Ensure new users receive password training              |
| System Admins        | Disable unused accounts and rotate default credentials  |

---

## 6. Compliance Standards

This policy supports compliance with:
- ISO/IEC 27001:2022 — A.9.2 (User Access Management)
- NIST SP 800-63B — Digital Identity Guidelines
- PCI DSS v4.0 — Requirement 8 (Identify and authenticate access)
- UK GDPR / DPA 2018 — Data protection by design and by default

---

## 7. Review Cycle

- **Review Frequency:** Annually or post major security incident
- **Owner:** Head of Cybersecurity / GRC Team
- **Version Control:** Maintained in internal compliance repository

---

> 🗓️ **Last Updated:** July 2025  
> 📧 For questions, contact: `security@yourdomain.com`  
> 🔒 Classification: Internal Use Only
