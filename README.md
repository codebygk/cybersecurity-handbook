# Cybersecurity Handbook

A practical, first-principles cybersecurity handbook covering fundamentals, operating systems, networking, cryptography, reconnaissance, exploitation, defensive security, and ethical hacking.

Priority order inside every section:

- P1 = Must know
- P2 = Should know
- P3 = Good to know

A topic is marked `[x]` only when the corresponding notes are available in this repository.

## Learning Path

**Fundamentals -> Operating Systems -> Networking -> Cryptography -> Reconnaissance -> Web Security -> Exploitation -> Privilege Escalation -> Post Exploitation -> Defensive Security -> Cloud Security -> Advanced Security**

---

# 1. Cybersecurity Fundamentals

## 1.1 Introduction to Cybersecurity

- [x] [What is Cybersecurity (P1)](introduction/what_is_cybersecurity.md)
- [x] [CIA Triad (P1)](introduction/cia_triad.md)
- [x] [Threat, Vulnerability, Risk and Exploit (P1)](introduction/threat_vulnerability_risk_exploit.md)
- [x] [Authentication, Authorization and Accounting (P1)](introduction/aaa.md)
- [ ] Security Principles (P1)
- [ ] Defense in Depth (P1)
- [ ] Principle of Least Privilege (P1)
- [ ] Zero Trust (P1)
- [ ] Security by Design (P1)
- [ ] Attack Surface (P1)
- [ ] Security Controls (P1)
- [ ] Preventive, Detective and Corrective Controls (P2)
- [ ] Physical, Technical and Administrative Controls (P2)
- [ ] Cybersecurity Threat Landscape (P1)
- [ ] Common Cyber Attacks (P1)
- [ ] Cyber Kill Chain (P2)
- [ ] MITRE ATT&CK Overview (P2)

## 1.2 Security Concepts

- [ ] Confidentiality, Integrity and Availability (P1)
- [ ] Non-repudiation (P2)
- [ ] Defense in Depth (P1)
- [ ] Least Privilege (P1)
- [ ] Separation of Duties (P2)
- [ ] Need to Know (P2)
- [ ] Fail Securely (P2)
- [ ] Secure Defaults (P2)
- [ ] Complete Mediation (P2)
- [ ] Threat Modeling (P1)
- [ ] Security Architecture Basics (P2)

---

# 2. Operating Systems

## 2.1 Linux

- [x] [Linux Fundamentals (P1)](linux/linux.md)
- [x] [Linux File System (P1)](linux/file_system.md)
- [x] [Linux Commands (P1)](linux/commands.md)
- [x] [Linux Users and Groups (P1)](linux/users_and_groups.md)
- [x] [Linux File Permissions (P1)](linux/file_permissions.md)
- [x] [Linux Processes (P1)](linux/processes.md)
- [x] [Linux Networking Commands (P1)](linux/networking_commands.md)
- [x] [Linux Package Management (P2)](linux/package_management.md)
- [ ] Linux Services and systemd (P1)
- [ ] Linux Environment Variables (P2)
- [ ] Linux Shell Scripting (P1)
- [ ] Bash Scripting (P1)
- [ ] Cron Jobs and Scheduled Tasks (P2)
- [ ] Linux Logging (P1)
- [ ] syslog and journald (P1)
- [ ] auditd (P2)
- [ ] Linux Security and Hardening (P1)
- [ ] sudo Security (P1)
- [ ] SSH Security (P1)
- [ ] SELinux (P2)
- [ ] AppArmor (P2)
- [ ] Linux Privilege Escalation (P1)

## 2.2 Windows

- [x] [Windows Fundamentals (P1)](windows/windows.md)
- [x] [Windows File System (P1)](windows/file_system.md)
- [x] [Windows Commands (P1)](windows/commands.md)
- [x] [Windows Users and Groups (P1)](windows/users_and_groups.md)
- [x] [Windows Processes (P1)](windows/processes.md)
- [ ] Windows Registry (P1)
- [ ] Windows Services (P1)
- [ ] PowerShell Fundamentals (P1)
- [ ] Windows Event Logs (P1)
- [ ] Windows Security Architecture (P1)
- [ ] Windows Defender (P2)
- [ ] Windows Firewall (P1)
- [ ] UAC (P1)
- [ ] Windows Authentication (P1)
- [ ] Active Directory Fundamentals (P1)
- [ ] Group Policy (P2)
- [ ] Kerberos (P1)
- [ ] NTLM (P1)
- [ ] Windows Privilege Escalation (P1)

---

# 3. Networking

## 3.1 Networking Fundamentals

- [x] [Networking Fundamentals (P1)](networking/networking.md)
- [x] [OSI Model (P1)](networking/osi_model.md)
- [x] [TCP/IP Model (P1)](networking/tcp_ip_model.md)
- [x] [IP Addresses (P1)](networking/ip_addresses.md)
- [x] [MAC Addresses (P1)](networking/mac_addresses.md)
- [x] [Ports and Protocols (P1)](networking/ports_and_protocols.md)
- [x] [TCP (P1)](networking/tcp.md)
- [x] [UDP (P1)](networking/udp.md)
- [x] [DNS (P1)](networking/dns.md)
- [x] [DHCP (P1)](networking/dhcp.md)
- [x] [ARP (P1)](networking/arp.md)
- [ ] ICMP (P1)
- [ ] IPv6 (P2)
- [ ] Subnetting (P1)
- [ ] CIDR (P1)
- [ ] Routing (P1)
- [ ] Switching (P1)
- [ ] VLANs (P2)
- [ ] NAT and PAT (P1)
- [ ] Firewalls (P1)
- [ ] Proxies (P1)
- [ ] VPNs (P1)

## 3.2 Application Protocols

- [ ] HTTP and HTTPS (P1)
- [ ] SSH (P1)
- [ ] FTP and SFTP (P2)
- [ ] SMTP (P2)
- [ ] IMAP and POP3 (P2)
- [ ] SMB (P1)
- [ ] RDP (P1)
- [ ] LDAP (P2)
- [ ] SNMP (P2)
- [ ] NTP (P2)
- [ ] TLS (P1)
- [ ] QUIC and HTTP/3 (P3)

## 3.3 Network Security

- [ ] Packet Sniffing (P1)
- [ ] Wireshark (P1)
- [ ] tcpdump (P1)
- [ ] Network Scanning (P1)
- [ ] Nmap (P1)
- [ ] ARP Spoofing (P1)
- [ ] DNS Attacks (P1)
- [ ] DHCP Attacks (P2)
- [ ] Man-in-the-Middle Attacks (P1)
- [ ] DoS and DDoS (P1)
- [ ] Network Segmentation (P1)
- [ ] IDS and IPS (P1)
- [ ] Network Monitoring (P1)

---

# 4. Cryptography

## 4.1 Cryptography Fundamentals

- [x] [Introduction to Cryptography (P1)](cryptography/cryptography.md)
- [x] [Encryption vs Hashing (P1)](cryptography/encryption_vs_hashing.md)
- [x] [Symmetric Encryption (P1)](cryptography/symmetric_encryption.md)
- [x] [Asymmetric Encryption (P1)](cryptography/asymmetric_encryption.md)
- [x] [Hashing (P1)](cryptography/hashing.md)
- [x] [Encoding vs Encryption vs Hashing (P1)](cryptography/encoding_encryption_hashing.md)
- [ ] Cryptographic Keys (P1)
- [ ] Key Exchange (P1)
- [ ] Digital Signatures (P1)
- [ ] Digital Certificates (P1)
- [ ] Public Key Infrastructure (PKI) (P1)
- [ ] Certificate Authorities (CA) (P1)
- [ ] Certificate Revocation (P2)
- [ ] HMAC (P1)
- [ ] Password Hashing (P1)
- [ ] Salt and Pepper (P1)
- [ ] Key Derivation Functions (P2)
- [ ] AES (P1)
- [ ] RSA (P1)
- [ ] ECC (P2)
- [ ] Diffie-Hellman (P1)
- [ ] Elliptic Curve Diffie-Hellman (ECDH) (P2)
- [ ] TLS Handshake (P1)
- [ ] Cryptographic Attacks (P2)
- [ ] Post-Quantum Cryptography (P3)

---

# 5. Reconnaissance and OSINT

## 5.1 Reconnaissance Fundamentals

- [x] [Introduction to Reconnaissance (P1)](reconnaissance/reconnaissance.md)
- [x] [Passive vs Active Reconnaissance (P1)](reconnaissance/passive_vs_active.md)
- [x] [Information Gathering (P1)](reconnaissance/information_gathering.md)
- [ ] Attack Surface Discovery (P1)
- [ ] Domain Enumeration (P1)
- [ ] IP Enumeration (P1)
- [ ] DNS Enumeration (P1)
- [ ] Subdomain Enumeration (P1)
- [ ] Port Scanning (P1)
- [ ] Service Enumeration (P1)
- [ ] Technology Fingerprinting (P1)

## 5.2 OSINT

- [ ] OSINT Fundamentals (P1)
- [ ] Google Dorking (P1)
- [ ] WHOIS (P1)
- [ ] DNS History (P2)
- [ ] Certificate Transparency (P2)
- [ ] Shodan (P1)
- [ ] Censys (P2)
- [ ] theHarvester (P2)
- [ ] Recon-ng (P2)
- [ ] Maltego (P2)
- [ ] SpiderFoot (P2)
- [ ] GitHub OSINT (P2)
- [ ] Wayback Machine (P2)
- [ ] Social Media OSINT (P3)

---

# 6. Web Application Security

## 6.1 Web Fundamentals

- [ ] How the Web Works (P1)
- [ ] HTTP Request and Response (P1)
- [ ] HTTP Methods (P1)
- [ ] HTTP Headers (P1)
- [ ] Cookies (P1)
- [ ] Sessions (P1)
- [ ] Same-Origin Policy (P1)
- [ ] CORS (P1)
- [ ] Browser Storage (P2)
- [ ] DNS to HTTP Request Flow (P1)
- [ ] TLS in Web Applications (P1)

## 6.2 OWASP Top 10

- [ ] Broken Access Control (P1)
- [ ] Cryptographic Failures (P1)
- [ ] Injection (P1)
- [ ] Insecure Design (P1)
- [ ] Security Misconfiguration (P1)
- [ ] Vulnerable and Outdated Components (P1)
- [ ] Identification and Authentication Failures (P1)
- [ ] Software and Data Integrity Failures (P1)
- [ ] Security Logging and Monitoring Failures (P2)
- [ ] Server-Side Request Forgery (SSRF) (P1)

## 6.3 Web Vulnerabilities

- [ ] SQL Injection (P1)
- [ ] Cross-Site Scripting - XSS (P1)
- [ ] Cross-Site Request Forgery - CSRF (P1)
- [ ] SSRF (P1)
- [ ] Command Injection (P1)
- [ ] Path Traversal (P1)
- [ ] File Inclusion (P2)
- [ ] File Upload Vulnerabilities (P1)
- [ ] Authentication Bypass (P1)
- [ ] Authorization Bypass (P1)
- [ ] IDOR / BOLA (P1)
- [ ] Session Attacks (P1)
- [ ] Open Redirect (P2)
- [ ] Clickjacking (P2)
- [ ] SSTI (P2)
- [ ] XXE (P2)
- [ ] Prototype Pollution (P2)
- [ ] Web Cache Poisoning (P3)
- [ ] Request Smuggling (P3)
- [ ] WebSocket Security (P2)

## 6.4 Web Security Tools

- [ ] Burp Suite (P1)
- [ ] OWASP ZAP (P2)
- [ ] ffuf (P1)
- [ ] Gobuster (P1)
- [ ] Nikto (P2)
- [ ] Nuclei (P2)
- [ ] SQLMap (P2)

---

# 7. API Security

## 7.1 API Fundamentals

- [ ] REST API Security (P1)
- [ ] GraphQL Security (P2)
- [ ] gRPC Security (P3)
- [ ] API Authentication (P1)
- [ ] API Authorization (P1)
- [ ] API Rate Limiting (P1)
- [ ] API Input Validation (P1)
- [ ] API Security Headers (P2)

## 7.2 Authentication and Authorization

- [ ] JWT (P1)
- [ ] JWT Attacks (P1)
- [ ] OAuth 2.0 (P1)
- [ ] OpenID Connect (P2)
- [ ] API Keys (P1)
- [ ] Session Tokens (P1)
- [ ] Broken Object Level Authorization - BOLA (P1)
- [ ] Broken Function Level Authorization - BFLA (P1)
- [ ] Mass Assignment (P2)

---

# 8. Exploitation

## 8.1 Exploitation Fundamentals

- [x] [Introduction to Exploitation (P1)](exploitation/exploitation.md)
- [x] [Vulnerability vs Exploit (P1)](exploitation/vulnerability_vs_exploit.md)
- [x] [Exploit Development Basics (P2)](exploitation/exploit_development.md)
- [ ] Exploitation Methodology (P1)
- [ ] Proof of Concept Development (P1)
- [ ] Exploit Chains (P2)
- [ ] Metasploit Framework (P1)
- [ ] Exploit Databases (P1)
- [ ] CVE and CWE (P1)
- [ ] CVSS (P1)
- [ ] EPSS (P2)

## 8.2 Memory Exploitation

- [ ] Stack and Heap (P1)
- [ ] Buffer Overflow (P1)
- [ ] Stack Overflow (P1)
- [ ] Heap Overflow (P2)
- [ ] Use-After-Free (P2)
- [ ] Format String Vulnerabilities (P2)
- [ ] Shellcode Basics (P2)
- [ ] ASLR (P2)
- [ ] DEP / NX (P2)
- [ ] Stack Canaries (P2)
- [ ] Return-Oriented Programming - ROP (P3)

---

# 9. Privilege Escalation

## 9.1 Linux Privilege Escalation

- [ ] Linux Privilege Escalation Methodology (P1)
- [ ] SUID / SGID (P1)
- [ ] Linux Capabilities (P1)
- [ ] Sudo Misconfiguration (P1)
- [ ] Cron Jobs (P1)
- [ ] PATH Hijacking (P2)
- [ ] Writable Files and Directories (P1)
- [ ] Weak Service Configuration (P2)
- [ ] Kernel Exploitation (P3)
- [ ] Linux Enumeration Tools (P1)
- [ ] LinPEAS (P1)

## 9.2 Windows Privilege Escalation

- [ ] Windows Privilege Escalation Methodology (P1)
- [ ] Windows Services (P1)
- [ ] Unquoted Service Paths (P1)
- [ ] Weak Service Permissions (P1)
- [ ] Registry Exploitation (P2)
- [ ] DLL Hijacking (P2)
- [ ] Token Impersonation (P2)
- [ ] UAC Bypass (P2)
- [ ] Windows Enumeration Tools (P1)
- [ ] WinPEAS (P1)

---

# 10. Active Directory Security

## 10.1 Active Directory Fundamentals

- [ ] Active Directory Architecture (P1)
- [ ] Domains and Forests (P1)
- [ ] Domain Controllers (P1)
- [ ] Users, Groups and Computers (P1)
- [ ] Group Policy (P1)
- [ ] LDAP (P1)
- [ ] Kerberos (P1)
- [ ] NTLM (P1)
- [ ] Service Principal Names - SPNs (P2)

## 10.2 Active Directory Attacks

- [ ] Kerberoasting (P1)
- [ ] AS-REP Roasting (P1)
- [ ] Pass the Hash (P1)
- [ ] Pass the Ticket (P2)
- [ ] NTLM Relay (P1)
- [ ] LLMNR / NBT-NS Poisoning (P1)
- [ ] DCSync (P2)
- [ ] Golden Ticket (P2)
- [ ] Silver Ticket (P2)
- [ ] Credential Dumping (P1)
- [ ] BloodHound (P1)
- [ ] SharpHound (P1)
- [ ] Active Directory Attack Paths (P1)

---

# 11. Post Exploitation

- [ ] Post Exploitation Methodology (P1)
- [ ] Situational Awareness (P1)
- [ ] Credential Harvesting (P1)
- [ ] Password Attacks (P1)
- [ ] Credential Dumping (P1)
- [ ] Persistence (P1)
- [ ] Lateral Movement (P1)
- [ ] Privilege Escalation (P1)
- [ ] Data Discovery (P1)
- [ ] Data Exfiltration Concepts (P2)
- [ ] Command and Control - C2 (P1)
- [ ] Pivoting (P1)
- [ ] Port Forwarding (P1)
- [ ] Tunneling (P2)
- [ ] Cleanup and Evidence Removal (P2)

---

# 12. Red Team and Penetration Testing

## 12.1 Penetration Testing

- [ ] Penetration Testing Fundamentals (P1)
- [ ] Penetration Testing Methodology (P1)
- [ ] Rules of Engagement (P1)
- [ ] Scope Definition (P1)
- [ ] Black Box Testing (P1)
- [ ] Grey Box Testing (P2)
- [ ] White Box Testing (P2)
- [ ] Vulnerability Assessment vs Penetration Testing (P1)
- [ ] Reconnaissance (P1)
- [ ] Enumeration (P1)
- [ ] Exploitation (P1)
- [ ] Post Exploitation (P1)
- [ ] Reporting (P1)

## 12.2 Red Team Concepts

- [ ] Red Team Fundamentals (P1)
- [ ] Adversary Simulation (P2)
- [ ] Initial Access (P1)
- [ ] Execution (P1)
- [ ] Persistence (P1)
- [ ] Privilege Escalation (P1)
- [ ] Defense Evasion (P1)
- [ ] Credential Access (P1)
- [ ] Discovery (P1)
- [ ] Lateral Movement (P1)
- [ ] Command and Control (P1)
- [ ] Exfiltration (P2)
- [ ] Impact (P2)
- [ ] MITRE ATT&CK (P1)

---

# 13. Malware and Reverse Engineering

## 13.1 Malware Fundamentals

- [ ] Malware Fundamentals (P1)
- [ ] Viruses (P1)
- [ ] Worms (P1)
- [ ] Trojans (P1)
- [ ] Ransomware (P1)
- [ ] Spyware (P2)
- [ ] Rootkits (P2)
- [ ] Botnets (P2)
- [ ] Fileless Malware (P2)
- [ ] Droppers and Loaders (P2)

## 13.2 Malware Analysis

- [ ] Static Analysis (P1)
- [ ] Dynamic Analysis (P1)
- [ ] Behavioral Analysis (P1)
- [ ] Indicators of Compromise - IoCs (P1)
- [ ] YARA (P2)
- [ ] Sandbox Analysis (P2)
- [ ] PE File Format (P2)
- [ ] ELF File Format (P2)
- [ ] Strings and Metadata Analysis (P1)

## 13.3 Reverse Engineering

- [ ] Reverse Engineering Fundamentals (P2)
- [ ] Assembly Basics (P2)
- [ ] x86 / x64 Architecture (P2)
- [ ] Debugging (P2)
- [ ] GDB (P2)
- [ ] x64dbg (P2)
- [ ] Ghidra (P1)
- [ ] IDA Free (P2)
- [ ] Radare2 (P3)

---

# 14. Defensive Security

## 14.1 Blue Team Fundamentals

- [ ] Blue Team Fundamentals (P1)
- [ ] Security Monitoring (P1)
- [ ] Log Analysis (P1)
- [ ] Threat Detection (P1)
- [ ] Threat Intelligence (P1)
- [ ] Incident Response (P1)
- [ ] Digital Forensics (P1)
- [ ] Endpoint Security (P1)
- [ ] Network Security Monitoring (P1)

## 14.2 SOC

- [ ] Security Operations Center - SOC (P1)
- [ ] SOC Roles and Responsibilities (P2)
- [ ] Alert Triage (P1)
- [ ] Incident Triage (P1)
- [ ] Incident Investigation (P1)
- [ ] SIEM (P1)
- [ ] EDR (P1)
- [ ] XDR (P2)
- [ ] SOAR (P2)
- [ ] Detection Engineering (P1)
- [ ] Threat Hunting (P1)

## 14.3 SIEM

- [ ] SIEM Fundamentals (P1)
- [ ] Log Collection (P1)
- [ ] Log Normalization (P2)
- [ ] Correlation Rules (P1)
- [ ] Detection Rules (P1)
- [ ] Alerting (P1)
- [ ] Dashboards and Reporting (P2)
- [ ] Splunk (P2)
- [ ] Elastic Security (P2)
- [ ] Microsoft Sentinel (P2)

---

# 15. Incident Response and Digital Forensics

## 15.1 Incident Response

- [ ] Incident Response Fundamentals (P1)
- [ ] Preparation (P1)
- [ ] Identification (P1)
- [ ] Containment (P1)
- [ ] Eradication (P1)
- [ ] Recovery (P1)
- [ ] Lessons Learned (P1)
- [ ] Incident Response Playbooks (P1)
- [ ] Evidence Preservation (P1)
- [ ] Chain of Custody (P1)

## 15.2 Digital Forensics

- [ ] Digital Forensics Fundamentals (P1)
- [ ] Disk Forensics (P1)
- [ ] Memory Forensics (P1)
- [ ] Network Forensics (P2)
- [ ] Browser Forensics (P2)
- [ ] Windows Forensics (P1)
- [ ] Linux Forensics (P2)
- [ ] Timeline Analysis (P2)
- [ ] Volatility (P1)
- [ ] Autopsy (P2)

---

# 16. Cloud Security

## 16.1 Cloud Fundamentals

- [ ] Cloud Computing Fundamentals (P1)
- [ ] Shared Responsibility Model (P1)
- [ ] IaaS, PaaS and SaaS (P1)
- [ ] Cloud Identity and Access Management (P1)
- [ ] Cloud Networking (P1)
- [ ] Cloud Logging and Monitoring (P1)
- [ ] Cloud Storage Security (P1)
- [ ] Cloud Secrets Management (P1)

## 16.2 AWS Security

- [ ] AWS Security Fundamentals (P1)
- [ ] IAM (P1)
- [ ] S3 Security (P1)
- [ ] VPC Security (P1)
- [ ] Security Groups and NACLs (P1)
- [ ] CloudTrail (P1)
- [ ] GuardDuty (P2)
- [ ] KMS (P1)
- [ ] Secrets Manager (P1)

## 16.3 Azure and GCP Security

- [ ] Azure Security Fundamentals (P2)
- [ ] Microsoft Entra ID (P1)
- [ ] Azure RBAC (P1)
- [ ] Azure Key Vault (P2)
- [ ] GCP Security Fundamentals (P2)
- [ ] Google Cloud IAM (P2)
- [ ] Google Cloud KMS (P2)

---

# 17. Container and Kubernetes Security

## 17.1 Containers

- [ ] Container Security Fundamentals (P1)
- [ ] Docker Security (P1)
- [ ] Container Images (P1)
- [ ] Image Vulnerability Scanning (P1)
- [ ] Container Secrets (P1)
- [ ] Container Isolation (P1)
- [ ] Container Runtime Security (P2)

## 17.2 Kubernetes

- [ ] Kubernetes Security Fundamentals (P1)
- [ ] Kubernetes RBAC (P1)
- [ ] Kubernetes Network Policies (P1)
- [ ] Kubernetes Secrets (P1)
- [ ] Pod Security (P1)
- [ ] Admission Controllers (P2)
- [ ] Kubernetes API Security (P1)
- [ ] Kubernetes Audit Logs (P2)

---

# 18. DevSecOps

- [ ] DevSecOps Fundamentals (P1)
- [ ] Secure SDLC (P1)
- [ ] Shift Left Security (P1)
- [ ] Security in CI/CD (P1)
- [ ] SAST (P1)
- [ ] DAST (P1)
- [ ] SCA (P1)
- [ ] Secret Scanning (P1)
- [ ] Container Scanning (P1)
- [ ] IaC Security (P1)
- [ ] Dependency Security (P1)
- [ ] Software Supply Chain Security (P1)
- [ ] SBOM (P2)
- [ ] Software Signing (P2)
- [ ] GitHub Security (P2)

---

# 19. Mobile Security

- [ ] Mobile Security Fundamentals (P2)
- [ ] Android Security (P1)
- [ ] iOS Security (P2)
- [ ] Android Application Architecture (P2)
- [ ] APK Analysis (P2)
- [ ] Mobile Authentication (P1)
- [ ] Mobile Authorization (P1)
- [ ] Mobile Data Storage Security (P1)
- [ ] Mobile Network Security (P1)
- [ ] Certificate Pinning (P2)
- [ ] Mobile Reverse Engineering (P3)
- [ ] Frida (P2)
- [ ] MobSF (P2)

---

# 20. IoT and Hardware Security

- [ ] IoT Security Fundamentals (P2)
- [ ] IoT Architecture (P2)
- [ ] Device Authentication (P2)
- [ ] Firmware Security (P2)
- [ ] Firmware Analysis (P3)
- [ ] Embedded Systems Security (P3)
- [ ] Hardware Security Fundamentals (P3)
- [ ] UART / JTAG (P3)
- [ ] Hardware Debug Interfaces (P3)

---

# 21. Identity and Access Management

- [ ] IAM Fundamentals (P1)
- [ ] Authentication (P1)
- [ ] Authorization (P1)
- [ ] RBAC (P1)
- [ ] ABAC (P2)
- [ ] MFA (P1)
- [ ] Passwordless Authentication (P2)
- [ ] Passkeys / WebAuthn (P2)
- [ ] SSO (P1)
- [ ] SAML (P2)
- [ ] OAuth 2.0 (P1)
- [ ] OpenID Connect (P1)
- [ ] LDAP (P2)
- [ ] Kerberos (P1)
- [ ] Privileged Access Management - PAM (P2)

---

# 22. Security Architecture

- [ ] Security Architecture Fundamentals (P1)
- [ ] Zero Trust Architecture (P1)
- [ ] Network Segmentation (P1)
- [ ] Defense in Depth (P1)
- [ ] Identity-Centric Security (P1)
- [ ] Secure Network Architecture (P1)
- [ ] Secure Application Architecture (P1)
- [ ] Secure Cloud Architecture (P1)
- [ ] Security Reference Architectures (P2)
- [ ] Threat Modeling (P1)

---

# 23. Vulnerability Management

- [ ] Vulnerability Management Fundamentals (P1)
- [ ] Asset Discovery (P1)
- [ ] Vulnerability Scanning (P1)
- [ ] Vulnerability Validation (P1)
- [ ] CVE (P1)
- [ ] CWE (P1)
- [ ] CVSS (P1)
- [ ] EPSS (P2)
- [ ] Vulnerability Prioritization (P1)
- [ ] Patch Management (P1)
- [ ] Risk-Based Vulnerability Management (P2)
- [ ] Remediation Tracking (P1)

---

# 24. Security Governance, Risk and Compliance

## 24.1 Governance

- [ ] Information Security Governance (P1)
- [ ] Security Policies (P1)
- [ ] Security Standards (P1)
- [ ] Security Procedures (P1)
- [ ] Security Awareness (P1)
- [ ] Security Metrics (P2)

## 24.2 Risk Management

- [ ] Risk Fundamentals (P1)
- [ ] Risk Identification (P1)
- [ ] Risk Assessment (P1)
- [ ] Risk Treatment (P1)
- [ ] Risk Register (P1)
- [ ] Business Impact Analysis (P2)
- [ ] Third-Party Risk Management (P2)
- [ ] Supply Chain Risk (P2)

## 24.3 Security Frameworks

- [ ] NIST Cybersecurity Framework - CSF (P1)
- [ ] NIST Risk Management Framework - RMF (P2)
- [ ] CIS Controls (P1)
- [ ] ISO/IEC 27001 (P1)
- [ ] SOC 2 (P2)
- [ ] PCI DSS (P2)
- [ ] GDPR (P2)
- [ ] HIPAA (P3)
- [ ] COBIT (P3)

---

# 25. Security Testing

- [ ] Security Testing Fundamentals (P1)
- [ ] SAST (P1)
- [ ] DAST (P1)
- [ ] IAST (P2)
- [ ] SCA (P1)
- [ ] API Security Testing (P1)
- [ ] Web Security Testing (P1)
- [ ] Mobile Security Testing (P2)
- [ ] Infrastructure Security Testing (P1)
- [ ] Cloud Security Testing (P1)
- [ ] Fuzz Testing (P2)
- [ ] Penetration Testing (P1)
- [ ] Vulnerability Assessment (P1)
- [ ] Security Regression Testing (P2)

---

# 26. Social Engineering

- [ ] Social Engineering Fundamentals (P1)
- [ ] Phishing (P1)
- [ ] Spear Phishing (P1)
- [ ] Whaling (P2)
- [ ] Vishing (P2)
- [ ] Smishing (P2)
- [ ] Pretexting (P2)
- [ ] Baiting (P2)
- [ ] Tailgating (P2)
- [ ] Shoulder Surfing (P3)
- [ ] Security Awareness Training (P1)

---

# 27. Physical Security

- [ ] Physical Security Fundamentals (P2)
- [ ] Physical Access Controls (P2)
- [ ] Badges and Biometrics (P3)
- [ ] CCTV Security (P3)
- [ ] Server Room Security (P2)
- [ ] Device Theft Protection (P2)
- [ ] Clean Desk Policy (P3)
- [ ] Physical Social Engineering (P2)

---

# 28. Security Tools

## 28.1 Reconnaissance

- [ ] Nmap (P1)
- [ ] Amass (P2)
- [ ] Subfinder (P2)
- [ ] httpx (P2)
- [ ] theHarvester (P2)
- [ ] Shodan (P1)

## 28.2 Web Security

- [ ] Burp Suite (P1)
- [ ] OWASP ZAP (P2)
- [ ] ffuf (P1)
- [ ] Gobuster (P1)
- [ ] Nikto (P2)
- [ ] Nuclei (P2)
- [ ] SQLMap (P2)

## 28.3 Exploitation

- [ ] Metasploit (P1)
- [ ] SearchSploit (P2)
- [ ] Netcat (P1)
- [ ] Socat (P3)

## 28.4 Password and Credential Security

- [ ] Hashcat (P1)
- [ ] John the Ripper (P1)
- [ ] Hydra (P1)
- [ ] CrackMapExec / NetExec (P2)

## 28.5 Network Analysis

- [ ] Wireshark (P1)
- [ ] tcpdump (P1)
- [ ] Zeek (P2)
- [ ] Suricata (P2)

## 28.6 Windows and Active Directory

- [ ] BloodHound (P1)
- [ ] Mimikatz (P2)
- [ ] Impacket (P1)
- [ ] Responder (P1)
- [ ] Rubeus (P2)

---

# 29. Capture The Flag

- [ ] CTF Fundamentals (P1)
- [ ] Linux CTFs (P1)
- [ ] Web CTFs (P1)
- [ ] Cryptography CTFs (P2)
- [ ] Reverse Engineering CTFs (P2)
- [ ] Binary Exploitation CTFs (P2)
- [ ] Forensics CTFs (P2)
- [ ] OSINT CTFs (P2)
- [ ] Privilege Escalation CTFs (P1)
- [ ] Active Directory CTFs (P2)

---

# 30. Bug Bounty

- [ ] Bug Bounty Fundamentals (P1)
- [ ] Program Scope and Rules (P1)
- [ ] Reconnaissance (P1)
- [ ] Asset Discovery (P1)
- [ ] Subdomain Enumeration (P1)
- [ ] Web Application Testing (P1)
- [ ] API Testing (P1)
- [ ] Vulnerability Validation (P1)
- [ ] Impact Assessment (P1)
- [ ] Report Writing (P1)
- [ ] Responsible Disclosure (P1)
- [ ] Common Bug Bounty Vulnerabilities (P1)

---

# 31. Emerging Security

## 31.1 AI Security

- [ ] AI Security Fundamentals (P1)
- [ ] LLM Security (P1)
- [ ] Prompt Injection (P1)
- [ ] Jailbreaking (P2)
- [ ] Sensitive Information Disclosure (P1)
- [ ] Insecure Tool Use (P1)
- [ ] Excessive Agency (P1)
- [ ] RAG Security (P2)
- [ ] AI Supply Chain Security (P2)
- [ ] Model Poisoning (P2)
- [ ] Adversarial Machine Learning (P2)
- [ ] AI Red Teaming (P1)
- [ ] AI Threat Modeling (P1)
- [ ] AI Agent Security (P1)

## 31.2 Emerging Technologies

- [ ] Post-Quantum Cryptography (P3)
- [ ] Blockchain Security (P3)
- [ ] Smart Contract Security (P3)
- [ ] Autonomous Systems Security (P3)
- [ ] Cloud-Native Security (P2)
- [ ] Software Supply Chain Security (P1)

---

# 32. Security Labs and Practice

- [ ] Linux Security Labs (P1)
- [ ] Networking Labs (P1)
- [ ] Web Security Labs (P1)
- [ ] API Security Labs (P1)
- [ ] Privilege Escalation Labs (P1)
- [ ] Active Directory Labs (P1)
- [ ] Cryptography Challenges (P2)
- [ ] Reverse Engineering Labs (P2)
- [ ] Malware Analysis Labs (P2)
- [ ] CTF Practice (P1)
- [ ] Bug Bounty Practice (P1)
- [ ] Detection Engineering Labs (P2)

---

# 33. References and Methodologies

- [ ] MITRE ATT&CK (P1)
- [ ] OWASP Top 10 (P1)
- [ ] OWASP API Security Top 10 (P1)
- [ ] OWASP Testing Guide (P1)
- [ ] NIST Cybersecurity Framework (P1)
- [ ] CIS Controls (P1)
- [ ] Cyber Kill Chain (P2)
- [ ] Diamond Model (P2)
- [ ] STRIDE (P1)
- [ ] DREAD (P3)
- [ ] CVSS (P1)
- [ ] CVE / CWE (P1)
