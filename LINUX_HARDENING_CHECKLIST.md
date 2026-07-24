# Cloud Security Checklist

## Purpose

Use this checklist to review common security controls for cloud services and cloud-hosted workloads.

## Scope

AWS, Microsoft Azure, Google Cloud, Microsoft 365, SaaS applications, identity platforms, cloud storage, and cloud workloads.

## Checklist

### 1. Governance and Ownership

- [ ] **P1:** Identify the business owner, technical owner, and data owner for each cloud service.
  - Evidence:
  - Notes:

- [ ] **P1:** Document the shared responsibility model for the cloud service.
  - Evidence:
  - Notes:

- [ ] **P2:** Track cloud services in an approved asset inventory.
  - Evidence:
  - Notes:

### 2. Identity and Access Management

- [ ] **P1:** Require MFA for administrator accounts.
  - Evidence:
  - Notes:

- [ ] **P1:** Use least privilege access for users, groups, roles, and service accounts.
  - Evidence:
  - Notes:

- [ ] **P1:** Remove inactive users and stale access keys.
  - Evidence:
  - Notes:

- [ ] **P2:** Review privileged roles on a regular schedule.
  - Evidence:
  - Notes:

### 3. Logging and Monitoring

- [ ] **P1:** Enable cloud audit logging.
  - Evidence:
  - Notes:

- [ ] **P1:** Send important cloud logs to a SIEM or central monitoring platform.
  - Evidence:
  - Notes:

- [ ] **P2:** Alert on suspicious administrator activity, impossible travel, disabled logging, and unusual data access.
  - Evidence:
  - Notes:

### 4. Data Protection

- [ ] **P1:** Encrypt sensitive data at rest.
  - Evidence:
  - Notes:

- [ ] **P1:** Encrypt sensitive data in transit.
  - Evidence:
  - Notes:

- [ ] **P1:** Restrict public access to cloud storage unless explicitly approved.
  - Evidence:
  - Notes:

- [ ] **P2:** Classify data stored in cloud applications.
  - Evidence:
  - Notes:

### 5. Network Security

- [ ] **P1:** Restrict inbound access to only required ports and trusted sources.
  - Evidence:
  - Notes:

- [ ] **P1:** Avoid exposing management interfaces directly to the internet.
  - Evidence:
  - Notes:

- [ ] **P2:** Use private networking, VPNs, or bastion hosts where appropriate.
  - Evidence:
  - Notes:

### 6. Backup and Recovery

- [ ] **P1:** Confirm backups are enabled for critical cloud workloads.
  - Evidence:
  - Notes:

- [ ] **P1:** Test restore procedures.
  - Evidence:
  - Notes:

- [ ] **P2:** Protect backups from deletion, tampering, and unauthorized access.
  - Evidence:
  - Notes:

### 7. SaaS Security

- [ ] **P1:** Review tenant-wide security settings for major SaaS applications.
  - Evidence:
  - Notes:

- [ ] **P1:** Disable legacy authentication where possible.
  - Evidence:
  - Notes:

- [ ] **P2:** Use secure configuration baselines for Microsoft 365 and other cloud business applications.
  - Evidence:
  - Notes:

### 8. Continuous Review

- [ ] **P2:** Run recurring cloud configuration reviews.
  - Evidence:
  - Notes:

- [ ] **P2:** Track misconfigurations to closure.
  - Evidence:
  - Notes:

- [ ] **P3:** Review cloud costs for abandoned or forgotten assets that may still create risk.
  - Evidence:
  - Notes:

## References

- Cybersecurity and Infrastructure Security Agency. Secure Cloud Business Applications project.
- Cybersecurity and Infrastructure Security Agency. Cybersecurity Performance Goals.
- Center for Internet Security. CIS Critical Security Controls.
