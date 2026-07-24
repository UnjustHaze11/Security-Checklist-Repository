# Password Policy Checklist

## Purpose

Use this checklist to review password and authentication practices.

## Scope

Local accounts, cloud accounts, domain accounts, privileged accounts, service accounts, and application accounts.

## Checklist

### 1. Password Length and Strength

- [ ] **P1:** Require strong minimum password length based on account risk.
  - Evidence:
  - Notes:

- [ ] **P1:** Allow long passphrases.
  - Evidence:
  - Notes:

- [ ] **P1:** Block commonly used, expected, or compromised passwords.
  - Evidence:
  - Notes:

- [ ] **P2:** Avoid password rules that encourage predictable patterns.
  - Evidence:
  - Notes:

### 2. Multifactor Authentication

- [ ] **P1:** Require MFA for administrator accounts.
  - Evidence:
  - Notes:

- [ ] **P1:** Require MFA for remote access and cloud applications.
  - Evidence:
  - Notes:

- [ ] **P2:** Prioritize phishing-resistant MFA for high-value accounts.
  - Evidence:
  - Notes:

### 3. Account Lockout and Rate Limiting

- [ ] **P1:** Limit repeated failed login attempts.
  - Evidence:
  - Notes:

- [ ] **P2:** Alert on repeated failed logins, password spraying, or credential stuffing.
  - Evidence:
  - Notes:

- [ ] **P2:** Review lockout thresholds to reduce both brute-force risk and denial-of-service risk.
  - Evidence:
  - Notes:

### 4. Password Storage and Handling

- [ ] **P1:** Store passwords using approved hashing methods.
  - Evidence:
  - Notes:

- [ ] **P1:** Never store passwords in plaintext.
  - Evidence:
  - Notes:

- [ ] **P2:** Protect password reset workflows.
  - Evidence:
  - Notes:

### 5. Privileged and Service Accounts

- [ ] **P1:** Use separate privileged accounts for administration.
  - Evidence:
  - Notes:

- [ ] **P1:** Rotate service account credentials after suspected compromise.
  - Evidence:
  - Notes:

- [ ] **P2:** Store service account secrets in a secrets manager or approved secure vault.
  - Evidence:
  - Notes:

### 6. User Awareness

- [ ] **P2:** Train users to use password managers.
  - Evidence:
  - Notes:

- [ ] **P2:** Train users to report suspicious login prompts and MFA fatigue attempts.
  - Evidence:
  - Notes:

## References

- National Institute of Standards and Technology. SP 800-63B, Digital Identity Guidelines: Authentication and Lifecycle Management.
- Cybersecurity and Infrastructure Security Agency. Cybersecurity Performance Goals.
- Center for Internet Security. CIS Critical Security Controls.
