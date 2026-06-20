# Microsoft 365 Security Lab — MFA Configuration

## Overview
This project demonstrates a basic security configuration lab completed using the Microsoft 365 Admin Center and Microsoft Entra ID. The focus of this lab was on implementing Multi-Factor Authentication (MFA) for user accounts to improve identity security and reduce the risk of unauthorized access.

Due to limitations in the free Microsoft 365 tenant, advanced features such as Conditional Access policies were not available. As a result, the lab focuses specifically on per-user MFA configuration and validation.

---

## Objectives
- Access Microsoft 365 Admin Center
- Configure Multi-Factor Authentication (MFA) for users
- Apply MFA to selected user accounts
- Validate MFA enforcement during login
- Understand basic identity security controls

---

## Tools Used
- Microsoft 365 Admin Center  
- Microsoft Entra ID (Identity Management)

---

## Lab Activities Completed

### 1. Accessed Identity Management Portal
- Logged into Microsoft 365 Admin Center
- Navigated to Microsoft Entra ID user settings

---

### 2. Enabled Multi-Factor Authentication (MFA)
- Located user account security settings
- Enabled MFA on selected user accounts
- Configured authentication method prompts

---

### 3. Applied MFA to Users
- Assigned MFA requirement to:
  - Admin User
  - Helpdesk User
  - Standard User (if applicable)

---

### 4. Tested MFA Enforcement
- Logged in with test accounts
- Verified MFA prompt was triggered during sign-in
- Confirmed authentication required before access was granted

---

## Key Learnings

- MFA significantly improves account security by adding a second verification layer beyond passwords
- Even in a basic tenant, identity protection is a critical security control
- Microsoft Entra ID provides centralized identity and access management
- Free-tier limitations restrict advanced features like Conditional Access policies

---

## Limitations of Lab Environment

- Conditional Access policies were not available in free tenant
- Advanced security reporting and risk-based policies were not accessible
- MFA was applied using per-user configuration instead of policy-based enforcement

---

## Screenshots

Screenshots included in this repository:
- MFA configuration settings
- User account security settings
- Login MFA prompt verification

---

## Future Improvements

If upgraded to a paid or developer tenant, this lab could be expanded to include:
- Conditional Access policies
- Risk-based authentication
- Security defaults enforcement
- Sign-in risk detection
- Advanced identity protection policies

---

## Summary
This lab demonstrates foundational identity security skills using Microsoft 365. It focuses on implementing Multi-Factor Authentication (MFA) as a key security control to protect user accounts from unauthorized access.