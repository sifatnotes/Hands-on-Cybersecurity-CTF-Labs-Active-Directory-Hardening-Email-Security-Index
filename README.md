# Hands-on-Cybersecurity-CTF-Labs-Active-Directory-Hardening-Email-Security-Index
A structured index of practical cybersecurity CTF labs focusing on Active Directory security, domain trusts, AD CS, delegation control, gMSAs, SMTP mail flow, POP3/IMAP abuse detection, and infrastructure defense.
# Hands-On Cybersecurity & CTF Lab Collection

Welcome to the **Hands-On Cybersecurity & CTF Lab Collection**. This repository provides a clean, searchable index of hands-on cybersecurity labs and Capture The Flag (CTF) exercises designed for security engineers, penetration testers, SOC analysts, and cybersecurity students.

This collection focuses on two core enterprise defense domains: **Active Directory Architecture & Identity Security** and **Mail Protocol Infrastructure & Operations**.

---

## Lab Collection Index

### 1. Active Directory Security & Identity Architecture
* **Secure AD Design**  
  *Lab Link:* [https://learn.secbyte.org/ctf/secure-ad-design](https://learn.secbyte.org/ctf/secure-ad-design)  
  *Focus:* Architecture principles for hardening Active Directory enterprise boundaries, organizational boundaries, and attack surface reduction.

* **Tiered Administration**  
  *Lab Link:* [https://learn.secbyte.org/ctf/tiered-administration](https://learn.secbyte.org/ctf/tiered-administration)  
  *Focus:* Designing Tier 0, Tier 1, and Tier 2 administrative isolation models to stop lateral movement and credential theft.

* **Forest Administration, Active Directory Trusts & Delegation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/forest-administration-active-directory-trusts-delegation](https://learn.secbyte.org/ctf/forest-administration-active-directory-trusts-delegation)  
  *Focus:* Analyzing multi-forest architectures, trust relationships, SID filtering, and administrative delegation across boundaries.

* **Domain Replication, Active Directory Trust, and Abuse Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/domain-replication-active-directory-trust-and-abuse-fundamen](https://learn.secbyte.org/ctf/domain-replication-active-directory-trust-and-abuse-fundamen)  
  *Focus:* Understanding domain controller replication mechanics, DCSync attack vectors, trust abusing patterns, and detection signals.

* **Certificate Services (AD CS) - Medium**  
  *Lab Link:* [https://learn.secbyte.org/ctf/certificate-services-ad-cs-medium](https://learn.secbyte.org/ctf/certificate-services-ad-cs-medium)  
  *Focus:* Investigating Active Directory Certificate Services misconfigurations, vulnerable certificate templates, and privilege escalation mechanics.

* **Group Managed Service Accounts: Enumeration, Abuse, and Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/group-managed-service-accounts-enumeration-abuse-and-defense](https://learn.secbyte.org/ctf/group-managed-service-accounts-enumeration-abuse-and-defense)  
  *Focus:* Auditing gMSA password retrieval permissions, enumerating active service accounts, and hardening account security boundaries.

* **Service Accounts Identity & Privilege Abuse Patterns**  
  *Lab Link:* [https://learn.secbyte.org/ctf/service-accounts-identity-privilege-abuse-patterns](https://learn.secbyte.org/ctf/service-accounts-identity-privilege-abuse-patterns)  
  *Focus:* Identifying Kerberoasting, SPN exposure, excess privilege granting, and credential misuse in legacy service accounts.

* **Delegation of Control Active Directory Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/delegation-of-control-active-directory-lab](https://learn.secbyte.org/ctf/delegation-of-control-active-directory-lab)  
  *Focus:* Uncovering unconstrained, constrained, and resource-based constrained delegation misconfigurations inside AD environments.

* **Organizational Units Active Directory Delegation and Control**  
  *Lab Link:* [https://learn.secbyte.org/ctf/organizational-units-active-directory-delegation-and-control](https://learn.secbyte.org/ctf/organizational-units-active-directory-delegation-and-control)  
  *Focus:* Auditing OU structures, Access Control Lists (ACLs), Access Control Entries (ACEs), and inherited permissions.

### 2. Email Infrastructure & Mail Protocol Defense
* **POP3 and IMAP Email Retrieval Security and Abuse Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/pop3-and-imap-email-retrieval-security-and-abuse-detection](https://learn.secbyte.org/ctf/pop3-and-imap-email-retrieval-security-and-abuse-detection)  
  *Focus:* Analyzing plain text vs encrypted mail access, detecting brute-force credential stuffing, and monitoring mailbox exfiltration.

* **SMTP Fundamentals, Mail Flow Exposure, and Abuse Prevention**  
  *Lab Link:* [https://learn.secbyte.org/ctf/smtp-fundamentals-mail-flow-exposure-abuse-prevention](https://learn.secbyte.org/ctf/smtp-fundamentals-mail-flow-exposure-abuse-prevention)  
  *Focus:* Analyzing Simple Mail Transfer Protocol transaction flows, open relay misuse, envelope command spoofing, and MTA defense.

* **Email Infrastructure Fundamentals & Security Operations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/email-infrastructure-fundamentals-security-operations](https://learn.secbyte.org/ctf/email-infrastructure-fundamentals-security-operations)  
  *Focus:* Core security operations across mail servers, DNS MX routing, logging, transport agent auditing, and perimeter mail flow monitoring.

---

## Learning Path

### Path A: Active Directory Identity Architecture
1. **Foundations & Structure:** Start with [Organizational Units Active Directory Delegation and Control](https://learn.secbyte.org/ctf/organizational-units-active-directory-delegation-and-control) and [Secure AD Design](https://learn.secbyte.org/ctf/secure-ad-design).
2. **Access & Privilege Boundaries:** Advance through [Tiered Administration](https://learn.secbyte.org/ctf/tiered-administration) and [Delegation of Control Active Directory Lab](https://learn.secbyte.org/ctf/delegation-of-control-active-directory-lab).
3. **Service Accounts & Identity:** Harden services using [Service Accounts Identity & Privilege Abuse Patterns](https://learn.secbyte.org/ctf/service-accounts-identity-privilege-abuse-patterns) and [Group Managed Service Accounts](https://learn.secbyte.org/ctf/group-managed-service-accounts-enumeration-abuse-and-defense).
4. **Enterprise & Cross-Domain Control:** Master complex identity attacks with [Certificate Services (AD CS) - Medium](https://learn.secbyte.org/ctf/certificate-services-ad-cs-medium), [Domain Replication & Abuse Fundamentals](https://learn.secbyte.org/ctf/domain-replication-active-directory-trust-and-abuse-fundamen), and [Forest Administration & Trusts](https://learn.secbyte.org/ctf/forest-administration-active-directory-trusts-delegation).

### Path B: Mail Infrastructure Security
1. **Core Operations:** Begin with [Email Infrastructure Fundamentals & Security Operations](https://learn.secbyte.org/ctf/email-infrastructure-fundamentals-security-operations).
2. **Transfer Security:** Practice relay control via [SMTP Fundamentals, Mail Flow Exposure, and Abuse Prevention](https://learn.secbyte.org/ctf/smtp-fundamentals-mail-flow-exposure-abuse-prevention).
3. **Access Monitoring:** Complete protocol defense with [POP3 and IMAP Email Retrieval Security and Abuse Detection](https://learn.secbyte.org/ctf/pop3-and-imap-email-retrieval-security-and-abuse-detection).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Launch the corresponding challenge via the provided Learn SecByte lab links.
3. Review scenario notes, technical topologies, and task requirements.
4. Perform interactive technical checks, enumeration, or configuration fixes to capture flags.
5. Apply defensive patterns directly to enterprise hardening blueprints.

---

## Target Audience

* **Active Directory Administrators:** Learn privilege separation, delegation cleanup, and secure domain design.
* **SOC & Security Analysts:** Understand AD event logs, DCSync audit trails, gMSA abuse patterns, and mail protocol anomalies.
* **Penetration Testers:** Understand modern AD delegation abuse, AD CS exploitation vectors, and mail service exposures.
* **Cybersecurity Students:** Practice real-world infrastructure operations with hands-on environments.

---

## Disclaimer

The links in this index point directly to official hands-on security labs hosted on Learn SecByte. All materials and exercises are provided strictly for authorized security training, defensive learning, and educational research. Unsanctioned exploitation of target networks or identity systems is prohibited.
