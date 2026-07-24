# Linux Hardening Checklist

## Purpose

Use this checklist to review common Linux server and workstation security controls.

## Scope

Ubuntu, Debian, Red Hat, Rocky Linux, AlmaLinux, Kali Linux lab systems, and general Linux servers.

## Checklist

### 1. System Inventory and Baseline

- [ ] **P1:** Record hostname, IP address, operating system version, kernel version, and system owner.
  - Evidence:
  - Notes:

- [ ] **P1:** Confirm the Linux distribution is supported and receiving security updates.
  - Evidence:
  - Notes:

- [ ] **P2:** Document the system role and required services.
  - Evidence:
  - Notes:

### 2. User and Privilege Management

- [ ] **P1:** Disable unused user accounts.
  - Evidence:
  - Notes:

- [ ] **P1:** Restrict sudo access to authorized administrators only.
  - Evidence:
  - Notes:

- [ ] **P1:** Disable direct root SSH login.
  - Evidence:
  - Notes:

- [ ] **P2:** Review accounts with UID 0.
  - Evidence:
  - Notes:

### 3. SSH Security

- [ ] **P1:** Use SSH keys where possible.
  - Evidence:
  - Notes:

- [ ] **P1:** Disable password-based SSH login for high-risk systems.
  - Evidence:
  - Notes:

- [ ] **P2:** Limit SSH access by firewall rules, VPN, or allowlists.
  - Evidence:
  - Notes:

- [ ] **P2:** Monitor repeated failed SSH login attempts.
  - Evidence:
  - Notes:

### 4. Patch Management

- [ ] **P1:** Apply current security updates.
  - Evidence:
  - Notes:

- [ ] **P2:** Enable automatic security updates when appropriate.
  - Evidence:
  - Notes:

- [ ] **P2:** Track packages that cannot be updated immediately.
  - Evidence:
  - Notes:

### 5. Firewall and Services

- [ ] **P1:** Enable a host firewall such as ufw, firewalld, or nftables.
  - Evidence:
  - Notes:

- [ ] **P1:** Disable unnecessary services.
  - Evidence:
  - Notes:

- [ ] **P2:** Confirm listening ports match the approved system purpose.
  - Evidence:
  - Notes:

### 6. File and Directory Permissions

- [ ] **P1:** Protect sensitive files such as `/etc/shadow`, SSH keys, and application secrets.
  - Evidence:
  - Notes:

- [ ] **P2:** Review world-writable files and directories.
  - Evidence:
  - Notes:

- [ ] **P2:** Confirm application files are owned by the correct service accounts.
  - Evidence:
  - Notes:

### 7. Logging and Monitoring

- [ ] **P1:** Confirm system logs are enabled.
  - Evidence:
  - Notes:

- [ ] **P1:** Send logs to a central logging platform or SIEM.
  - Evidence:
  - Notes:

- [ ] **P2:** Monitor authentication logs for failed logins and privilege escalation.
  - Evidence:
  - Notes:

### 8. Backup and Recovery

- [ ] **P1:** Confirm critical Linux systems have backups.
  - Evidence:
  - Notes:

- [ ] **P1:** Test restore procedures.
  - Evidence:
  - Notes:

- [ ] **P2:** Protect backup credentials and backup storage.
  - Evidence:
  - Notes:

## References

- National Institute of Standards and Technology. SP 800-123, Guide to General Server Security.
- Canonical. Ubuntu security documentation.
- Center for Internet Security. CIS Critical Security Controls.
