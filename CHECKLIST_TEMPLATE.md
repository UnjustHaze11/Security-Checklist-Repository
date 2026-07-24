# Windows Hardening Checklist

## Purpose

Use this checklist to review common Windows workstation or server security controls.

## Scope

Windows 10/11, Windows Server, and domain-joined Windows environments.

## Checklist

### 1. Asset and Baseline Management

- [ ] **P1:** Identify the Windows version, build, hostname, owner, and business purpose.
  - Evidence:
  - Notes:

- [ ] **P1:** Apply a documented Windows security baseline.
  - Evidence:
  - Notes:

- [ ] **P2:** Remove unsupported Windows versions from the environment.
  - Evidence:
  - Notes:

### 2. Accounts and Authentication

- [ ] **P1:** Disable or rename unnecessary local administrator accounts.
  - Evidence:
  - Notes:

- [ ] **P1:** Require multifactor authentication for privileged and remote access.
  - Evidence:
  - Notes:

- [ ] **P1:** Enforce least privilege for users and administrators.
  - Evidence:
  - Notes:

- [ ] **P2:** Review local group membership for Administrators, Remote Desktop Users, and Backup Operators.
  - Evidence:
  - Notes:

### 3. Patch and Update Management

- [ ] **P1:** Confirm current security updates are installed.
  - Evidence:
  - Notes:

- [ ] **P1:** Enable automatic update deployment or managed patching.
  - Evidence:
  - Notes:

- [ ] **P2:** Track failed patches and create remediation tickets.
  - Evidence:
  - Notes:

### 4. Endpoint Protection

- [ ] **P1:** Confirm Microsoft Defender or approved endpoint protection is active.
  - Evidence:
  - Notes:

- [ ] **P1:** Enable real-time protection.
  - Evidence:
  - Notes:

- [ ] **P2:** Confirm malware signatures and endpoint agent versions are current.
  - Evidence:
  - Notes:

### 5. Network and Remote Access

- [ ] **P1:** Disable unused remote access services.
  - Evidence:
  - Notes:

- [ ] **P1:** Restrict Remote Desktop Protocol access by firewall, VPN, or jump host.
  - Evidence:
  - Notes:

- [ ] **P2:** Enable Windows Firewall for domain, private, and public profiles.
  - Evidence:
  - Notes:

### 6. Logging and Auditing

- [ ] **P1:** Enable account logon, privilege use, process creation, and policy change auditing.
  - Evidence:
  - Notes:

- [ ] **P1:** Forward security logs to a SIEM or central log system.
  - Evidence:
  - Notes:

- [ ] **P2:** Confirm logs are retained long enough for investigations.
  - Evidence:
  - Notes:

### 7. Data Protection

- [ ] **P1:** Enable full-disk encryption on laptops and high-risk systems.
  - Evidence:
  - Notes:

- [ ] **P2:** Restrict removable media where appropriate.
  - Evidence:
  - Notes:

- [ ] **P2:** Confirm sensitive data is not stored in public or temporary folders.
  - Evidence:
  - Notes:

### 8. Backup and Recovery

- [ ] **P1:** Confirm backups exist for critical Windows systems.
  - Evidence:
  - Notes:

- [ ] **P1:** Test at least one restore procedure.
  - Evidence:
  - Notes:

- [ ] **P2:** Protect backups from unauthorized modification or deletion.
  - Evidence:
  - Notes:

## References

- Microsoft. Security Compliance Toolkit.
- Microsoft. Windows security baselines.
- National Institute of Standards and Technology. SP 800-123, Guide to General Server Security.
- Center for Internet Security. CIS Critical Security Controls.
