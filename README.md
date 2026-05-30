# 🛡️ Cybersecurity Handbook

<div align="center">
  <img src=".assets/logo.png" alt="Logo" width=200 height=200/>
</div>

> [!NOTE]
> A comprehensive, open-source cybersecurity reference covering every layer of the field – from core fundamentals and hands-on offensive/defensive skills to enterprise governance and emerging AI threats. Includes a structured roadmap, term glossary, and career path. Built for students, practitioners, and security leaders alike. Items marked with `[CISO]` indicate enterprise/management-level responsibilities relevant for senior security roles.

---

## Overview

<div align="center">

| 🗺️ Roadmap | 📖 Glossary | 🤝 Contributing |
|:-----------:|:-----------:|:---------------:|
| [View Roadmap](#cybersecurity-roadmap) | [View Glossary](#glossary) | [Contribute](#contributing) |

</div>

---

## Cybersecurity Roadmap

**[`^        back to top        ^`](#overview)**

```
| Cybersecurity Roadmap
|
|-- Fundamentals
|   |-- Introduction to Cybersecurity
|   |   |-- CIA Triad (Confidentiality, Integrity, Availability)
|   |   |-- Importance and Principles of Cybersecurity
|   |   |-- Types of Cybersecurity (Network, Information, Application, Cloud, OT, etc.)
|   |   |-- Cybersecurity Threat Landscape (Malware, Phishing, Ransomware, etc.)
|   |   |-- Authentication vs Authorization vs Accounting (AAA)
|   |   |-- Principle of Least Privilege
|   |   |-- Defense in Depth
|   |   |-- Security by Design
|   |   |-- Understand Concept of Isolation
|   |   |-- Understand Handshakes (TCP, TLS, etc.)
|   |   |-- Understand Concept of Runbooks
|   |   |-- Basics of Computer Networking (overview)
|   |   |-- Understand Common Hacking Tools
|   |   |-- Understand Common Exploit Frameworks
|   |   |-- Basics of Forensics
|   |
|   |-- Operating Systems Security
|   |   |-- Windows
|   |   |   |-- Active Directory Basics and Security
|   |   |   |-- Group Policy (GPO)
|   |   |   |-- Windows Defender and Built-in Security Tools
|   |   |   |-- Event Log Analysis
|   |   |   |-- Hardening (CIS Benchmarks)
|   |   |-- Linux
|   |   |   |-- File Permissions and Ownership (chmod, chown, ACLs)
|   |   |   |-- User and Group Management
|   |   |   |-- Logging and Auditing (auditd, syslog)
|   |   |   |-- SELinux / AppArmor
|   |   |   |-- Hardening (CIS Benchmarks, lynis)
|   |   |-- macOS
|   |   |   |-- Built-in Security Features (Gatekeeper, SIP, FileVault)
|   |   |   |-- Security Configurations and Hardening
|   |   |-- General OS Skills
|   |   |   |-- Installation and Configuration
|   |   |   |-- Different Versions and Differences
|   |   |   |-- Navigating via GUI and CLI
|   |   |   |-- Understand Permissions
|   |   |   |-- Installing Software and Applications
|   |   |   |-- Performing CRUD on Files
|   |   |   |-- Troubleshooting and Common Commands
|   |   |   |-- OS-Independent Troubleshooting
|   |   |   |-- OS Hardening Concepts
|   |   |   |-- Computer Hardware Components
|
|-- Networking Knowledge
|   |-- OSI Model and TCP/IP Stack (security at each layer)
|   |-- Common Protocols and their Uses
|   |-- Common Ports and their Uses
|   |-- IP Terminology
|   |   |-- localhost, loopback, CIDR, Subnet Mask, Default Gateway
|   |   |-- Public vs Private IP Addresses
|   |   |-- Subnetting Basics
|   |-- Network Terminology
|   |   |-- VLAN, DMZ, ARP, VM, DHCP, DNS, NAT
|   |   |-- Router, Switch, VPN, Proxy
|   |   |-- MAN, LAN, WAN, WLAN
|   |   |-- NAS and SAN Basics
|   |   |-- SSL and TLS Basics (overview)
|   |   |-- IPv6 Security Considerations
|   |   |-- 802.1X Port-Based Authentication
|   |   |-- BGP Security (hijacking, RPKI, ROA)
|   |   |-- QUIC Protocol Security
|   |   |-- ARP Spoofing and Poisoning
|   |   |-- NTP Amplification Attacks
|   |   |-- Rogue DHCP Attacks
|   |   |-- ICMP-Based Attacks (Ping of Death, Smurf)
|   |   |-- Packet Fragmentation Attacks
|   |   |-- SD-WAN Security
|   |   |-- MPLS Security Considerations
|   |   |-- Network TAP and SPAN Ports
|   |   |-- Out-of-Band (OOB) Management
|   |-- Network Topologies (Star, Ring, Mesh, Bus)
|   |-- Network Protocols
|   |   |-- SSH, RDP, FTP, SFTP
|   |   |-- HTTP / HTTPS, SSL / TLS
|   |   |-- DNS, DHCP, NTP, IPAM
|   |   |-- DNS over HTTPS (DoH) and DNS over TLS (DoT)
|   |   |-- SPF, DKIM, DMARC (email authentication)
|   |-- Connection Types
|   |   |-- WiFi, Bluetooth, NFC, Infrared, iCloud sync
|   |-- Virtualization Basics
|   |   |-- Hypervisor, VM, GuestOS, HostOS
|   |   |-- VMware, VirtualBox, ESXi, Proxmox
|   |-- Troubleshooting Tools
|   |   |-- Port Scanners: nmap, masscan
|   |   |-- Packet Sniffers / Protocol Analyzers: Wireshark, tcpdump
|   |   |-- nslookup, dig, ping, tracert, hping, curl
|   |   |-- ipconfig, netstat, arp, route, iptables
|
|-- Threats and Vulnerabilities
|   |-- Types of Cyber Threats
|   |   |-- Malware (Viruses, Worms, Trojans, Rootkits, Spyware, Adware)
|   |   |-- Ransomware
|   |   |-- Phishing, Spear Phishing, Whaling, Vishing, Smishing
|   |   |-- Spam vs Spim
|   |   |-- Social Engineering (Pretexting, Baiting, Impersonation, Reconnaissance)
|   |   |-- Denial of Service (DoS) and Distributed DoS (DDoS)
|   |   |-- Man-in-the-Middle (MitM) Attacks
|   |   |-- Insider Threats
|   |   |-- Supply Chain Attacks (e.g., SolarWinds, XZ Utils)
|   |   |-- Zero-Day Exploits
|   |-- Common Attack Techniques
|   |   |-- SQL Injection, XSS, CSRF, SSRF
|   |   |-- Buffer Overflow, Memory Leak
|   |   |-- Pass the Hash, Replay Attack
|   |   |-- DNS Poisoning, VLAN Hopping
|   |   |-- Brute Force vs Password Spray
|   |   |-- Directory Traversal
|   |   |-- Drive-by Attack, Watering Hole Attack
|   |   |-- Typosquatting
|   |   |-- Shoulder Surfing, Dumpster Diving, Tailgating
|   |   |-- Evil Twin, Rogue Access Point, Deauth Attack
|   |   |-- Spoofing, MITM
|   |-- Vulnerability Assessment
|   |   |-- Asset Management and Inventory
|   |   |-- Vulnerability Scanning (Nessus, OpenVAS)
|   |   |   |-- Scope: OS, Network Devices, Apps, Databases, Code,
|   |   |   |          Physical, Cloud, Mobile, Containers, IoT, OT/SCADA
|   |   |   |-- Attack Surface Management
|   |   |-- Identify Vulnerabilities (periodic or continuous)
|   |   |-- Classify and Prioritize Vulnerabilities
|   |   |-- Risk-Based Approach to Prioritization (e.g., EPSS)
|   |   |-- Mitigation: Fix, Verify, False Positive Handling
|   |   |-- Baseline and Metrics (measure vuln mgmt effectiveness)
|   |   |-- Penetration Testing (Ethical Hacking)
|   |   |-- Security Audits and Assessments
|   |   |-- CVSS Scoring and EPSS (Exploit Prediction Scoring System)
|   |   |-- CVE / NVD Databases
|   |   |-- Cyber Kill Chain
|   |   |-- MITRE ATT&CK Framework
|   |   |-- Diamond Model
|
|-- Encryption and Cryptography
|   |-- Introduction to Cryptography
|   |   |-- Symmetric Encryption (AES, DES, 3DES)
|   |   |-- Asymmetric Encryption (RSA, ECC)
|   |   |-- Hashing Algorithms (SHA-256, SHA-3, MD5)
|   |   |-- Salting and Key Exchange
|   |   |-- Public Key Infrastructure (PKI)
|   |   |-- Private vs Public Keys
|   |   |-- Digital Signatures and Certificates
|   |   |-- Certificate Transparency (CT) Logs
|   |   |-- OCSP and Certificate Revocation
|   |   |-- TLS Certificate Pinning
|   |   |-- HSM (Hardware Security Module)
|   |   |-- Zero-Knowledge Proofs (ZKP)
|   |   |-- Key Derivation Functions (PBKDF2, bcrypt, Argon2)
|   |   |-- Elliptic Curve Diffie-Hellman (ECDH)
|   |   |-- Diffie-Hellman Key Exchange and Weaknesses
|   |   |-- Forward Secrecy (PFS -- Perfect Forward Secrecy)
|   |   |-- Padding Oracle Attacks
|   |   |-- Downgrade Attacks (POODLE, BEAST, CRIME)
|   |   |-- Steganography
|   |   |-- Key Escrow
|   |   |-- Obfuscation
|   |-- Encryption Protocols
|   |   |-- SSL / TLS (versions, handshake, misconfigurations)
|   |   |-- IPsec
|   |   |-- SSH
|   |   |-- PGP / GPG
|   |   |-- DNSSEC, LDAPS, SRTP, S/MIME
|   |-- Quantum-Safe Encryption
|   |   |-- Threat of Quantum Computers (Shor's Algorithm)
|   |   |-- NIST Post-Quantum Cryptography Standards (CRYSTALS-Kyber, CRYSTALS-Dilithium)
|   |   |-- Quantum Key Distribution (QKD)
|   |   |-- Confidential Computing (Intel TDX, AMD SEV, ARM CCA)
|   |   |-- [CISO] Quantum Strategy and Planning
|
|-- Identity and Access Management (IAM)
|   |-- Identity Credentialing
|   |   |-- User Provisioning and Identity Lifecycle Management
|   |   |-- HR Process Integration
|   |   |-- Unified Identity Profiles
|   |   |-- IoT Device Identities
|   |   |-- AI Agent Identity
|   |-- Authentication Mechanisms
|   |   |-- Password Policies and Best Practices
|   |   |-- Multi-Factor Authentication (MFA) and 2FA
|   |   |   |-- Authenticator Apps
|   |   |   |-- Hardware Tokens and Cards
|   |   |   |-- One-Time Passcodes (OTP)
|   |   |-- Biometric Authentication (Face Recognition, Voice Signatures)
|   |   |-- Passkey (FIDO2 / WebAuthn)
|   |   |-- Single Sign-On (SSO), SAML, Shibboleth
|   |   |-- Federation and OAuth 2.0 / OpenID Connect
|   |   |-- Passwordless Authentication
|   |   |-- Kerberos, RADIUS, LDAP / Active Directory
|   |   |   |-- Kerberoasting, AS-REP Roasting
|   |   |   |-- Golden Ticket / Silver Ticket attacks
|   |   |   |-- Pass the Ticket
|   |   |   |-- DCSync Attack
|   |   |   |-- Overpass the Hash
|   |   |   |-- LSASS Memory Dumping
|   |   |   |-- Cloud Identity Stores
|   |   |   |-- Local ID Stores
|   |   |-- Local Auth (Certificates, Local Authentication)
|   |   |-- Use of Public Identity (Google, Facebook) via OAuth / OpenID
|   |   |-- Digital Certificates
|   |   |-- EAP vs PEAP
|   |   |-- SCIM (System for Cross-domain Identity Management)
|   |   |-- Directory Services (Azure AD / Microsoft Entra ID)
|   |   |-- Certificate-Based Authentication (CBA)
|   |   |-- Hardware-Bound Credentials (TPM-backed)
|   |   |-- Conditional Access Policies
|   |   |-- MFA Fatigue / Push Bombing Attacks
|   |   |-- Session Hijacking
|   |   |-- Cookie Theft and Session Fixation
|   |   |-- Credential Stuffing
|   |   |-- SIM Swapping
|   |   |-- Account Takeover (ATO)
|   |   |-- Token Theft (Bearer Token, Refresh Token abuse)
|   |   |-- OAuth 2.0 Misconfigurations and Token Hijacking
|   |-- Access Control Models
|   |   |-- Role-Based Access Control (RBAC)
|   |   |-- Attribute-Based Access Control (ABAC)
|   |   |-- Mandatory Access Control (MAC)
|   |   |-- Discretionary Access Control (DAC)
|   |-- Privilege Management
|   |   |-- Privileged Access Management (PAM)
|   |   |-- Privilege Escalation (techniques and prevention)
|   |   |-- Just-in-Time (JIT) Access
|   |   |-- Privileged Access Workstations (PAW)
|   |   |-- Just Enough Administration (JEA)
|   |   |-- Privileged Identity Management (PIM)
|   |   |-- LAPS (Local Administrator Password Solution)
|   |   |-- Non-Human Identity (NHI) -- service accounts, API keys, secrets
|   |   |-- Identity Threat Detection and Response (ITDR)
|   |-- Customer and External Identity
|   |   |-- Customer Identity for Ecommerce and Mobile Apps
|   |   |-- Password Resets and Self-Service
|   |   |-- Integrating Cloud-Based Identities
|   |   |-- IAM SaaS Solutions
|   |-- IAM with Zero Trust Technologies
|
|-- Network Security
|   |-- Security Controls
|   |   |-- Network/Application Firewalls
|   |   |   |-- Next-Generation Firewall (NGFW)
|   |   |   |-- Host-Based Firewall
|   |   |-- Network IPS and IDS
|   |   |-- VPNs (IPsec, OpenVPN, WireGuard)
|   |   |-- Network Access Control (NAC)
|   |   |-- Network Segmentation and DMZ
|   |   |-- Proxy / Content Filtering
|   |   |-- DNS Security / Filtering
|   |   |   |-- DNSSEC Deployment and Validation
|   |   |-- DDoS Protection
|   |   |-- Honeypots and Honeynets
|   |   |-- Canary Tokens and Honeytokens
|   |   |-- Sinkholes
|   |-- Secure vs Unsecure Protocols
|   |   |-- FTP vs SFTP
|   |   |-- HTTP vs HTTPS
|   |   |-- SSL vs TLS
|   |   |-- LDAP vs LDAPS
|   |   |-- IPSEC, DNSSEC, SRTP, S/MIME
|   |-- Wireless Security
|   |   |-- Wi-Fi Standards: WEP, WPA, WPA2, WPA3
|   |   |-- Bluetooth and BLE Security
|   |   |-- NFC and Infrared Security
|   |   |-- Evil Twin / Rogue Access Points
|   |   |-- Deauthentication Attacks
|   |   |-- Wi-Fi Sniffing and MitM
|   |   |-- EAP vs PEAP, WPS Vulnerabilities
|   |   |-- 802.11 Frame Analysis (management, control, data frames)
|   |-- Hardening Concepts
|   |   |-- MAC-based and NAC-based Hardening
|   |   |-- Port Blocking, Group Policy
|   |   |-- ACLs, Patching
|   |   |-- Jump Server / Bastion Host
|   |   |-- Endpoint Security
|   |   |-- Desktop and Mobile Security
|   |   |-- Anti-Malware, Anti-Spam
|   |   |-- Hardening Guidelines (CIS Benchmarks)
|   |   |-- Security Health Checks
|   |-- Network Monitoring and Analysis
|   |   |-- Network Baseline and Traffic Profiling
|   |   |-- Log Analysis and Correlation
|   |   |-- Packet Capture Analysis (Wireshark, tcpdump)
|
|-- Application Security
|   |-- Secure Software Development
|   |   |-- Application Development Standards
|   |   |-- Secure Coding Practices
|   |   |-- Software Development Life Cycle (SDLC) with Security Gates
|   |   |-- Integration of Security into SDLC and Project Delivery
|   |   |-- Threat Modeling (STRIDE, PASTA)
|   |   |-- Secure Code Reviews
|   |   |-- Application Vulnerability Testing
|   |   |-- Static Application Security Testing (SAST)
|   |   |   |-- Tools: Semgrep, SonarQube, Checkmarx
|   |   |-- Dynamic Application Security Testing (DAST)
|   |   |-- Software Composition Analysis (SCA)
|   |   |   |-- Dependency Scanning: Dependabot, Snyk, OWASP Dependency-Check
|   |   |-- Inventory of Open Source Components
|   |   |-- Source Code Supply Chain Security
|   |   |-- Change Control
|   |   |-- File Integrity Monitoring (FIM)
|   |-- Web Application Security
|   |   |-- OWASP Top 10 (current edition)
|   |   |-- SQL Injection
|   |   |-- Cross-Site Scripting (XSS) -- stored, reflected, DOM-based
|   |   |-- Cross-Site Request Forgery (CSRF)
|   |   |-- Server-Side Request Forgery (SSRF)
|   |   |-- Insecure Deserialization
|   |   |-- XXE (XML External Entity) Injection
|   |   |-- IDOR (Insecure Direct Object Reference)
|   |   |-- Business Logic Vulnerabilities
|   |   |-- Race Conditions in Web Apps
|   |   |-- HTTP Request Smuggling
|   |   |-- HTTP Desync Attacks (HTTP/1 vs HTTP/2)
|   |   |-- Prototype Pollution
|   |   |-- Clickjacking
|   |   |-- Subdomain Takeover
|   |   |-- CORS Misconfigurations
|   |   |-- Server-Side Template Injection (SSTI)
|   |   |-- Path Traversal
|   |   |-- Open Redirect
|   |   |-- WebSockets Security
|   |   |-- Web Cache Poisoning
|   |   |-- DNS Rebinding Attacks
|   |   |-- Insecure File Upload
|   |   |-- Security Headers (CSP, HSTS, X-Frame-Options, etc.)
|   |   |-- Web Application Firewall (WAF)
|   |   |-- API Security (REST, GraphQL)
|   |   |   |-- OWASP API Security Top 10
|   |   |   |-- Broken Object Level Authorization (BOLA)
|   |   |   |-- Broken Function Level Authorization (BFLA)
|   |   |   |-- Mass Assignment Vulnerability
|   |   |   |-- Shadow API and Zombie API Discovery
|   |   |   |-- API Rate Limiting and Throttling
|   |   |   |-- GraphQL Introspection and Batching Attacks
|   |   |   |-- GraphQL Depth Limiting and Query Complexity
|   |   |   |-- gRPC and Protobuf Security
|   |   |-- API Authentication and Secrets Management
|   |   |   |-- JWT Attacks (algorithm confusion, none algorithm)
|   |   |   |-- OAuth 2.0 Attack Patterns (token hijacking, open redirect)
|   |-- DevSecOps
|   |   |-- Secure DevOps and DevSecOps Practices
|   |   |-- Embedding Security Tools in CI/CD Pipelines
|   |   |-- Integrate Cloud-Based Security Tools
|   |   |-- Secure Infrastructure as Code
|   |   |   |-- IaC Scanning: tfsec, Checkov, KICS
|   |   |-- Secret Scanning (GitLeaks, TruffleHog, GitHub Secret Scanning)
|   |   |-- GitOps Security
|   |   |-- Workload Identity Federation
|   |   |-- Automate API Inventory
|   |   |-- Container Security in Pipelines
|   |   |   |-- Container Image Scanning: Trivy, Grype, Clair
|   |   |-- Runtime Application Self-Protection (RASP)
|   |-- Tools
|   |   |-- Burp Suite
|   |   |-- OWASP ZAP
|
|-- Cloud Security
|   |-- Cloud Security Principles
|   |   |-- Understand the Concept of Security in the Cloud
|   |   |-- Understand the Basics and General Flow of Deploying in the Cloud
|   |   |-- Shared Responsibility Model (AWS, Azure, GCP)
|   |   |-- Cloud vs On-Premises Security Differences
|   |   |-- Data Protection in Cloud Environments
|   |   |-- Data Ownership and Compliance
|   |   |-- Identity and Access in Cloud (IAM roles, policies)
|   |   |-- Secrets Management (HashiCorp Vault, AWS Secrets Manager)
|   |   |-- Cloud Log Integration / APIs
|   |   |-- Cloud Audit Logging (CloudTrail, Azure Monitor, GCP Audit Logs)
|   |-- Cloud Service and Deployment Models
|   |   |-- SaaS, PaaS, IaaS
|   |   |-- Private, Public, Hybrid, Multi-Cloud
|   |   |-- [CISO] SaaS Strategy, Policy and Guidelines
|   |   |-- [CISO] Vendor Financial Strength and SLAs
|   |   |-- [CISO] Infrastructure Audit
|   |   |-- [CISO] Proof of Application Security (vendor eval)
|   |   |-- [CISO] Ownership / Liability / Incidents
|   |   |-- [CISO] Integration of Identity Management / Federation / SSO
|   |-- Cloud Security Tools and Controls
|   |   |-- Cloud Access Security Brokers (CASB)
|   |   |-- Cloud Security Posture Management (CSPM)
|   |   |-- Cloud Misconfiguration Testing
|   |   |-- Infrastructure as Code (IaC) Security (Terraform, CloudFormation)
|   |   |-- Container Security (Docker, Kubernetes)
|   |   |   |-- Kubernetes RBAC Hardening
|   |   |   |-- Kubernetes Network Policies
|   |   |   |-- OPA (Open Policy Agent)
|   |   |   |-- Service Account Security (Kubernetes)
|   |   |   |-- Immutable Infrastructure
|   |   |   |-- Cloud Security Benchmarks (CIS AWS, CIS Azure, CIS GCP)
|   |   |-- Container-to-Container Communication Security
|   |   |-- Service Mesh and Microservices Security
|   |   |-- Serverless Computing Security
|   |   |-- Cloud-Native Application Security
|   |   |-- VPC Security (Security Groups, NACLs)
|   |   |-- Egress Filtering and Traffic Control
|   |   |-- Cloud Entitlement Management
|   |   |-- Virtualized Security Appliances
|   |   |-- SASE / SSE Strategy and Vendors
|   |   |-- eBPF Security (Falco, Cilium, Tetragon)
|   |   |-- Runtime Security Monitoring (Falco, Sysdig)
|   |   |-- CNAPP (Cloud-Native Application Protection Platform)
|   |   |-- DSPM (Data Security Posture Management)
|   |   |-- CIEM (Cloud Infrastructure Entitlement Management)
|   |-- Cloud Platforms
|   |   |-- AWS Security Services
|   |   |-- Microsoft Azure Security
|   |   |-- Google Cloud Platform (GCP) Security
|   |   |-- Common Cloud Storage (S3, Dropbox, Box, OneDrive, Google Drive, iCloud)
|   |-- Cloud Architecture and Resilience
|   |   |-- Multi-Cloud Architecture and Strategy
|   |   |-- Software Defined Networking (SDN)
|   |   |-- Network Function Virtualization (NFV)
|   |   |-- Cloud / Hybrid / Multiple Cloud Vendors
|   |   |-- Backup / Replication / Multiple Sites
|   |   |-- [CISO] Disaster Recovery Posture Assessment
|
|-- Security Operations
|   |-- Security Monitoring
|   |   |-- Security Information and Event Management (SIEM)
|   |   |   |-- Splunk, ELK Stack, Microsoft Sentinel
|   |   |-- Log Management and Analysis
|   |   |   |-- Log Analysis, Correlation / SIEM / SOAR / AI Agents
|   |   |   |-- Event Logs, Syslogs, Netflow
|   |   |   |-- Packet Captures, Firewall Logs
|   |   |-- NetFlow Analysis
|   |   |   |-- NetFlow vs sFlow vs IPFIX
|   |   |-- Full Packet Inspection
|   |   |-- Threat Intelligence (CTI)
|   |   |   |-- MITRE ATT&CK, Diamond Model, Kill Chain
|   |   |   |-- Indicators of Compromise (IoCs)
|   |   |   |-- Indicators of Attack (IoAs)
|   |   |   |-- Threat Intelligence Platform (TIP) Integration
|   |   |   |-- MITRE ATT&CK Navigator
|   |   |   |-- [CISO] Partnerships with ISACs
|   |   |-- SOAR (Security Orchestration, Automation and Response)
|   |   |   |-- Automation and SOAR Playbooks
|   |   |-- DLP (Data Loss Prevention) Monitoring
|   |   |-- UEBA (User and Entity Behavior Analytics)
|   |   |-- Network Detection and Response (NDR)
|   |   |-- Extended Detection and Response (XDR)
|   |   |-- Security Data Lake
|   |   |-- Sigma Rules (detection rule language)
|   |   |-- Snort / Suricata IDS Rules
|   |   |-- Detection-as-Code
|   |   |-- MITRE D3FEND Framework
|   |   |-- Deception Technologies for Breach Detection
|   |   |-- Detect Misconfigurations
|   |   |-- MSSP Integration
|   |-- Security Operations Center (SOC)
|   |   |-- SOC Tiers and Roles
|   |   |-- [CISO] SOC Resource Management
|   |   |-- SOC Staff Continuous Training
|   |   |-- [CISO] Shift Management and SOC Procedures
|   |   |-- [CISO] SOC Metrics and Reports
|   |   |-- [CISO] SOC and NOC Integration
|   |   |-- [CISO] SOC Tech Stack Management
|   |   |-- [CISO] SOC DR Exercises
|   |   |-- Alert Triage and Incident Management
|   |   |-- Playbooks and Runbooks
|   |   |-- Tabletop Exercises
|   |   |-- MTTD / MTTR Metrics (Mean Time to Detect / Respond)
|   |   |-- Purple Team Maturity (VECTR, SCYTHE)
|   |   |-- False Positive / False Negative / True Positive / True Negative
|   |   |-- Red Team / Blue Team Exercises
|   |   |-- Integrate Cloud-Based Security Tools into SOC
|   |-- Threat Detection Capability
|   |   |-- [CISO] Gap Assessment
|   |   |-- [CISO] Prioritization to Fill Gaps
|   |   |-- [CISO] Long-Term Trend Analysis
|   |   |-- [CISO] Integrate New Data Sources (IoT, unstructured data)
|   |   |-- [CISO] Prepare for Unplanned Work
|   |   |-- [CISO] DevOps Integration
|   |   |-- Hypothesis-Driven Threat Hunting
|   |   |-- Threat Hunting Maturity Model
|   |   |-- False Positive Tuning and Alert Fatigue Reduction
|   |   |-- Endpoint Telemetry Collection
|   |   |-- EDR Tuning and Deployment
|   |   |-- Threat Hunting with Splunk / ELK
|   |   |-- Cyber Deception and Active Defense
|   |   |-- Breach and Attack Simulation (BAS) Tools (Cymulate, AttackIQ)
|   |   |-- Security Champions Program
|   |   |-- Security Metrics: KPIs, KRIs, OKRs
|   |-- Analysis Tools
|   |   |-- VirusTotal, Any.run, Joe Sandbox
|   |   |-- urlvoid, urlscan, WHOIS
|   |-- Common Hacking Distros
|   |   |-- Kali Linux
|   |   |-- Parrot OS
|   |-- Living off the Land
|   |   |-- LOLBAS (Windows)
|   |   |-- GTFOBINS (Linux)
|   |   |-- WADCOMS
|   |-- Security Terms Reference
|   |   |-- Antivirus, Antimalware, EDR, DLP, ACL
|   |   |-- Firewall and Next-Generation Firewall (NGFW)
|   |   |-- HIPS, NIDS, NIPS, Host-Based Firewall
|   |   |-- Sandboxing
|
|-- Incident Response and Forensics
|   |-- Incident Response Process
|   |   |-- Preparation -> Identification -> Containment
|   |   |-- Eradication -> Recovery -> Lessons Learned
|   |   |-- Incident Response Teams (CSIRT / CERT)
|   |   |-- Incident Response Playbooks
|   |   |-- [CISO] Incident Readiness Assessment
|   |   |-- [CISO] Update and Test Incident Response Plan
|   |   |-- [CISO] Set Leadership Expectations
|   |   |-- Communication and Escalation Procedures
|   |   |-- [CISO] Media Relations
|   |   |-- [CISO] Managing Relationships with Law Enforcement
|   |   |-- [CISO] Forensic and IR Partner / Retainer
|   |   |-- Adequate Logging for IR
|   |   |-- [CISO] Post-Incident Analysis and Future Avoidance
|   |   |-- [CISO] Cyber Risk Insurance
|   |-- Breach Exercises and Readiness
|   |   |-- IR Playbook Testing
|   |   |-- Breach Simulations and Mock Exercises
|   |   |-- First Responders Training
|   |-- Data Breach Preparation
|   |   |-- Data Breach Response Plan
|   |   |-- Forensic Investigation Process
|   |   |-- Evidence Preservation
|   |-- Ransomware Preparedness
|   |   |-- Identify Critical Systems
|   |   |-- [CISO] Ransomware Business Impact Assessment (BIA)
|   |   |-- [CISO] Tie with BC/DR Plans
|   |   |-- Devise Containment Strategy
|   |   |-- Ensure Adequate Backups (Periodic + Offline)
|   |   |-- Periodic Backup Testing
|   |   |-- Implement Machine Integrity Checking
|   |   |-- Mock Ransomware Exercises
|   |-- Supply Chain Incident Management
|   |   |-- Software Component Inventory
|   |   |-- Integrate into Vulnerability Management
|   |   |-- Integrate into SDLC and Risk Management
|   |   |-- AI Models, Agents and Tools (supply chain risk)
|   |-- Digital Forensics
|   |   |-- Evidence Collection and Chain of Custody
|   |   |-- Disk and Memory Forensics
|   |   |-- Data Recovery
|   |   |-- Log Forensics
|   |   |-- Forensic Tools (Autopsy, EnCase, Volatility, FTK Imager, winhex, memdump, dd)
|   |   |-- CLI Tools for IR: cat, dd, head, tail, grep
|   |   |-- Disk Imaging and Write Blockers
|   |   |-- Volatile vs Non-Volatile Data (order of volatility)
|   |   |-- DFIR Reporting Standards and Templates
|   |   |-- Memory Acquisition Tools (WinPmem, LiME, Magnet RAM)
|   |   |-- Memory Forensics: Process Injection and Hollowing
|   |   |-- Cloud Forensics (AWS CloudTrail, Azure Monitor Logs)
|   |   |-- Container Forensics
|   |   |-- Mobile Device Forensics (iOS, Android)
|   |   |-- Digital Forensics Readiness Planning
|   |   |-- SANS FOR Courses Reference (FOR500, FOR508, FOR572, FOR610)
|   |   |-- Windows Forensic Artifacts (Event IDs, Prefetch, Registry Hives)
|   |   |-- Linux Forensic Artifacts (/proc, bash history, cron)
|   |   |-- Browser Forensics
|   |   |-- Email Header Analysis
|   |   |-- Timeline Analysis and Super-Timeline
|   |   |-- Anti-Forensics Techniques
|   |-- Network Forensics
|   |   |-- Packet Capture Analysis
|   |   |-- NetFlow and Traffic Analysis
|   |   |-- Network Forensics with Zeek (Bro)
|   |   |-- Log Sources and Correlation Rules
|   |   |-- Indicators of Compromise at Artifact Level
|   |   |-- Identifying C2 (Command and Control) Channels
|   |-- Malware Analysis
|   |   |-- Static Analysis
|   |   |   |-- File Type Identification (magic bytes)
|   |   |   |-- String Extraction
|   |   |   |-- Disassembly (Ghidra, IDA Pro, Binary Ninja)
|   |   |   |-- YARA Rules
|   |   |-- Dynamic Analysis
|   |   |   |-- Sandbox Environments (Any.run, Cuckoo Sandbox)
|   |   |   |-- Behavioral Monitoring (process, network, registry)
|   |   |   |-- Debugging (x64dbg, OllyDbg)
|   |   |   |-- Anti-Disassembly Techniques
|   |   |   |-- Code Obfuscation Techniques
|   |   |   |-- Sandbox Evasion Techniques
|   |   |-- Malware Types Deep Dive
|   |   |   |-- Rootkits and Kernel-level Malware
|   |   |   |-- Bootkits, Fileless Malware
|   |   |   |-- Ransomware Mechanics and Encryption
|   |   |   |-- Polymorphic and Metamorphic Malware
|   |   |   |-- Dropper and Loader Techniques
|   |   |   |-- Kernel Rootkit Internals
|   |   |   |-- Bootkit Analysis
|   |   |   |-- Ransomware Negotiation Tactics
|   |   |   |-- C2 Communication Patterns (beaconing, domain fronting)
|
|-- Red Team / Blue Team / Purple Team
|   |-- Red Team (Offensive)
|   |   |-- Penetration Testing Methodology
|   |   |   |-- Rules of Engagement
|   |   |   |-- Recon -> Exploit -> Post-Exploit -> Report
|   |   |-- Common Frameworks
|   |   |   |-- Metasploit, Cobalt Strike, Sliver, Havoc, Brute Ratel
|   |   |-- OSINT and Reconnaissance
|   |   |   |-- Passive vs Active Recon
|   |   |   |-- Google Dorking, Shodan, Censys
|   |   |   |-- Domain and IP Research (WHOIS, ASN, DNS history)
|   |   |   |-- Tools: Maltego, theHarvester, Recon-ng, SpiderFoot
|   |   |   |-- OSINT Framework (osintframework.com)
|   |   |-- Active Directory Attack Paths (BloodHound, SharpHound)
|   |   |-- Lateral Movement Techniques (PsExec, WMI, SMB relay)
|   |   |-- Credential Dumping (Mimikatz, LSASS)
|   |   |-- LLMNR / NBT-NS Poisoning (Responder)
|   |   |-- Evasion Techniques (AV / EDR bypass)
|   |   |-- DLL Hijacking and Sideloading
|   |   |-- UAC Bypass Techniques
|   |   |-- Token Impersonation and Manipulation
|   |   |-- Process Injection Techniques
|   |   |-- NTLM Relay Attacks
|   |   |-- Living off Trusted Sites (LOTS)
|   |   |-- Macro-Based Malware and Office Exploits
|   |   |-- Notable CVEs: PrintNightmare, ZeroLogon, Log4Shell
|   |   |-- Social Engineering Engagements
|   |   |-- Physical Penetration Testing
|   |   |-- Bug Bounty Programs (HackerOne, Bugcrowd)
|   |   |-- Password Cracking (Hashcat, John the Ripper)
|   |   |-- Web Fuzzing and Enumeration (ffuf, gobuster, feroxbuster)
|   |   |-- Subdomain Enumeration (Amass, subfinder)
|   |   |-- SSL Stripping
|   |   |-- Phishing Infrastructure Setup
|   |   |-- C2 Infrastructure (redirectors, CDN fronting)
|   |   |-- Automated Pen Testing (AI-assisted)
|   |-- Blue Team (Defensive)
|   |   |-- Threat Detection and Hunting
|   |   |-- Hardening and Patch Management
|   |   |-- Security Awareness Training
|   |   |-- Backups and Resiliency
|   |-- Purple Team
|   |   |-- Collaborative Offensive / Defensive Exercises
|   |   |-- ATT&CK-based Adversary Simulations
|   |   |-- Measuring Detection Coverage
|
|-- Security Architecture
|   |-- Network Architecture
|   |   |-- Traditional Network Segmentation
|   |   |-- Micro-Segmentation Strategy
|   |   |-- Application Protection
|   |   |-- Defense-in-Depth Strategy (implementation)
|   |   |-- DMZ, Overlay Networks, Secure Enclaves
|   |   |-- Perimeter vs DMZ vs Segmentation
|   |-- Zero Trust Architecture
|   |   |-- Principles: "Never Trust, Always Verify"
|   |   |-- Assume Breach (core ZT principle)
|   |   |-- Explicit Verification (always authenticate and authorize)
|   |   |-- Continuous Verification and Authentication
|   |   |-- Zero Trust Models and Roadmap
|   |   |-- Zero Trust Access to Applications
|   |   |-- Microsegmentation
|   |   |-- Identity-Centric Security
|   |   |-- Context-Aware Access (device health, location, risk score)
|   |   |-- Policy Decision Point (PDP) and Policy Enforcement Point (PEP)
|   |   |-- Device Trust and Compliance (ZT device pillar)
|   |   |-- Software-Defined Perimeter (SDP)
|   |   |-- CISA Zero Trust Maturity Model
|   |   |-- DoD Zero Trust Strategy and Reference Architecture
|   |   |-- BeyondCorp (Google Zero Trust Model)
|   |   |-- SASE / SSE Strategy
|   |   |-- Implementing Zero Trust (NIST SP 800-207)
|   |-- Remote Access Architecture
|   |   |-- VPN Technologies
|   |   |-- Zero Trust Network Access (ZTNA)
|   |   |-- Bastion Hosts / Jump Servers
|   |-- Encryption Technologies and Key Management
|   |   |-- Encryption Technologies (at rest, in transit)
|   |   |-- PKI and Certificate Management
|   |   |-- Quantum-Safe Encryption Planning
|   |-- Resilience Architecture
|   |   |-- Business Continuity Planning (BCP)
|   |   |-- Disaster Recovery (DR) Planning
|   |   |-- Understand Backups and Resiliency
|   |-- [CISO] SDLC and Project Delivery Lifecycle
|   |   |-- Embedding Security in Project Requirements
|   |   |-- Threat Modeling and Design Reviews
|   |   |-- Security Testing in SDLC
|   |   |-- Certification and Accreditation
|
|-- Risk Management
|   |-- Risk Assessment
|   |   |-- Risk Assessment Methodology and Framework
|   |   |-- [CISO] Cyber Risk Quantification (CRQ)
|   |   |-- [CISO] Single Risk Dashboard
|   |   |-- [CISO] Centralized Risk Register (automated)
|   |   |-- Ongoing Risk Assessments and Pen Testing
|   |   |-- Understand the Definition of Risk
|   |   |-- Risk Appetite and Risk Tolerance
|   |   |-- Inherent Risk vs Residual Risk
|   |   |-- Security Exception Management
|   |   |-- Audit Trail Requirements
|   |   |-- Evidence Collection for Audits
|   |   |-- Penetration Test Scoping and Rules of Engagement
|   |   |-- Third-Party Security Assessments
|   |-- Third-Party Risk
|   |   |-- [CISO] Third-Party Risk Management (TPRM) Automation
|   |   |-- Vendor Contracts and Security Requirements
|   |   |-- Supply Chain Risk
|   |-- Data-Centric Security
|   |   |-- Data Discovery
|   |   |-- Data Classification
|   |   |-- Access Control for Data
|   |   |-- Data Loss Prevention (DLP)
|   |   |-- Customer and Partner Access Controls
|   |   |-- Encryption and Data Masking
|   |   |-- Monitoring and Alerting
|   |-- Policies and Procedures
|   |   |-- Security Policy Development
|   |   |-- Phishing and Associate Awareness
|   |   |-- Code Reviews and SAST
|   |   |-- [CISO] Automate Risk Scoring
|   |   |-- [CISO] Automate Asset Inventory
|   |   |-- [CISO] Automate Risk Register
|   |   |-- [CISO] Automate Security Metrics
|   |   |-- [CISO] Automate Threat Hunting
|   |   |-- [CISO] Automate Incident Response (where applicable)
|   |   |-- [CISO] Automate Compliance Checks
|
|-- OT / SCADA Security
|   |-- Operational Technology Overview
|   |   |-- Industrial Control Systems (ICS)
|   |   |-- PLCs (Programmable Logic Controllers)
|   |   |-- SCADA Systems
|   |   |-- HMIs (Human-Machine Interfaces)
|   |-- OT-Specific Threats
|   |   |-- Targeting Critical Infrastructure
|   |   |-- Physical Safety Implications
|   |   |-- Nation-State Actors (Stuxnet, TRITON, etc.)
|   |-- OT Security Controls
|   |   |-- Network Segmentation for OT (Purdue Model)
|   |   |-- Air-Gapping and Data Diodes
|   |   |-- OT-Specific Monitoring Tools
|   |   |-- Patch Management Challenges in OT
|   |-- Standards and Frameworks
|   |   |-- IEC 62443
|   |   |-- NERC CIP (energy sector)
|   |   |-- NIST SP 800-82
|
|-- IoT Security
|   |-- IoT Architecture and Threats
|   |   |-- Attack Surface of IoT Devices
|   |   |-- Hardware / Device Security Features
|   |   |-- IoT Communication Protocols
|   |   |-- Device Identity, Authentication and Integrity
|   |   |-- Over-the-Air (OTA) Updates Security
|   |-- IoT Security Controls
|   |   |-- Firmware Analysis and Extraction
|   |   |-- Network Segmentation for IoT
|   |   |-- MQTT and Other IoT Protocol Security
|   |   |-- IoT SaaS Platforms Security
|   |-- IoT Use Cases and Frameworks
|   |   |-- IoT Frameworks Overview
|   |   |-- Autonomous Vehicles, Drones, Medical Devices
|   |   |-- Smart Grid, Smart Cities / Communities
|   |   |-- Industrial IoT (IIoT) and Condition-Based Monitoring
|   |   |-- Track and Trace, Customer Experience
|   |   |-- Edge Computing Security
|   |   |-- Augmented and Virtual Reality
|   |   |-- AI-Based IoT Tools and Applications
|
|-- Mobile Security
|   |-- Mobile Device Management
|   |   |-- BYOD Policy and MDM Solutions
|   |   |-- Lost / Stolen Device Procedures
|   |   |-- Mobile App Inventory
|   |-- Mobile Application Security
|   |   |-- Mobile App Vulnerability Testing
|   |   |-- App Permissions and Data Access
|   |   |-- Secure Storage on Mobile Devices
|   |-- Mobile Protocols
|   |   |-- Bluetooth and BLE Security (mobile context)
|   |   |-- NFC and Infrared
|   |   |-- WPA3 for Mobile
|
|-- Physical Security
|   |-- Physical Access Controls (badges, biometrics, mantraps)
|   |-- CCTV and Surveillance
|   |-- Use of Computer Vision in Physical Security
|   |-- Social Engineering via Physical Access
|   |   |-- Tailgating / Piggybacking
|   |   |-- Shoulder Surfing
|   |   |-- Dumpster Diving
|   |-- Loss and Fraud Prevention
|   |-- Clean Desk Policy
|   |-- Hardware Theft and Device Encryption
|
|-- Compliance and Regulations
|   |-- Cybersecurity Frameworks
|   |   |-- NIST Cybersecurity Framework (CSF)
|   |   |-- NIST Risk Management Framework (RMF)
|   |   |-- NIST/FISMA
|   |   |-- ISO/IEC 27001
|   |   |-- CIS Controls (v8)
|   |   |-- SOC 2 / SSAE 18 (Type I and Type II)
|   |   |-- COBIT, COSO, ITIL, FAIR (risk and governance frameworks)
|   |   |-- FISMA, CMMC
|   |   |-- [CISO] Regular Audits
|   |   |-- NIS2 Directive (EU)
|   |   |-- ISO 22301 (Business Continuity Management)
|   |   |-- Cyber Essentials (UK)
|   |   |-- FedRAMP (US Federal Cloud)
|   |   |-- ISO 27701 (Privacy Information Management -- GDPR extension)
|   |   |-- SOC 2 Trust Service Criteria (Security, Availability, Confidentiality, PI, Processing Integrity)
|   |   |-- PCI DSS v4 (current version)
|   |   |-- [CISO] Control Mapping Across Frameworks
|   |   |-- [CISO] GDPR Article 30 (Records of Processing Activities)
|   |   |-- [CISO] GDPR Article 32 (Security of Processing)
|   |   |-- Operational Resilience (DORA context)
|   |   |-- Critical Infrastructure Protection (CIP)
|   |   |-- Secure by Default Principles
|   |   |-- Shift-Left Security
|   |   |-- Security Debt Management
|   |   |-- SWIFT CSP (Customer Security Programme)
|   |   |-- ENISA Guidelines and Frameworks
|   |-- Data Privacy Regulations
|   |   |-- Privacy by Design
|   |   |-- Data Protection Impact Assessment (DPIA)
|   |   |-- Business Impact Analysis (BIA)
|   |   |-- GDPR and CCPA (and other data privacy laws)
|   |   |-- HIPAA / HITECH and HITRUST
|   |   |-- PCI DSS
|   |   |-- SOX
|   |   |-- DORA (Digital Operational Resilience Act)
|   |   |-- SEC Notification Requirements
|   |-- Legal Considerations
|   |   |-- Data Discovery and Data Ownership
|   |   |-- [CISO] Vendor Contracts and Security Clauses
|   |   |-- [CISO] Investigations and Forensics (Legal Hold)
|   |   |-- [CISO] Attorney-Client Privilege
|   |   |-- [CISO] Data Retention and Destruction Policies
|   |-- [CISO] Roles and Responsibilities
|   |   |-- Compliance and Auditors
|   |   |-- Compliance Management
|   |   |-- Stakeholders: HR, Legal, Management
|   |   |-- RACI Charts
|
|-- Advanced Topics
|   |-- Advanced Persistent Threats (APT)
|   |   |-- APT Lifecycle and TTPs (Tactics, Techniques, Procedures)
|   |   |-- Threat Classification (Zero-Day, Known vs Unknown, Nation-State)
|   |   |-- Detection, Mitigation and Threat Hunting
|   |   |-- Nation-State Actor Attribution
|   |-- Reverse Engineering
|   |   |-- Assembly Language Basics (x86/x64)
|   |   |-- Debugging and Tracing Techniques
|   |   |-- Unpacking Obfuscated Malware
|   |   |-- Tools: Ghidra, IDA Pro, x64dbg, Binary Ninja
|   |-- Exploit Development
|   |   |-- Buffer Overflows (stack, heap)
|   |   |-- Heap Spray Attacks
|   |   |-- Format String Vulnerabilities
|   |   |-- Use-After-Free Vulnerabilities
|   |   |-- Return-Oriented Programming (ROP)
|   |   |-- Shellcode Basics
|   |   |-- Mitigations: ASLR, DEP/NX, Stack Canaries (and bypasses)
|   |-- Blockchain Security
|   |   |-- Cryptographic Principles in Blockchain
|   |   |-- Smart Contract Vulnerabilities (reentrancy, integer overflow)
|   |   |-- Wallet and Key Security
|
|-- Emerging Trends
|   |-- AI and Machine Learning in Cybersecurity
|   |   |-- AI-Based Threat Detection and Anomaly Detection
|   |   |-- Log Anomaly Detection (ML-based)
|   |   |-- ML Model Training and Retraining
|   |   |-- Adversarial ML Attacks (model poisoning, evasion)
|   |   |-- Adversarial Attacks on AI Systems
|   |   |-- Algorithm Biases in Security AI
|   |   |-- Automating Incident Response
|   |   |-- AI-Powered Phishing and Deepfakes
|   |-- Securing AI Systems
|   |   |-- AI Policies, Governance and Transparency
|   |   |-- AI Frameworks (NIST AI RMF, Google, IBM, Databricks, etc.)
|   |   |-- Ethical and Responsible Use of AI
|   |   |-- LLMs, Chatbots, Agents and RAG Security
|   |   |-- LLM Prompt Injection (direct and indirect)
|   |   |-- AI-Generated Malware and Deepfake Threats
|   |   |-- Deepfake Detection Techniques
|   |   |-- AI Model Poisoning and Data Poisoning
|   |   |-- Model Inversion Attacks
|   |   |-- Membership Inference Attacks
|   |   |-- LLM Jailbreaking Techniques
|   |   |-- Retrieval-Augmented Generation (RAG) Attack Vectors
|   |   |-- AI Model Watermarking
|   |   |-- Synthetic Data Risks
|   |   |-- AI-Powered Social Engineering
|   |   |-- AI Bias and Fairness in Security Contexts
|   |   |-- Federated Learning Security
|   |   |-- Differential Privacy
|   |   |-- Responsible AI Disclosure
|   |   |-- AI Red Teaming Methodology
|   |   |-- OWASP Top 10 for LLMs
|   |   |-- AI Model Red Teaming
|   |   |-- MCP, A2A and Other AI Protocols
|   |   |-- AI Models and Supply Chain Risks
|   |   |-- Agentic AI Security (tools, frameworks)
|   |   |-- Security of RAG / Vector Databases
|   |   |-- AI Sovereignty and Data Lakes
|   |   |-- Human-in-the-Loop Strategies
|   |   |-- AI Application Security Testing
|   |   |-- Protecting Intellectual Property
|   |   |-- Third-Party AI Tools Risk
|   |-- Using AI as a Security Professional
|   |   |-- Train InfoSec Teams on AI Technologies
|   |   |-- SOC AI Agents
|   |   |-- AI Threat Hunting
|   |   |-- Automated Pen Testing
|   |   |-- Source Code Scanning with AI
|   |   |-- AI for Threat Modeling
|   |   |-- AI Gateways
|   |   |-- Use of GenAI and Data Analytics
|   |   |-- Automating Routine Tasks with AI
|   |   |-- Staff Training and Research via AI
|   |   |-- [CISO] Automate Patching, Risk Scoring, Compliance Checks
|   |   |-- [CISO] Manage Data Process Cost
|   |-- Hardware and Firmware Security
|   |   |-- TPM (Trusted Platform Module)
|   |   |-- Secure Boot and UEFI Security
|   |   |-- Firmware Security and UEFI Rootkits
|   |   |-- Side-Channel Attacks (Spectre, Meltdown, Rowhammer)
|   |   |-- Hardware Security Modules (HSM) -- deployment
|   |-- Specialized Domain Security
|   |   |-- 5G Network Security
|   |   |-- Satellite and Space System Security
|   |   |-- Automotive Cybersecurity (ISO 21434)
|   |   |-- Medical Device Cybersecurity (FDA guidelines)
|   |   |-- Browser Isolation (Remote Browser Isolation -- RBI)
|   |   |-- Dark Web Monitoring (threat intelligence)
|   |   |-- SBOM Extended: VEX (Vulnerability Exploitability eXchange), CSAF
|   |   |-- SCADA / ICS Attack Simulation
|   |   |-- Cyber Threat Simulation (BAS Tools)
|   |-- Supply Chain Security
|   |   |-- Software Bill of Materials (SBOM)
|   |   |-- Dependency Confusion Attacks
|   |   |-- Secure CI/CD Pipelines
|   |   |-- Third-Party Risk Management
|   |   |-- Public Software Repositories Security
|
|-- [CISO] Enterprise / Management Track
|   |-- Governance
|   |   |-- Strategy and Business Alignment
|   |   |-- Security Policies and Standards
|   |   |-- Legal, Regulatory and Contract Compliance
|   |   |-- Risk Management / Control Frameworks
|   |   |   |-- NIST, ISO, COBIT, COSO, ITIL, FAIR, FISMA, CMMC (full framework list)
|   |   |   |-- [CISO] Visibility Across Multiple Frameworks
|   |   |-- Data Ownership, Sharing, and Data Privacy
|   |   |-- [CISO] Conflict Management
|   |   |-- Metrics and Reporting
|   |   |   |-- Operational Metrics
|   |   |   |-- Executive Metrics
|   |   |   |-- Validating Effectiveness of Metrics
|   |   |-- IT / OT / IoT/IIoT Convergence
|   |   |-- Cooperative SOC and Collaborative InfoSec
|   |   |-- Tools and Vendors Consolidation
|   |   |-- [CISO] Evaluating Control Effectiveness
|   |   |-- Maintaining a 1-3 Year Security Roadmap / Plan
|   |   |-- Board Oversight and Board Presentations
|   |   |-- NICE Framework (cybersecurity workforce)
|   |-- Business Enablement
|   |   |-- Mergers and Acquisitions
|   |   |   |-- Acquisition Risk Assessment
|   |   |   |-- Network / Application / Cloud Integration Cost
|   |   |   |-- IAM Integration
|   |   |   |-- Security Tools Rationalization
|   |   |-- Business Partnerships
|   |   |-- HR / Onboarding / Termination Processes
|   |   |-- Agility, Business Continuity and DR
|   |   |-- Understand Industry Trends
|   |   |-- Evaluating Emerging Technologies (Quantum, Crypto, GenAI)
|   |-- Team Management
|   |   |-- Manage InfoSec Budget
|   |   |   |-- Balancing People, Training, Tools, Travel, Conferences
|   |   |   |-- CapEx and OpEx Considerations
|   |   |   |-- Technology Amortization
|   |   |   |-- Retire Redundant and Underutilized Tools
|   |   |   |-- Consulting and Outsourcing
|   |   |-- Managing Security Projects
|   |   |   |-- Business Case Development
|   |   |   |-- Alignment with IT Projects
|   |   |-- Security Team Branding
|   |   |-- Aligning with Corporate Objectives
|   |   |   |-- Continuous Management Updates and Metrics
|   |   |   |-- Negotiation and Corporate Politics
|   |   |   |-- Innovation and Value Creation
|   |   |   |-- Expectations Management
|   |   |   |-- Show Progress / Risk Reduction
|   |   |   |-- Return on Security Investment (ROSI)
|   |   |-- Staffing and Talent Management
|   |   |   |-- Recruiting, Performance and Retention
|   |   |   |-- Staff Burnout Prevention
|   |   |   |-- Balance FTE and Contractors
|   |   |   |-- Staff Training and Skills Update
|
|-- Career Path
|   |-- Certifications
|   |   |-- Beginner
|   |   |   |-- CompTIA A+
|   |   |   |-- CompTIA Network+
|   |   |   |-- CompTIA Linux+
|   |   |   |-- CompTIA Security+
|   |   |   |-- CCNA (Cisco)
|   |   |   |-- Google Cybersecurity Certificate
|   |   |-- Intermediate
|   |   |   |-- CompTIA CySA+ (Blue Team / Analyst)
|   |   |   |-- CompTIA PenTest+
|   |   |   |-- CEH -- Certified Ethical Hacker (EC-Council)
|   |   |   |-- eJPT -- eLearnSecurity Junior Penetration Tester
|   |   |   |-- eCPPT -- eLearnSecurity Certified Professional Penetration Tester
|   |   |   |-- GSEC -- GIAC Security Essentials
|   |   |   |-- GPEN -- GIAC Penetration Tester
|   |   |   |-- GWAPT -- GIAC Web Application Penetration Tester
|   |   |   |-- CISA -- Certified Information Systems Auditor (ISACA)
|   |   |   |-- CISM -- Certified Information Security Manager (ISACA)
|   |   |-- Offensive Security (OffSec)
|   |   |   |-- OSCP -- Offensive Security Certified Professional
|   |   |   |-- OSEP -- Offensive Security Experienced Penetration Tester
|   |   |   |-- OSED -- Offensive Security Exploit Developer
|   |   |   |-- OSWE -- Offensive Security Web Expert
|   |   |   |-- OSWP -- Offensive Security Wireless Professional
|   |   |   |-- OSDA -- Offensive Security Defense Analyst
|   |   |-- HackTheBox Certifications
|   |   |   |-- HTB CPTS -- Certified Penetration Testing Specialist
|   |   |   |-- HTB CBBH -- Certified Bug Bounty Hunter
|   |   |   |-- HTB CDSA -- Certified Defensive Security Analyst
|   |   |   |-- HTB CWEE -- Certified Web Exploitation Expert
|   |   |-- Advanced / Expert
|   |   |   |-- CISSP -- Certified Information Systems Security Professional (ISC2)
|   |   |   |-- CREST (various tracks: CRT, CCT, CPSA)
|   |   |   |-- GXPN -- GIAC Exploit Researcher and Advanced Penetration Tester
|   |   |   |-- GREM -- GIAC Reverse Engineering Malware
|   |   |   |-- GCFE -- GIAC Certified Forensic Examiner
|   |   |   |-- GCFA -- GIAC Certified Forensic Analyst
|   |   |   |-- GCIA -- GIAC Certified Intrusion Analyst
|   |   |   |-- GNFA -- GIAC Network Forensic Analyst
|   |   |   |-- SANS / GIAC (various tracks)
|   |   |-- Cloud Security Certifications
|   |   |   |-- AWS Security Specialty
|   |   |   |-- Microsoft Azure Security Engineer (AZ-500)
|   |   |   |-- Google Professional Cloud Security Engineer
|   |   |   |-- CCSP -- Certified Cloud Security Professional (ISC2)
|   |   |-- Management / CISO Track
|   |   |   |-- CISSP (ISC2)
|   |   |   |-- CISM (ISACA)
|   |   |   |-- CRISC -- Certified in Risk and Information Systems Control (ISACA)
|   |   |   |-- CGEIT -- Certified in Governance of Enterprise IT (ISACA)
|   |   |   |-- CCISO -- Certified Chief Information Security Officer (EC-Council)
|   |-- Practice Platforms
|   |   |-- HackTheBox (https://www.hackthebox.com)
|   |   |-- TryHackMe (https://tryhackme.com)
|   |   |-- VulnHub (https://www.vulnhub.com)
|   |   |-- picoCTF (https://picoctf.org)
|   |   |-- PentesterLab (https://pentesterlab.com)
|   |   |-- CyberDefenders (https://cyberdefenders.org)
|   |   |-- SANS Holiday Hack Challenge
|   |   |-- PortSwigger Web Security Academy (https://portswigger.net/web-security)
|   |   |-- Root Me (https://www.root-me.org)
|   |   |-- Hack The Box Academy (https://academy.hackthebox.com)
|   |-- Programming Skills
|   |   |-- Python
|   |   |-- Bash / PowerShell
|   |   |-- Go
|   |   |-- JavaScript
|   |   |-- C / C++
|   |-- Tools to Know
|   |   |-- MS Office Suite, Google Suite (for reporting and documentation)
|   |   |-- Password Managers (for personal OpSec)
|   |   |-- Obsidian / Notion (note-taking and knowledge management)
|   |   |-- Draw.io / Lucidchart (security diagrams)
|   |-- Soft Skills
|   |   |-- Technical Writing and Security Reporting
|   |   |-- CTF Strategy and Approach
|   |   |-- Bug Bounty Hunting Methodology
|   |   |-- Building a Home Lab
|   |   |-- Staying Current (threat feeds, security blogs, CVE tracking)
|   |   |-- Security Research and Publication
|   |   |-- Interview Preparation for Security Roles
|   |   |-- Communication with Non-Technical Stakeholders
|   |   |-- Understand Your Audience (Stakeholders, HR, Legal, Management)
|   |   |-- Collaboration with Dev, Ops, Legal, Management
|   |   |-- Continuous Learning Mindset (Keep Learning)
```


---

## Glossary

**[`^        back to top        ^`](#overview)**

> [!TIP]
> 📚 **849 entries** – abbreviations and acronyms used across cybersecurity, networking, and adjacent fields.

<div align="center">
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExb2NkdGh4bnppMzdyeHBpbDFlY3d0b3FpY21sN3V1YWd4MHZhY2k4diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/4B1BTOMTi8b3OdPrzy/giphy.gif" alt="Cybersecurity" width=300 height=300 />
</div>

| Abbreviation | Meaning | Definition |
| --- | --- | --- |
| A | Availability | One of the three CIA Triad pillars – ensuring authorized users can access systems and data when needed. |
| A2A | Agent-to-Agent Protocol | An emerging AI protocol enabling direct communication and task delegation between AI agents. |
| AAA | Authentication, Authorization, Accounting | A security framework for controlling access: verifying identity (Authentication), granting permissions (Authorization), and recording activity (Accounting). |
| AAD | Azure Active Directory | Microsoft's cloud-based identity and access management service, now rebranded as Microsoft Entra ID. |
| ABAC | Attribute-Based Access Control | An access control model granting permissions based on user, resource, and environmental attributes rather than fixed roles. |
| ABLE | Actor, Behavior, Location, Evidence | A threat intelligence framework describing incidents by Actor, Behavior, Location, and Evidence. |
| AC | Attack Complexity | Attack Complexity – a CVSS metric indicating how difficult conditions must be for an attacker to exploit a vulnerability. |
| ACA | Azure Container App | Microsoft Azure's serverless container hosting service. |
| ACE | Access Control Entry | An individual entry in an Access Control List specifying permissions for a user or group on a resource. |
| ACL | Access Control List | A list of rules specifying which users or systems are granted or denied access to a resource. |
| ACLE | Account Life Cycle Events | Events tracking the full lifecycle of an account: creation, modification, suspension, and deletion. |
| ACM | AWS Certificate Manager | An AWS service for provisioning, managing, and deploying SSL/TLS certificates. |
| ACME | Automated Certificate Management Environment | A protocol automating certificate issuance and renewal between a CA and a web server. |
| ACPI | Advanced Configuration and Power Interface | An open standard defining power management and hardware configuration interfaces for operating systems. |
| ACRE | ATT&CK Coverage Ratio Evaluation | A metric measuring how well an organization's detection capabilities cover MITRE ATT&CK techniques. |
| AD CS | Active Directory Certificate Services | Microsoft's PKI role service providing certificate management for issuing and managing digital certificates. |
| AD DS | Active Directory Domain Service | Microsoft's directory service for managing users, computers, and policies in a Windows domain environment. |
| AD FS | Active Directory Federation Services | A Microsoft service providing SSO and federated identity across organizational boundaries. |
| ADFS | Active Directory Federated Services | The older name for AD FS (Active Directory Federation Services) – Microsoft's federated identity and SSO service. |
| ADR | Architecture Design Review | A formal document capturing a significant architectural decision, its context, and its consequences. |
| ADSI | Active Directory Service Interfaces | A Windows API for interacting with Active Directory and other directory services programmatically. |
| AEP | ATT&CK Emulation Plans | Detailed adversary simulation plans based on real-world threat actor TTPs from MITRE ATT&CK. |
| AES | Advanced Encryption Standard | A symmetric block cipher adopted as the US encryption standard, supporting 128, 192, and 256-bit keys. |
| AH | Authentication Header | An IPsec protocol providing data integrity and authentication for IP packets without encryption. |
| AI | Artificial Intelligence | Technology enabling computers to simulate human learning, problem-solving, and decision-making. |
| AitM | Adversary in the Middle | An attack where the adversary secretly intercepts and can modify communications between two parties. |
| AKS | Azure Kubernetes Service | Microsoft Azure's managed Kubernetes container orchestration service. |
| ALB | Amazon Load Balancer | AWS's managed load balancer distributing incoming HTTP/HTTPS traffic across multiple targets. |
| ALPN | Application-Layer Protocol Negotiation | A TLS extension allowing client and server to negotiate the application protocol during the TLS handshake. |
| AMD | Advanced Micro Devices | A semiconductor company; relevant in security for AMD SEV (Secure Encrypted Virtualization) in confidential computing. |
| AMI | Amazon Machine Image | A pre-configured virtual machine image used to launch EC2 instances on AWS. |
| AMQP | Advanced Message Query Protocol | An open messaging protocol for reliable, asynchronous message-oriented middleware communication. |
| AMSI | Antimalware Scan Interface | A Windows API allowing applications to request antimalware scans of content at runtime. |
| ANSI | American National Standards Institute | The US body coordinating voluntary standards, including many IT and security standards. |
| APAKE | Augmented Password Authenticated Key Exchange | A password authentication protocol preventing server compromise from exposing user passwords. |
| API | Application Programming Interface | A set of protocols and definitions allowing software components to communicate with each other. |
| APIPA | Automatic Private IP Addressing | A Windows feature auto-assigning a 169.254.x.x IP address when a DHCP server is unreachable. |
| APT | Advanced Persistent Threat / Advanced Packaging Tool | Advanced Persistent Threat – a sophisticated, long-term attack campaign by nation-state or organized groups. Also: Advanced Packaging Tool (Linux package manager). |
| ARO | Annual Rate of Occurrence | A risk metric representing how often a specific threat is expected to occur per year. |
| ARP | Address Resolution Protocol | A network protocol mapping IP addresses to MAC addresses on a local network. |
| AS-REP | Authentication Service Response | The Kerberos response to an AS-REQ; AS-REP Roasting targets accounts without pre-authentication enabled. |
| ASC | Azure Security Center | Microsoft's unified security management system for Azure, now called Microsoft Defender for Cloud. |
| ASLR | Address Space Layout Randomization | An OS security technique randomizing key memory areas to prevent exploitation. |
| ASM | Attack Surface Management | The continuous process of discovering, classifying, and reducing an organization's attack exposure. |
| ASN | Autonomous System Number | A unique number assigned to an autonomous system for use in BGP routing; used in OSINT and network reconnaissance. |
| ASPX | Active Server Page Extended | File extension for ASP.NET web pages – a common target in web server attacks. |
| ASR | Attack Surface Reduction | Windows Defender rules blocking behaviors commonly used by malware, reducing attack surface. |
| AST | Abstract Syntax Tree | A tree representation of source code structure used in static analysis and security scanning. |
| ASVS | Application Security Verification Standard | An OWASP framework defining security requirements for web application design, development, and testing. |
| ATA | Advanced Technology Attachment | A disk interface standard; also Advanced Threat Analytics – a Microsoft on-premises threat detection solution. |
| ATM | Asynchronous Transfer Mode | A cell-switching network technology for transmitting voice, video, and data. |
| ATO | Account Takeover | An attack where an adversary gains unauthorized access to another user's account, often via credential stuffing or phishing. |
| ATS | Applicant Tracking System | A human resources software platform for tracking job applicants through recruitment. |
| ATT | App Tracking Transparency | Apple's framework requiring apps to request permission before tracking users across other apps. |
| ATT&CK | Adversarial Tactics, Techniques, and Common Knowledge | The MITRE framework documenting real-world adversary tactics, techniques, and procedures. |
| AuthPF | Authentication Packet Filter | An OpenBSD packet filter changing firewall rules based on authenticated user sessions. |
| AV | Antivirus / Attack Vector | Antivirus – software detecting malware. Also: Attack Vector – a CVSS metric on how an attacker reaches the vulnerability. |
| AWL | App Whitelisting | A security control allowing only pre-approved, trusted applications to execute on a system. |
| AXFR | DNS Zone Transfer / DNS Query Type | A DNS query type for zone transfers; can expose all DNS records if accessible to unauthorized parties. |
| AXS | API Cross-Site Scripting | A cross-site scripting attack specifically targeting API endpoints. |
| AZ | Availability Zone | An isolated data center location within a cloud region providing fault tolerance. |
| AZ-500 | Microsoft Azure Security Engineer Certification | Microsoft's intermediate certification for implementing security controls and threat protection in Azure environments. |
| BAS | Breach and Attack Simulation | Tools continuously simulating real-world attack scenarios to test and validate defensive controls. |
| BC | Business Continuity | The capability of an organization to continue delivering services at acceptable levels following a disruption. |
| BCP | Business Continuity Plan | A documented strategy ensuring critical business functions continue during and after a disaster or security incident. |
| BEAST | Browser Exploit Against SSL/TLS | A 2011 TLS 1.0 attack exploiting CBC mode; mitigated by TLS 1.2+ and RC4 (now also deprecated). |
| BEC | Business Email Compromise | A social engineering attack using compromised or spoofed business email to authorize fraudulent transactions. |
| BFLA | Broken Function Level Authorization | An API vulnerability where functions are accessible to users without proper authorization (OWASP API #5). |
| BFP | Berkeley Packet Filter | A kernel-level interface for capturing and filtering network packets; the foundation for eBPF. |
| BGP | Border Gateway Protocol | The routing protocol managing how packets are routed across the internet between autonomous systems. |
| BIA | Business Impact Analysis | A process identifying critical business functions and the impact of disruption, used in BCP and DR planning. |
| BIOC | Behavioral Indicator of Compromise | Evidence of a security incident based on behavioral anomalies rather than known signatures. |
| BITS | Background Intelligence Transfer Service | A Windows service transferring files in the background; abused by malware for persistent C2 communication. |
| BLE | Bluetooth Low Energy | A power-efficient variant of Bluetooth designed for IoT devices; subject to eavesdropping and relay attacks. |
| BLOB | Binary Large Object | A collection of binary data stored as a single entity in a database or object storage. |
| BOLA | Broken Object Level Authorization | An API vulnerability where attackers access or modify objects belonging to other users (OWASP API #1). |
| BSIMM | Building Security In Maturity Model | A data-driven framework measuring software security practices by comparison to real-world initiatives. |
| BSS | Base Service Set | The basic building block of a Wi-Fi network consisting of one access point and its associated stations. |
| BYOD | Bring Your Own Device | A policy allowing employees to use personal devices for work activities and corporate resource access. |
| BYOL | Bring Your Own Land | An attack technique using tools and infrastructure already present in the target environment. |
| BYOVD | Bring Your Own Vulnerable Driver | An attack loading a legitimate but vulnerable signed kernel driver to bypass security controls. |
| C | Confidentiality | Confidentiality – one of the CIA Triad pillars; ensuring data is accessible only to authorized parties. |
| C2 | Command and Control | Infrastructure and communication channels used by attackers to remotely control compromised systems. |
| C3 | Custom Command and Control | A customizable framework for building command and control infrastructure for red team operations. |
| C4 | Customizable Command and Control Center | An extended C2 framework offering advanced customization for complex red team engagements. |
| CA | Certification Authority | A trusted entity that issues digital certificates binding public keys to identities. |
| CAM | Content Addressable Memory | High-speed memory in network switches storing MAC address tables for fast packet forwarding. |
| CAPE | Config and Payload Extraction | A malware analysis sandbox extracting configurations and payloads from malicious samples. |
| CAPTCHA | Completely Automated Public Turing Test to tell Computers and Humans Apart | A challenge-response test used to determine whether the user is human or an automated bot. |
| CAR | Cyber Analytics Repository | A MITRE knowledge base of analytics for detecting adversary behaviors documented in ATT&CK. |
| CASB | Cloud Access Security Broker | Security software between cloud users and providers enforcing security, compliance, and governance policies. |
| CBA | Certificate-Based Authentication | An authentication method using digital certificates instead of passwords to verify identity. |
| CBC | Cipher Block Chaining | A block cipher mode where each plaintext block is XORed with the previous ciphertext block before encryption. |
| CBC-MAC | Cipher Block Chaining Message Authentication Code | A MAC algorithm using CBC mode to generate a fixed-size authentication tag. |
| CBSP | Cloud-Based Security Provider | A third-party provider offering cloud-hosted security services including firewalls and SIEM. |
| CCA | ARM Confidential Compute Architecture | ARM's hardware technology for creating isolated Trusted Execution Environments on ARM processors. |
| CCRA | Common Criteria Recognition Arrangement | A mutual recognition agreement among countries accepting Common Criteria security evaluations. |
| CCT | CREST Certified Tester | An intermediate-level CREST certification for penetration testers. |
| ccTLD | Country Code Top-Level Domain | A top-level domain reserved for a country or territory (e.g., .uk, .de, .ua). |
| CCTV | Closed-Circuit Television | A video surveillance system; relevant to physical security and the use of computer vision in security. |
| CDC | Cyber Defense Center | A team or facility focused on monitoring, detecting, and responding to cybersecurity threats. |
| CDM | Continuous Diagnostics and Mitigation | A DHS program continuously monitoring IT assets to improve federal agency cybersecurity posture. |
| CDN | Content Delivery Network | A distributed network of servers delivering web content to users based on geographic proximity. |
| CDP | Certificate Distribution Point | A directory or URL where a Certificate Revocation List is hosted for retrieval. |
| CDS | Cross Domain Solution | A system or device controlling and monitoring data transfer between different security domains. |
| CEH | Certified Ethical Hacker | An EC-Council certification validating knowledge of ethical hacking and penetration testing techniques. |
| CERT | Computer Emergency Response Team | A team of security experts handling incident response, coordination, and vulnerability disclosure. |
| CFG | Control Flow Guard | A Windows security feature preventing code from jumping to unexpected locations, mitigating ROP attacks. |
| CFP | Call for Papers | An invitation for researchers and practitioners to submit technical presentations to conferences. |
| CHAP | Challenge-Handshake Authentication Protocol | An authentication protocol using a challenge-response mechanism to verify identity without transmitting passwords. |
| CI/CD | Continuous Integration / Continuous Delivery | A DevOps practice automating building, testing, and deployment of code changes through pipelines. |
| CIA | Confidentiality, Integrity, Availability | The foundational triad of information security: Confidentiality, Integrity, and Availability. |
| CIEM | Cloud Infrastructure Entitlement Management | Tools managing and enforcing least-privilege entitlements across cloud resources and identities. |
| CIFS | Common Internet File System | A network file sharing protocol (dialect of SMB) used primarily on Windows networks. |
| CIP | Critical Infrastructure Protection | Standards and practices protecting essential services (power, water, finance) from physical and cyber threats. |
| CIS | Center for Internet Security | A nonprofit producing the CIS Controls and CIS Benchmarks – widely used security configuration standards. |
| CISO | Chief Information Security Officer | The senior executive responsible for an organization's information and cybersecurity strategy. |
| CL | Content-Length | An HTTP header indicating the size of the request or response body in bytes. |
| CLI | Command-Line Interface | A text-based interface for interacting with systems by typing commands; essential for security work on Linux and Windows. |
| CLM | Constrained Language Mode | A PowerShell security mode restricting access to sensitive language elements to reduce attack surface. |
| CMMI | Capability Maturity Model Integration | A process improvement framework defining maturity levels for software development and service delivery. |
| CN | Change Notice | A notification of a change to a product, standard, or configuration. |
| CNA | CVE Numbering Authority | An organization authorized by MITRE to assign CVE identifiers to vulnerabilities they discover. |
| CNAPP | Cloud-Native Application Protection Platform | An integrated platform combining CSPM, CWPP, and other capabilities for cloud-native protection. |
| CNCF | Cloud Native Computing Foundation | A vendor-neutral foundation hosting cloud-native projects including Kubernetes and Prometheus. |
| COFF | Common Object File Format | A format for executable and object code files on Windows; the predecessor of the PE format. |
| COLO | Co-Location | A data center facility where businesses rent space for their own servers and hardware. |
| COM | Component Object Model | A Microsoft platform-independent standard enabling software components to communicate. |
| CONOPS | Concept of Operations | A document describing how an organization uses a system to achieve operational objectives. |
| CORS | Cross-Origin Resource Sharing | A browser mechanism controlling how web pages request resources from a different origin. |
| CPE | Common Platform Enumeration | A standardized naming scheme for software applications, operating systems, and hardware platforms. |
| CPRS | Cross-Origin Resource Sharing | An alias/typo variant for CORS – see CORS. |
| CPSA | CREST Practitioner Security Analyst | An entry-level CREST certification for security analysts. |
| CRC | Code Ready Containers | OpenShift's local container development environment for running containers on a developer's machine. |
| CRI | Container Runtime Interface | A plugin interface allowing the Kubernetes kubelet to use different container runtimes. |
| CRIME | Compression Ratio Info-leak Made Easy | A 2012 TLS attack exploiting data compression to recover session tokens; mitigated by disabling TLS compression. |
| CRL | Certificate Revocation List | A list maintained by a CA of certificates revoked before their expiration date. |
| CRLF | Carriage Return Line Feed | A line-ending sequence (\r\n); CRLF injection can lead to HTTP response splitting and header injection. |
| CRQ | Cyber Risk Quantification | The process of expressing cybersecurity risk in financial terms to support business decision-making. |
| CRQC | Cryptographically Relevant Quantum Computer | A quantum computer powerful enough to break current asymmetric encryption like RSA and ECC. |
| CRT | CREST Registered Tester | A CREST entry-level penetration testing qualification for individuals. |
| CRUD | Create, Read, Update, Delete | The four basic persistent storage operations: Create, Read, Update, and Delete. |
| CSAF | Common Security Advisory Framework | A standard for machine-readable security advisories enabling automated vulnerability management. |
| CSD | Client-Side Desync | An HTTP request smuggling technique exploiting differences between client and server HTTP parsing. |
| CSF | Cybersecurity Framework | NIST's voluntary framework of standards and best practices for managing cybersecurity risk (NIST CSF). |
| CSIRT | Computer Security Incident Response Team | A dedicated team responsible for receiving, analyzing, and responding to cybersecurity incidents. |
| CSMA/CD | Carrier Sense Multiple Access/Collision Detection | A network access method used in Ethernet for detecting and resolving packet collisions on shared media. |
| CSP | Content Security Policy | An HTTP security header restricting which resources a browser can load, mitigating XSS attacks. |
| CSPM | Cloud Security Posture Management | Tools continuously monitoring cloud environments for misconfigurations and compliance violations. |
| CSPT | Client-Side Path Traversal | A vulnerability allowing attackers to manipulate file paths on the client side to access unintended resources. |
| CSRF | Cross-Site Request Forgery | An attack tricking an authenticated user into unknowingly submitting malicious requests to a web application. |
| CSRSS | Client Server Runtime Process | A core Windows process managing console windows; a target for process injection attacks. |
| CT | Certificate Transparency | A public log of all issued TLS certificates enabling detection of misissued or fraudulent certificates. |
| CTA | Cyberroam Transparent Authentication | A Cyberroam feature providing seamless user authentication without a dedicated login page. |
| CTAP | Client to Authenticator Protocol | A protocol enabling external hardware authenticators to communicate with platforms via FIDO2/WebAuthn. |
| CTEM | Continuous Threat Exposure Management | A continuous program for identifying, assessing, prioritizing, and remediating an organization's attack surface. |
| CTF | Capture The Flag | A cybersecurity competition where participants solve security challenges to find hidden flags. |
| CTI | Cyber Threat Intelligence | Analyzed, actionable information about threats and threat actors used to inform security defenses. |
| CU | Content Update | An update package delivering the latest fixes and improvements for a software product. |
| CVE | Common Vulnerabilities and Exposures | A public dictionary of known cybersecurity vulnerabilities, each assigned a unique identifier. |
| CVRF | Common Vulnerability Reporting Framework | An XML-based format for sharing security advisory information between organizations. |
| CVSS | Common Vulnerability Scoring System | A standardized framework rating the severity of software vulnerabilities on a 0–10 scale. |
| CWE | Common Weakness Enumeration | A community-developed categorization of common software and hardware security weaknesses. |
| CWP | Cloud Workload Protection | Security solutions protecting workloads running in cloud environments from threats and vulnerabilities. |
| D3FEND | Detection, Denial, and Disruption Framework Empowering Network Defense | A MITRE knowledge base of defensive cybersecurity techniques complementing the ATT&CK framework. |
| DAAS | Data, Assets, Applications and Services | The four primary targets for security protection: Data, Assets, Applications, and Services. |
| DAC | Discretionary Access Control | An access control model where the resource owner decides who can access their own resources. |
| DACL | Discretionary Access Control List | The portion of a Windows security descriptor specifying which users and groups can access an object. |
| DAD | Destruction, Alteration, Disclosure | The opposing triad to CIA: Destruction, Alteration, and Disclosure of information. |
| DAPP | Decentralized Applications | Blockchain-based applications running on a decentralized network rather than centralized servers. |
| DAST | Dynamic Application Security Testing | Security testing performed against a running application from outside to find exploitable vulnerabilities. |
| DCIM | Data Center Infrastructure Management | Software for monitoring and managing data center infrastructure including power and cooling. |
| DCOM | Distributed Component Object Model | A Microsoft protocol enabling software components to communicate across a network. |
| DDNS | Dynamic Domain Name System | A system automatically updating DNS records when a device's IP address changes. |
| DDoS | Distributed Denial of Service | An attack flooding a target with traffic from multiple sources to make it unavailable. |
| DEFI | Decentralized Finance | Financial services built on blockchain technology without traditional intermediaries. |
| DEG | Defender Exploit Guard | Windows Defender Exploit Guard – host intrusion prevention capabilities built into Windows 10+. |
| DEP | Data Execution Prevention | A security feature preventing code from executing in memory regions marked as non-executable. |
| DES | Data Encryption Standard | An outdated 56-bit symmetric cipher, now considered insecure and replaced by AES. |
| DFD | Data Flow Diagram | A diagram showing data flow through a system; used in threat modeling to identify attack surfaces. |
| DFIR | Digital Forensics Incident Response | The combined discipline of investigating incidents and collecting, preserving, and analyzing digital evidence. |
| DFR | Dynamic Function Resolution | A technique resolving function addresses at runtime to evade static analysis and detection. |
| DGA | Domain Generation Algorithm | A malware technique generating pseudo-random domain names for C2 communication to evade blocklists. |
| DH | Diffie-Hellman | A key exchange protocol enabling two parties to establish a shared secret over an insecure channel. |
| DHCP | Dynamic Host Configuration Protocol | A protocol automatically assigning IP addresses and network configuration to devices on a network. |
| DI | Dependency Injection | A software pattern where dependencies are provided to a component externally rather than created internally. |
| DIG | Domain Information Groper | A command-line DNS lookup utility for querying name servers and troubleshooting DNS issues. |
| DKIM | DomainKeys Identified Mail | An email authentication method using digital signatures attached to messages to verify the sending domain. |
| DLP | Data Loss Prevention | Policies and tools preventing sensitive data from being accidentally or maliciously exfiltrated. |
| DLR | Dynamic Language Runtime | A .NET runtime environment enabling dynamically typed languages to run on the .NET framework. |
| DMA | Direct Memory Access | A feature allowing hardware to access system memory independently of the CPU; vulnerable to DMA attacks. |
| DMARC | Domain-Based Message Authentication Reporting and Conformance | An email authentication protocol specifying how to handle messages that fail SPF and DKIM checks. |
| dMSA | Delegated Managed Service Account | A Windows managed service account that can be delegated to specific services. |
| DMZ | Demilitarized Zone | A network segment isolating an internal network from external networks, hosting public-facing services. |
| DNF | Dandified YUM | The next-generation package manager for RPM-based Linux distributions, replacing YUM. |
| DNS | Domain Name System | The internet's system for translating human-readable domain names into IP addresses. |
| DNSBL | Domain Name System-Based Blackhole List | A list of IP addresses known to send spam or host malicious content, used to block traffic. |
| DNSCAA | DNS Certification Authority Authorization | A DNS record type allowing domain owners to specify which CAs are permitted to issue TLS certificates for their domain. |
| DNSSEC | Domain Name System Security Extensions | DNS extensions adding cryptographic signatures to records to prevent spoofing and cache poisoning. |
| DOCSIS | Data Over Cable Service Interface Specification | A standard defining broadband data transmission over existing cable TV infrastructure. |
| DOH | DNS over HTTPS | A protocol encrypting DNS queries within HTTPS to prevent eavesdropping and manipulation. |
| DOM | Document Object Model | The programming interface representing an HTML or XML document as a tree; manipulated in DOM-based XSS. |
| DORA | Digital Operational Resilience Act | EU regulation requiring financial sector entities to demonstrate operational resilience against ICT disruptions. |
| DOT | DNS over TLS | A protocol encrypting DNS queries using TLS to provide privacy and prevent manipulation. |
| DPA | Data Processing Agreement | A contract defining how a data processor may handle personal data on behalf of a controller. |
| DPAPI | Data Protection Application Programming Interface | A Windows API providing transparent encryption and decryption of data tied to user credentials. |
| DPIA | Data Protection Impact Assessment | A process required by GDPR for analyzing how a project will affect personal data privacy. |
| DR | Disaster Recovery | The process and plans for restoring IT systems and data after a disruptive event such as a cyberattack or outage. |
| DRDoS | DNS Reflection Denial of Service | A DDoS amplification attack using open DNS resolvers to flood a victim with large DNS responses. |
| DREAD | Damage, Reproducibility, Exploitability, Affected Users, Discoverability | A vulnerability scoring model evaluating Damage, Reproducibility, Exploitability, Affected users, and Discoverability. |
| DRS | Directory Replication Service | The Windows service replicating Active Directory data between domain controllers. |
| DRSUAPI | Directory Replication Service Universal API | The Windows API used for Active Directory replication; abused in DCSync attacks to dump credential hashes. |
| DSA | Digital Signature Algorithm | A cryptographic algorithm for generating digital signatures ensuring authenticity and non-repudiation. |
| DSC | Desired State Configuration | A PowerShell configuration management feature for declaratively managing Windows server configurations. |
| DSCP | Differentiated Services Code Point | A field in the IP header used to classify and manage network traffic for QoS prioritization. |
| DSL | Domain Specific Language | A language designed for a specific domain such as SQL (databases) or YARA (malware detection). |
| DSP | Digital Signal Processor | A specialized microprocessor optimized for digital signal processing operations. |
| DSPM | Data Security Posture Management | Tools discovering, classifying, and securing sensitive data across cloud storage and databases. |
| DSS | Data Security Standard | Data Security Standard – most commonly PCI DSS for protecting payment card data. |
| DTD | Document Type Definition | A specification defining XML document structure; exploited in XXE attacks. |
| DTMF | Dual-Tone Multi-Frequency | The signaling system used by telephone keypads, where each key generates two simultaneous audio tones. |
| E2EE | End-to-End Encryption | Encryption ensuring only the communicating endpoints can read messages, preventing intermediary access. |
| EAL | Evaluation Assurance Level | A numerical grade in the Common Criteria framework describing the rigor of a security evaluation. |
| EAP | Extensible Authentication Protocol | A network authentication framework defining the message format for various authentication methods. |
| EAP-AKA | EAP Authentication and Key Agreement | An EAP method using the Authentication and Key Agreement protocol for 3G/4G mobile network authentication. |
| EAP-AKA' | EAP Authentication and Key Agreement Prime | An enhanced version of EAP-AKA providing additional security for LTE/5G network authentication. |
| EAP-EKE | EAP Encrypted Key Exchange | An EAP method using an Encrypted Key Exchange protocol for password-based mutual authentication. |
| EAP-FAST | EAP Flexible Authentication via Secure Tunneling | An EAP method using a Protected Access Credential to establish a TLS tunnel without certificates. |
| EAP-GTC | EAP Generic Token Card | An EAP method using a generic token card as the authentication mechanism. |
| EAP-IKEv2 | EAP Internet Key Exchange v2 | An EAP method using IKEv2 for mutual authentication. |
| EAP-NOOB | EAP Nimble Out-of-Band Authentication | An EAP method for IoT device bootstrapping using an out-of-band channel for initial authentication. |
| EAP-POTP | EAP Protected One-Time Password | An EAP method providing one-time password authentication with server authentication. |
| EAP-PSK | EAP Pre-Shared Key | An EAP method using a Pre-Shared Key for mutual authentication without certificates. |
| EAP-SIM | EAP Subscriber Identity Module | An EAP method using a SIM card for authentication in mobile networks. |
| EAP-TLS | EAP Transport Layer Security | The most secure EAP method, using mutual certificate-based authentication over TLS. |
| EAP-TTLS | EAP Tunneled Transport Layer Security | An EAP method creating a TLS tunnel and then authenticating using any inner method. |
| EAR | Execution After Redirect | A web vulnerability where code continues to execute after a redirect, bypassing authorization checks. |
| eBGP | External Border Gateway Protocol | BGP sessions between routers in different autonomous systems, used for inter-domain routing on the internet. |
| EBP | Extended Base Pointer | A 32-bit CPU register pointing to the base of the current stack frame; used in stack-based exploitation. |
| EBPF | Extended Berkeley Packet Filter | A Linux kernel technology enabling safe, sandboxed programs for networking, security, and observability. |
| EBS | Elastic Block Storage | AWS's persistent block storage service providing volumes for EC2 instances. |
| EC2 | Elastic Compute Cloud | AWS's virtual server service providing resizable compute capacity in the cloud. |
| ECC | Elliptic Curve Cryptography | Cryptographic approach using elliptic curve math to provide strong security with smaller key sizes. |
| ECDH | Elliptic Curve Diffie-Hellman | A key agreement protocol using elliptic curves allowing two parties to establish a shared secret. |
| ECDSA | Elliptic Curve Digital Signature Algorithm | A digital signature algorithm using elliptic curve cryptography for compact, strong signatures. |
| ECP | Encryption Control Protocol | A PPP subprotocol negotiating encryption algorithms for PPP connections. |
| eCPPT | eLearnSecurity Certified Professional Penetration Tester | eLearnSecurity's intermediate penetration testing certification with a fully practical exam. |
| ECS | Elastic Container Service | Amazon AWS's fully managed container orchestration service. |
| EDR | Endpoint Detection and Response | Security software providing continuous endpoint monitoring, threat detection, and automated response. |
| EDTR | Endpoint Detection and Threat Response | An alternative acronym for EDR – security software for continuous endpoint monitoring and threat response. |
| EEPROM | Electrically Erasable Programmable Read-Only Memory | Non-volatile memory that can be erased and reprogrammed electrically; used in firmware storage. |
| EFS | Elastic File System | AWS Elastic File System; also Windows Encrypting File System for file-level transparent encryption. |
| EIGRP | Enhanced Interior Gateway Routing Protocol | A Cisco proprietary advanced distance-vector routing protocol for IP networks. |
| EIP | Extended Instruction Pointer | The 32-bit instruction pointer register in x86 architecture tracking the next instruction to execute. |
| eJPT | eLearnSecurity Junior Penetration Tester | eLearnSecurity's entry-level penetration testing certification with a practical lab-based exam. |
| EKE | Encrypted Key Exchange | A password-based protocol for authenticated key exchange providing mutual authentication. |
| EKS | Elastic Kubernetes Service | Amazon AWS's managed Kubernetes service for running containerized applications. |
| ELB | Elastic Load Balancing | AWS's service for distributing incoming application traffic across multiple targets. |
| ELF | Executable and Linkable Format | The standard binary format for executables, object code, and shared libraries on Linux/Unix systems. |
| ELK | Elasticsearch, Logstash, Kibana | The Elasticsearch, Logstash, and Kibana stack for log aggregation, processing, and visualization. |
| EM | Exposure Management | A continuous process for discovering, assessing, and prioritizing an organization's exposures to reduce risk. |
| ENISA | European Union Agency for Cybersecurity | The EU agency providing guidance, recommendations, and analysis to improve cybersecurity across Europe. |
| EPA | Extended Protection for Authentication | A Windows security feature binding authentication credentials to the TLS channel to prevent relay attacks. |
| EPP | Endpoint Protection Platform | A suite of endpoint security technologies working together to prevent and detect threats on endpoints. |
| EPROM | Erasable Programmable Read-Only Memory | Non-volatile memory erasable by UV light; used in legacy firmware storage. |
| EPSS | Exploit Prediction Scoring System | A data-driven model scoring the probability that a CVE will be exploited in the wild within 30 days. |
| ESAE | Enhanced Security Administrative Environment | Microsoft's red forest model for privileged access; a hardened AD forest dedicated to managing privileged accounts. |
| ESI | Edge Side Includes | A markup language for assembling web content at the edge; ESI injection can lead to SSRF or XSS. |
| ESP | Encapsulating Security Payload | An IPsec protocol providing confidentiality, integrity, and authentication for IP packets. |
| ESS | Extended Session Security | An NTLM security feature adding a client challenge to prevent certain relay attacks. |
| ETL | Extract, Transform, Load | A data integration process extracting data from sources, transforming it, and loading it into a target system. |
| ETW | Event Tracing for Windows | A high-performance Windows tracing framework for logging system and application activity. |
| 2FA | Two-Factor Authentication | An authentication method requiring two distinct forms of identity verification to grant access. |
| FAANG | Facebook, Apple, Amazon, Netflix, Google | Acronym for the five major US technology companies; now sometimes extended to MAANG (with Microsoft). |
| FAIR | Factor Analysis of Information Risk | A quantitative risk analysis framework for measuring and managing information security risk in financial terms. |
| FAST | Flexible Authentication Secure Tunneling | A Cisco EAP method establishing a TLS tunnel using a Protected Access Credential (PAC). |
| FDA | Food and Drug Administration | The US agency regulating medical devices; publishes cybersecurity guidance for connected medical devices. |
| FDE | Full Disk Encryption | Encryption of an entire disk drive to protect all stored data from unauthorized physical access. |
| FIB | Forward Information Base | A routing table optimized for fast packet forwarding, derived from the RIB (Routing Information Base). |
| FIDO | Fast Identity Online | Open authentication standards using public key cryptography, forming the basis of passkeys. |
| FIDO2 | Fast Identity Online 2 | The second version of the FIDO standard combining WebAuthn and CTAP to enable passwordless authentication. |
| FIFO | First In, First Out | A data structure and scheduling method where the first item added is the first item processed. |
| FIM | File Integrity Monitoring | A security control monitoring and alerting on unauthorized changes to critical files and directories. |
| FinTS | Financial Transaction Services | A German online banking protocol providing a standardized interface for bank-customer communication. |
| FIPS | Federal Information Processing Standards | US government standards specifying approved cryptographic modules for federal systems. |
| FLoC | Federated Learning of Cohorts | A deprecated Google privacy-preserving advertising proposal replacing third-party cookies. |
| FOCI | Family of Client IDs | An OAuth concept grouping related client applications sharing permissions and data access. |
| FOR500 | SANS FOR500: Windows Forensic Analysis | A SANS course covering Windows digital forensics artifacts and investigation techniques. |
| FOR508 | SANS FOR508: Advanced Incident Response and Threat Hunting | A SANS course covering memory forensics, threat hunting, and enterprise-scale incident response. |
| FOR572 | SANS FOR572: Advanced Network Forensics | A SANS course covering network forensics including traffic analysis and log investigation. |
| FOR610 | SANS FOR610: Reverse-Engineering Malware | A SANS course on malware analysis using static and dynamic reverse engineering techniques. |
| FOSS | Free and Open Source Software | Software distributed with its source code, licensed for free use, modification, and distribution. |
| FPM | FastCGI Process Manager | A PHP process manager providing advanced features for high-traffic web sites. |
| FT | Fast Basic Service Set Transition | An IEEE 802.11r feature enabling faster roaming between Wi-Fi access points. |
| FTE | Full-Time Equivalent | A unit measuring employee workload; used in security workforce planning and budget discussions. |
| FTK | Forensic Toolkit | A digital forensics software suite by Exterro (formerly AccessData) used for disk and evidence analysis. |
| FTP | File Transfer Protocol | A legacy protocol for transferring files that transmits data in cleartext; replaced by SFTP or FTPS in secure environments. |
| FTTB | Fiber to the Building | A broadband architecture delivering fiber optic cable to a building's entry point, then copper to units. |
| FTTC/K | Fiber to the Curb / Kerb | A broadband architecture delivering fiber to a street cabinet, then copper to premises. |
| FTTD | Fiber to the Desktop | A broadband architecture delivering fiber optic cable directly to desktop computers. |
| FTTDP | Fiber to the Distribution Point | A broadband architecture delivering fiber to a distribution point near homes. |
| FTTE/Z | Fiber to the Enclosure / Zone | A broadband architecture delivering fiber to an enclosure or zone within a building. |
| FTTF | Fiber to the Frontage | A broadband architecture delivering fiber to the front of a property. |
| FTTH | Fiber to the Home | A broadband architecture delivering fiber optic cable directly to individual residences. |
| FTTLA | Fiber to the Last Amplifier | A hybrid broadband architecture delivering fiber to the last amplifier in a cable network. |
| FTTN | Fiber to the Node | A broadband architecture delivering fiber to a neighborhood node, then copper to premises. |
| FTTO | Fiber to the Office | A broadband architecture delivering fiber optic cable directly to office premises. |
| FTTP | Fiber to the Premises | A broadband architecture delivering fiber optic cable directly to any premises. |
| FTTX | Fiber to the X | A generic term for any broadband architecture delivering fiber optic cable to a specific endpoint. |
| FUD | Fully Undetectable | Describes malware or payloads designed to bypass all known security tool detections. |
| GCM | Galois Counter Mode | An authenticated encryption mode combining counter encryption with a GHASH tag for integrity. |
| GCP | Google Cloud Platform | Google's comprehensive suite of cloud computing services and infrastructure. |
| GDPR | General Data Protection Regulation | EU regulation governing the collection, processing, and protection of personal data of EU residents. |
| GenAI | Generative Artificial Intelligence | AI capable of generating new content (text, images, code) based on patterns learned during training. |
| gMSA | Group Managed Service Accounts | A Windows managed service account providing automatic password management across multiple servers. |
| GOT | Global Offset Table | A data structure in ELF binaries resolving dynamic library addresses at runtime; targeted in memory exploits. |
| GPG | GNU Privacy Guard | An open-source implementation of the OpenPGP standard for encryption and digital signatures. |
| GPO | Group Policy Object | A Windows feature enabling administrators to define and enforce configuration policies across a domain. |
| GPON | Gigabit-Capable Passive Optical Network | A fiber-optic access network technology providing high-speed broadband to homes and businesses. |
| GPP | Group Policy Preferences | Windows Group Policy Preferences – historically stored plaintext credentials in SYSVOL, a known security risk. |
| GRC | Governance, Risk Management and Compliance | The integrated approach managing governance, enterprise risk, and regulatory compliance. |
| GRE | Generic Routing Encapsulation | A tunneling protocol encapsulating various network-layer protocols within IP tunnels. |
| GRPC | Google Remote Procedure Calls | Google's high-performance RPC framework using HTTP/2 and Protocol Buffers for inter-service communication. |
| GSSAPI | Generic Security Services Application Program Interface | An API providing a common interface for security services, widely used with Kerberos authentication. |
| GTFOBINS | GTFOBins | A curated list of Unix binaries that can be exploited to bypass local security restrictions or escalate privileges. |
| gTLD | Generic Top-Level Domain | Top-level domains not associated with a specific country (e.g., .com, .org, .net, .security). |
| GUID | Globally Unique Identifier | A 128-bit globally unique identifier used in software and systems to uniquely identify objects. |
| HACE | High Assurance Cryptographic Equipment | Cryptographic equipment certified to protect highly classified government information. |
| HBCI | Home Banking Computer Interface | A German standard for online banking communication between banks and customers. |
| HFC | Hybrid Fiber-Coaxial | A broadband network combining fiber optic and coaxial cable, used by cable operators for internet access. |
| HID | Human Interface Device | A class of USB devices (keyboards, mice, gamepads) that interact with users; can be abused in USB attacks. |
| HIDS | Host-Based Intrusion Detection System | Security software monitoring a single host for suspicious activity, unauthorized changes, or policy violations. |
| HIPS | Host-Based Intrusion Prevention System | Security software on a host that monitors and blocks malicious activity in real time. |
| HITECH | Health Information Technology for Economic and Clinical Health Act | US legislation expanding HIPAA protections for electronic health records and breach notification requirements. |
| HMAC | Hash-Based Message Authentication Code | A MAC algorithm using a cryptographic hash function combined with a secret key to authenticate messages. |
| HMM | Hunting Maturity Model | A model defining maturity levels for organizational threat hunting programs. |
| HNDL | Harvest Now, Decrypt Later | A quantum threat strategy where adversaries collect encrypted data now to decrypt it with future quantum computers. |
| HOTP | HMAC-Based One-Time Password | A one-time password algorithm based on HMAC, generating a new password with each authentication event. |
| HPC | High Performance Computing | Systems designed for large-scale computational tasks; increasingly relevant to cryptography and AI security. |
| HQL | Hibernate Query Language | An ORM query language; HQL injection is an attack variant of SQL injection targeting Hibernate applications. |
| HR | Human Resources | The organizational department managing personnel; relevant to security in onboarding, offboarding, and insider threat programs. |
| HSDPA | High-Speed Downlink Packet Access | A 3.5G mobile data standard providing faster downlink speeds over UMTS networks. |
| HSM | Hardware Security Module | A physical device providing tamper-resistant generation, storage, and management of cryptographic keys. |
| HSRP | Hot Standby Router Protocol | A Cisco proprietary first-hop redundancy protocol; vulnerable to spoofing if not authenticated. |
| HSTS | HTTP Strict Transport Security | A web security policy forcing browsers to use only HTTPS, preventing protocol downgrade attacks. |
| HTA | HTML Application | An HTML file running as a desktop application with full system privileges; commonly abused by malware. |
| HTB | HackTheBox | A popular online cybersecurity training platform offering CTF-style labs and certifications. |
| HTML | Hypertext Markup Language | The standard markup language for creating web pages and applications. |
| HTTP | Hypertext Transfer Protocol | The foundation protocol for data communication on the web; transmits data in cleartext, replaced by HTTPS. |
| HTTPS | Hypertext Transfer Protocol Secure | HTTP secured with TLS encryption; the standard protocol for secure web communication. |
| I | Integrity | Integrity – one of the CIA Triad pillars; ensuring data has not been tampered with or altered. |
| IAM | Identity and Access Management | The discipline managing digital identities and controlling user access to systems and resources. |
| IAST | Interactive Application Security Testing | Security testing that instruments a running application to detect vulnerabilities in real time. |
| IAVM | Information Assurance Vulnerability Alert | A US DoD notification system alerting organizations about critical vulnerabilities requiring remediation. |
| iBGP | Internal Border Gateway Protocol | BGP sessions between routers within the same autonomous system for internal route distribution. |
| IBN | Intent-Based Networking | A networking approach using AI and automation to align network behavior with business intent. |
| ICMP | Internet Control Message Protocol | A network protocol for error reporting and diagnostics (ping, traceroute); used in some DoS attacks. |
| ICS | Industrial Control Systems | Electronic systems monitoring and controlling industrial processes like power generation and manufacturing. |
| IDA | IDA Pro | An industry-standard interactive disassembler and debugger widely used in reverse engineering and malware analysis. |
| IDN | International Domain Name | A domain name containing non-ASCII characters, enabling internationalized domain names. |
| IDOR | Insecure Direct Object Reference | A vulnerability allowing attackers to access unauthorized objects by manipulating input parameters. |
| IdP | Identity Provider | A system creating, storing, and managing digital identities and providing authentication assertions to relying parties. |
| IDS | Intrusion Detection System | A monitoring tool detecting malicious activity or policy violations on a network or host. |
| IDTR | Identity Threat Detection and Response | Security capabilities detecting and responding to attacks targeting identity infrastructure and credentials. |
| IEC | International Electrotechnical Commission | The international body developing and publishing standards for electrical and electronic technologies. |
| IFS | Internal Field Separator | A bash variable defining the delimiter used to split strings; misuse can lead to command injection. |
| IGMP | Internet Group Management Protocol | A protocol managing multicast group memberships on IP networks. |
| IGRP | Interior Gateway Routing Protocol | A deprecated Cisco distance-vector routing protocol replaced by EIGRP. |
| IKE | Internet Key Exchange | A protocol negotiating and managing IPsec security associations and cryptographic keys. |
| IMAP | Internet Message Access Protocol | An email protocol allowing clients to access and manage messages on a remote mail server. |
| IMDS | Instance Metadata Service | A cloud metadata endpoint accessible from within VMs; a common SSRF target for credential theft. |
| IMEI | International Mobile Equipment Identity | A unique 15-digit number identifying a mobile device; used in device tracking and blocking. |
| IMSI | International Mobile Subscriber Identity | A unique number identifying a mobile subscriber stored on a SIM card; targeted in IMSI-catcher attacks. |
| IOA | Indicator of Attack | Evidence suggesting an attack is actively in progress, based on behavioral patterns. |
| IOC | Indicator of Compromise | Artifacts indicating a system has been compromised (hashes, IPs, domains, registry keys). |
| IOCTL | Device Input and Output Controls | A system call interface allowing userspace programs to interact with device drivers; exploited in privilege escalation. |
| IOMMU | Input-Output Memory Management Unit | Hardware providing memory protection for DMA transfers; helps prevent DMA-based attacks. |
| IP | Internet Protocol | The primary protocol for addressing and routing packets across internet and local networks. |
| IPAM | IP Address Management | Administration of IP address space including DNS and DHCP management in a network. |
| IPC | Inter-Process Communication | Mechanisms allowing processes to communicate (pipes, sockets, shared memory); relevant to privilege escalation. |
| IPFIX | Internet Protocol Flow Information Export | A standard protocol for exporting network flow records from routers and switches for analysis. |
| IPMI | Intelligent Platform Management Interface | A hardware-level interface for remote server management; historically plagued by serious security vulnerabilities. |
| IPS | Intrusion Prevention System | A security tool monitoring network traffic and automatically blocking detected threats. |
| IPSEC | Internet Protocol Security | Uppercase variant of IPsec. See IPsec – a protocol suite providing authentication and encryption for IP communications. |
| IPsec | Internet Protocol Security | A protocol suite authenticating and encrypting IP packets for secure network communications. |
| IPv4 | Internet Protocol version 4 | The fourth version of IP using 32-bit addresses; still the dominant internet protocol despite exhaustion of addresses. |
| IPv6 | Internet Protocol version 6 | The sixth version of IP using 128-bit addresses; introduces new security considerations including SLAAC. |
| IR | Infrared | Electromagnetic radiation used in short-range wireless communication and remote controls. |
| IRAP | Infosec Registered Assessors Program | An Australian program allowing authorized assessors to evaluate systems and cloud services for government use. |
| IRDP | ICMP Router Discovery Protocol | A protocol allowing hosts to discover routers; vulnerable to ICMP-based default gateway spoofing attacks. |
| IRQL | Interrupt Request Level | A Windows kernel mechanism controlling which interrupts can preempt the current code; relevant to kernel exploitation. |
| IS-IS | Intermediate System to Intermediate System | A link-state routing protocol used in large service provider networks. |
| ISAC | Information Sharing and Analysis Center | Sector-specific organizations facilitating cybersecurity threat intelligence sharing between members. |
| ISACA | Information Systems Audit and Control Association | A professional association offering cybersecurity certifications including CISA, CISM, CRISC, and CGEIT. |
| ISAKMP | Internet Security Association and Key Management Protocol | A framework for establishing Security Associations and cryptographic keys, used in IKE. |
| ISC2 | International Information System Security Certification Consortium | A nonprofit organization offering the CISSP, CCSP, and other security certifications. |
| ISM | Information Security Manual | Australia's government cybersecurity framework providing controls for protecting sensitive information. |
| ISO | International Organization for Standardization | The international body publishing standards including ISO/IEC 27001 for information security management. |
| IT | Information Technology | The use of computers, storage, networking, and other physical devices to create, process, and store data. |
| ITDR | Identity Threat Detection and Response | A security capability focused on detecting, investigating, and responding to attacks targeting identity systems. |
| JAXB | Java Architecture for XML Binding | A Java API for serializing Java objects to XML and back; deserialization vulnerabilities can enable RCE. |
| JEA | Just Enough Administration | A PowerShell security feature limiting privileged access to only the specific commands needed for specific tasks. |
| JIT | Just In Time | A security model granting elevated access only when needed and for a limited, defined time period. |
| JS | JavaScript | A programming language widely used in web applications; key target for XSS, prototype pollution, and client-side attacks. |
| JSON | JavaScript Object Notation | A lightweight data interchange format based on JavaScript syntax, widely used in APIs and configuration. |
| JSP | Java Server Pages | A server-side Java technology for generating dynamic web content; susceptible to injection attacks. |
| JSR | Java Specification Request | The formal document describing proposed specifications and technologies for the Java platform. |
| JWE | JSON Web Encryption | A standard for representing encrypted content using JSON data structures. |
| JWKS | JSON Web Key Set | A JSON structure representing a set of public keys used to verify JWTs. |
| JWT | JSON Web Token | A compact, URL-safe token for securely transmitting claims between parties; used in authentication. |
| KASLR | Kernel Address Space Layout Randomization | An OS technique randomizing the kernel's memory layout to make kernel exploits significantly harder. |
| KDC | Key Distribution Center | The Kerberos component authenticating users and issuing tickets for accessing network services. |
| KICS | Keeping Infrastructure as Code Secure | An open-source IaC security scanner by Checkmarx detecting misconfigurations in Terraform, Kubernetes, and other IaC files. |
| KPP | Kernel Patch Protection | A Windows kernel security feature (PatchGuard) preventing unauthorized modification of kernel structures. |
| KQL | Kibana Query Language / Kusto Query Language | Query languages used in security platforms – KQL for Elastic/Kibana SIEM and Kusto for Microsoft Sentinel. |
| KWARGS | Keyword Arguments | Python function arguments passed by name; relevant in security when evaluating dynamic code execution. |
| LAN | Local Area Network | A network connecting computers within a limited area such as a home, office, or building. |
| LAPS | Local Administrator Password Solution | A Microsoft solution automatically managing unique local administrator passwords on domain machines. |
| LDAP | Lightweight Directory Access Protocol | A protocol for accessing and maintaining distributed directory information services like Active Directory. |
| LDAPS | LDAP over SSL/TLS | Secure LDAP – LDAP traffic encrypted with TLS to prevent credential interception. |
| LEAP | Lightweight Extensible Authentication Protocol | A deprecated Cisco EAP method considered insecure and no longer recommended. |
| LFI | Local File Inclusion | A web vulnerability allowing attackers to include files from the server's local filesystem in output. |
| LFO | Least Frequency of Occurrence | A cache eviction algorithm removing the least-frequently accessed items. |
| LIFO | Last In, First Out | A data structure where the most recently added item is removed first; used in stack implementations. |
| LINQ | Language-Integrated Query | .NET query syntax integrated into C# and VB.NET; LINQ injection can be a vector in .NET applications. |
| LKM | Loadable Kernel Module | A kernel module that can be loaded and unloaded at runtime; used by rootkits for kernel-level persistence. |
| LLC | Logical Link Control | The upper sublayer of the data link layer managing frame synchronization, flow control, and error checking. |
| LLM | Large Language Model | A large AI model trained on massive text datasets capable of generating, summarizing, and reasoning. |
| LLMNR | Link-Local Multicast Name Resolution | A Windows name resolution protocol exploited in poisoning attacks to capture NTLM credential hashes. |
| LOC | Logistic Operation Center | A facility managing logistics and operational coordination. |
| 3LOD | Three Lines of Defense | A governance model separating risk management into three layers: operations (owns the risk), risk/compliance functions (oversees it), and internal audit (independently validates). |
| LOI | Living-Off-Identity | An attack technique abusing legitimate identity providers and services to avoid detection. |
| LOLBAS | Living off the Land Binaries and Scripts | A project cataloging Windows binaries, scripts, and libraries that can be abused by attackers for defense evasion. |
| LORAWAN | Long Range Wide Area Network | A low-power wireless protocol for IoT devices over long distances; security relies on AES-128 encryption. |
| LOTL | Living off the Land | An attack approach using built-in system tools (PowerShell, WMI, certutil) to avoid introducing new malware. |
| LOTS | Living off Trusted Sites | An attack technique abusing legitimate, trusted cloud services and websites to host malware or exfiltrate data. |
| LPD | Line Printer Daemon | A network printing protocol; legacy protocol with known security weaknesses. |
| LQL | Lucene Query Language | The query syntax used in Apache Lucene and Elasticsearch; injection can lead to information disclosure. |
| LSA | Local Security Authority | The Windows subsystem managing security policies, authentication, and generating audit logs. |
| LSASS | Local Security Authority Subsystem Service | A critical Windows process handling authentication; targeted by attackers to dump credential hashes. |
| LXC | Linux Container | An OS-level virtualization method for running multiple isolated Linux systems on a single host. |
| LXD | Linux Daemon | A container manager built on LXC providing a REST API; privilege escalation via LXD is a known attack path. |
| MAC | Mandatory Access Control / Medium Access Control / Message Authentication Code | Mandatory Access Control – enforces access based on security labels. Also: Medium Access Control (hardware address). Also: Message Authentication Code (integrity verification). |
| MCP | Model Context Protocol | An open protocol standardizing how AI applications communicate with external data sources and tools. |
| MD | Message Digest | A cryptographic hash function output; MD5 is deprecated for security use due to collision vulnerabilities. |
| MD5 | Message Digest 5 | A widely used cryptographic hash function; considered broken for security use due to collision vulnerabilities. |
| MDLC | Malware Development Lifecycle | The process adversaries use to develop, test, and deploy malware; mirrors the software SDLC. |
| MDM | Mobile Device Management | Software managing, monitoring, and securing mobile devices deployed across an organization. |
| mDNS | Multicast DNS | A protocol resolving hostnames on small networks without a DNS server; exploitable for local network spoofing. |
| MDR | Managed Detection and Response | An outsourced security service providing expert threat detection, investigation, and response. |
| MEAN | MongoDB, Express.js, AngularJS, Node.js | A full-stack JavaScript framework; each component has distinct security considerations. |
| MFA | Multi-Factor Authentication | An authentication method requiring two or more verification factors to grant access. |
| MFD | Multifunction Device | Office equipment combining printing, scanning, and faxing; can store sensitive data and is a network attack vector. |
| MIB | Management Information Base | A database used by SNMP containing network device management information. |
| MIME | Multipurpose Internet Mail Extensions | A standard extending email to support non-ASCII text, attachments, and multimedia content. |
| MITM | Man-in-the-Middle | An attack where an adversary secretly intercepts and potentially alters communications between two parties. |
| ML | Machine Learning | A branch of AI enabling systems to learn from data and improve without explicit programming; used in threat detection and anomaly analysis. |
| ML-DSA | Module-Lattice-Based Digital Signature Algorithm | NIST-standardized post-quantum digital signature algorithm (formerly CRYSTALS-Dilithium). |
| ML-KEM | Module-Lattice-Based Key Encapsulation Mechanism | NIST-standardized post-quantum key encapsulation mechanism (formerly CRYSTALS-Kyber). |
| MOK | Machine Owner Key | A user-enrolled key in UEFI authorizing loading of custom kernel modules during Secure Boot. |
| MPLS | Multiprotocol Label Switching | A routing technique using short path labels rather than long network addresses to speed up forwarding. |
| MQTT | Message Queue Telemetry Transport Protocol | A lightweight publish-subscribe messaging protocol designed for constrained IoT and low-bandwidth environments. |
| MS-DRSR | Microsoft Directory Replication Service Remote Protocol | The protocol used for AD replication; exploited in DCSync attacks to extract credential hashes. |
| MS-NRPC | Microsoft NetLogon Remote Protocol | The Windows protocol for domain authentication; vulnerable to the ZeroLogon (CVE-2020-1472) attack. |
| MSHTA | Microsoft HTML Application Host | A Windows utility executing HTA files; commonly abused by malware for code execution and defense evasion. |
| MSS | Maximum Segment Size | The largest amount of data a TCP segment can carry, negotiated during connection establishment. |
| MSSP | Managed Security Service Provider | A company providing outsourced security monitoring, management, and response services. |
| MSTG | Mobile Security Testing Guide | The OWASP testing guide for mobile application security on iOS and Android platforms. |
| MTA | Mail Transfer Agent | Software transferring email between servers (e.g., Postfix, Sendmail, Exchange). |
| MTA-STS | Mail Transfer Agent Strict Transport Security | A mechanism specifying that email can only be delivered over TLS-authenticated SMTP connections. |
| MTLS | Mutual TLS | A TLS configuration requiring both client and server to authenticate with certificates. |
| MTOM | Message Transmission Optimization Mechanism | A SOAP protocol for efficiently transmitting binary attachments; relevant to XML security. |
| MTTA | Mean Time to Acknowledge | The average time between an alert firing and a security team acknowledging it. |
| MTTD | Mean Time to Detect | The average time from when a breach occurs to when it is identified – a key security performance metric. |
| MTTP | Mean Time to Production | The average time from code completion to deployment in production. |
| MTTR | Mean Time to Respond | The average time from detection of a security incident to full containment and recovery. |
| NAC | Network Access Control | Security solutions enforcing policy compliance on devices before and during network access. |
| NAK | Negative Acknowledgement | A signal indicating that data was received with errors or that a request was rejected. |
| NAS | Network-Attached Storage | A file-level storage server connected to a network; a target for ransomware and data exfiltration. |
| NAT | Network Address Translation | A method remapping IP addresses in packet headers, allowing multiple devices to share a single public IP address. |
| NBNS | NetBIOS Name Server | The NetBIOS component resolving computer names to IP addresses; exploited in poisoning attacks. |
| NBT | NetBIOS over TCP/IP | A protocol enabling legacy NetBIOS applications to communicate over TCP/IP networks; exploited in NBNS poisoning. |
| NBT-NS | NetBIOS Name Service | A Windows name resolution protocol exploited alongside LLMNR to steal credential hashes. |
| NCSC | National Cyber Security Centre | The UK government agency (part of GCHQ) providing cybersecurity advice and incident response. |
| NDA | Non-Disclosure Agreement | A legal contract restricting parties from disclosing confidential information; relevant to security engagements. |
| NDR | Network Detection and Response | Security solutions analyzing network traffic to detect threats bypassing endpoint and perimeter controls. |
| NERC | North American Electric Reliability Corporation | The organization setting reliability and cybersecurity standards (CIP) for the North American power grid. |
| NFC | Near-Field Communication | Short-range wireless technology enabling contactless data exchange between devices within a few centimeters. |
| NFS | Network File System | A distributed file system protocol allowing remote file access over a network. |
| NFV | Network Function Virtualization | The practice of virtualizing network services (firewalls, load balancers) to run as software rather than hardware. |
| NGAV | Next-Generation Antivirus | Antivirus software using AI, machine learning, and behavioral analysis instead of signatures. |
| NGE | Next Generation Encryption | Cisco's framework of cryptographic algorithms recommended for modern secure communications. |
| NGFW | Next-Generation Firewall | An advanced firewall with deep packet inspection, application awareness, and threat intelligence integration. |
| NHI | Non-Human Identity | Digital identities for non-person entities: service accounts, API keys, and machine identities. |
| NICE | National Initiative for Cybersecurity Education | A NIST-led framework defining cybersecurity workforce roles, knowledge areas, and competencies. |
| NIDS | Network-Based Intrusion Detection System | An IDS deployed at the network level monitoring traffic across multiple hosts simultaneously. |
| NIPS | Network-Based Intrusion Prevention System | An IPS deployed at the network level monitoring and blocking malicious traffic in real time. |
| NIS2 | Network and Information Security Directive 2 | An updated EU directive expanding cybersecurity requirements to more sectors and harmonizing incident reporting. |
| NIST | National Institute of Standards and Technology | The US agency publishing cybersecurity standards and frameworks (CSF, SP 800 series, PQC standards). |
| NLA | Network Level Authentication | A Windows authentication mechanism requiring authentication before establishing a full RDP session. |
| NMI | Non-Maskable Interrupt | A hardware interrupt that cannot be ignored by the processor; used in kernel debugging and some attacks. |
| NMS | Network Monitoring System | Software monitoring network devices and links for availability, performance, and security events. |
| NOC | Network Operations Center | A centralized facility monitoring and managing network infrastructure for availability and performance. |
| NONCE | Number Used Once | A value used only once in cryptographic communication, preventing replay attacks. |
| NoSQL | Not Only SQL | Non-relational databases (MongoDB, Redis, Cassandra); vulnerable to NoSQL injection attacks. |
| NoTW | Mark-of-the-Web | A Windows security feature tagging files downloaded from the internet to trigger security warnings. |
| NPE | Non-Person Entity | A digital identity for non-human actors such as devices, applications, and services in a Zero Trust context. |
| NSX | VMware NSX | VMware's full-stack network and security virtualization platform for software-defined data centers. |
| NTDS.DIT | New Technology Directory Services Directory Information Tree | The Active Directory database file storing all AD data including password hashes; a primary attack target. |
| NTFS | New Technology File System | The primary Windows file system supporting permissions, encryption (EFS), and alternate data streams. |
| NTLM | New Technology LAN Manager | A legacy Windows authentication protocol vulnerable to pass-the-hash, relay, and brute-force attacks. |
| NTP | Network Time Protocol | A protocol synchronizing clocks across networked devices; NTP amplification attacks are a common DDoS vector. |
| NVD | National Vulnerability Database | NIST's repository of CVE vulnerability data enriched with CVSS scores and remediation guidance. |
| NX | Non-Executable Stack | A hardware/OS protection marking memory regions as non-executable to prevent shellcode execution. |
| OCSF | Open Cybersecurity Schema Framework | An open standard for normalizing security event data across different tools and vendors. |
| OCSP | Online Certificate Status Protocol | A protocol for checking the revocation status of a digital certificate in real time. |
| OGNL | Object-Graph Navigation Language | An expression language used in Java frameworks; OGNL injection enabled critical RCE in Apache Struts. |
| OID | Object Identifier | A globally unique identifier used to name objects in ASN.1, SNMP, X.509, and other standards. |
| OIDC | OpenID Connect | An identity authentication layer on top of OAuth 2.0 for federated login and user profile retrieval. |
| ONVIF | Open Network Video Interface Forum | A standard for IP-based security cameras and video systems; relevant to IoT/physical security. |
| OOB | Out-of-Band | Communication or management using a channel separate from the primary data path for secure administration. |
| OPA | Open Policy Agent | An open-source policy engine enabling fine-grained, context-aware authorization in cloud environments. |
| OPCUA | OPC Unified Architecture | A platform-independent ICS communication standard for industrial automation and SCADA systems. |
| OPSEC | Operations Security | The process identifying and controlling information that adversaries could use to plan attacks. |
| OPtH | Overpass-the-Hash | An attack using an NTLM hash to request a Kerberos TGT, enabling lateral movement with Kerberos. |
| OSCP | Offensive Security Certified Professional | Offensive Security's hands-on penetration testing certification with a demanding 24-hour practical exam. |
| OSI | Open Systems Interconnection | A seven-layer conceptual model for network communication; each layer has distinct security considerations and attack surfaces. |
| OSINT | Open Source Intelligence | Intelligence gathered exclusively from publicly available sources. |
| OSPF | Open Shortest Path First | A link-state routing protocol using Dijkstra's algorithm to calculate optimal paths within a network. |
| OSSEC | Open Source HIDS Security | An open-source HIDS providing log analysis, file integrity monitoring, and real-time alerting. |
| OSSEM | Open Source Security Event Metadata | A community project defining standard security event metadata for improving detection quality. |
| OSSTMM | Open Source Security Testing Methodology Manual | A peer-reviewed manual providing a scientific methodology for security testing. |
| OSWE | Offensive Security Web Expert | OffSec's advanced web application security certification requiring a 48-hour practical exam. |
| OT | Operational Technology | Technology used to monitor and control physical industrial processes, equipment, and infrastructure. |
| OTA | Over-the-Air | Wireless delivery of software updates to devices; OTA security ensures updates are authenticated and encrypted. |
| OTP | One-Time Password | A password valid for only one authentication session or transaction, preventing replay attacks. |
| OVAL | Open Vulnerability and Assessment Language | An XML-based language for representing system configuration information, vulnerability data, and compliance checks. |
| OWASP | Open Web Application Security Project | A nonprofit producing free web application security resources including the OWASP Top 10. |
| OXID | Object Exporter Identifier | A DCOM identifier for objects; OXIDs are queried during network reconnaissance to discover interfaces. |
| PA | Policy Administrator | A Zero Trust component handling session information and communicating decisions to the Policy Enforcement Point. |
| PAC | Privileged Attribute Certificate | In Kerberos, a data structure embedded in tickets containing authorization and group membership data. |
| PAKE | Password Authenticated Key Exchange | A cryptographic protocol allowing two parties to establish a shared key using only a shared password. |
| PAM | Privileged Access Management | Security solutions controlling, monitoring, and auditing privileged account access to critical resources. |
| PAP | Password Authentication Protocol | A simple, insecure PPP authentication protocol transmitting passwords in cleartext. |
| PASTA | Process for Attack Simulation and Threat Analysis | A risk-centric, seven-stage threat modeling methodology aligning technical risks with business impact. |
| PAW | Privileged Access Workstation | A dedicated, hardened workstation used exclusively for performing administrative tasks to reduce attack surface. |
| PBKDF1 | Password-Based Key Derivation Function 1 | An older key derivation function; superseded by PBKDF2 with stronger security guarantees. |
| PBKDF2 | Password-Based Key Derivation Function 2 | A key derivation function applying HMAC with a salt and many iterations to slow password cracking. |
| PCI | Payment Card Industry | Payment Card Industry – the standards body responsible for PCI DSS for protecting cardholder data. |
| PDF | Portable Document Format | A file format for documents; PDFs can contain malicious JavaScript, embedded files, and exploit code. |
| PDO | PHP Data Objects | A PHP database abstraction layer; using prepared statements with PDO prevents SQL injection. |
| PDP | Policy Decision Point | In Zero Trust, the policy engine component making authorization decisions based on rules and context. |
| PEAK | Prepare, Execute, Act, Knowledge | A structured incident response or red team methodology framework. |
| PEAP | Protected Extensible Authentication Protocol | An EAP method creating a secure TLS tunnel and then authenticating using an inner protocol. |
| PEAP-MSCHAPv2 | Protected EAP with MS-CHAPv2 | A widely deployed Wi-Fi authentication method; vulnerable to credential theft if certificate validation is disabled. |
| PEB | Process Environment Block | A Windows data structure containing process information; targeted in process injection and evasion techniques. |
| PEM | Privacy Enhanced Mail | A base64-encoded format for storing and sharing cryptographic keys, certificates, and other data. |
| PEP | Policy Enforcement Point | In Zero Trust, the component that enforces access decisions made by the Policy Decision Point. |
| PFS | Perfect Forward Secrecy | A property ensuring that session keys cannot be compromised even if long-term private keys are later exposed. |
| PFX | Personal Information Exchange | A binary format (PKCS#12) for storing a private key, certificate, and chain in a single encrypted file. |
| PGP | Pretty Good Privacy | An encryption program providing cryptographic privacy and authentication for email and file encryption. |
| PI | Process Instrumentation | Sensors and measurement devices used in industrial processes; relevant to OT/SCADA security. |
| PIE | Position Independent Executable | An executable compiled to run at any memory address, enabling ASLR to fully randomize its location. |
| PII | Personally Identifiable Information | Any data that can identify a specific individual (name, SSN, email); protected under GDPR and similar regulations. |
| PIM | Privileged Identity Management | An Azure/Entra ID feature providing just-in-time, time-bound privileged access with approval workflows. |
| PIP | Policy Information Point | An access control component providing telemetry and context data that the PDP needs for authorization decisions. |
| PKCS | Public-Key Cryptography Standards | A group of standards (PKCS#1 through PKCS#15) published by RSA Security defining cryptographic practices. |
| PKI | Public Key Infrastructure | The framework of policies, procedures, hardware, and software managing digital certificates and keys. |
| PMK | Pairwise Master Key | The master key in WPA/WPA2 derived from authentication, used to generate per-session encryption keys. |
| PNAC | Port-Based Network Access Control | An IEEE 802.1X framework controlling network access at the physical port level based on authentication. |
| POC | Proof of Concept | A demonstration showing that a vulnerability is exploitable; used in bug reports and security research. |
| POODLE | Padding Oracle On Downgraded Legacy Encryption | A 2014 attack exploiting SSLv3 CBC padding; led to the deprecation of SSL 3.0. |
| POP | Post Office Protocol | An email retrieval protocol; POP3 downloads email from a server, typically removing it from the server. |
| POSIX | Portable Operating System Interface | A family of IEEE standards defining APIs for Unix-like OS compatibility. |
| PP | Protection Profile | A Common Criteria document defining security requirements for a category of products. |
| PPL | Protected Process Light | A Windows security feature restricting which processes can interact with security-critical processes. |
| PQC | Post-Quantum Cryptography | Cryptographic algorithms designed to resist attacks from both classical and quantum computers. |
| PR | Privileges Required | Privileges Required – a CVSS metric indicating the access level an attacker needs to exploit a vulnerability. |
| PRF | Pseudorandom Function | A function producing output indistinguishable from random; used in key derivation and cryptographic protocols. |
| ProgID | Programmatic Identifier | A Windows COM registry key mapping a human-readable name to a CLSID; abused in COM hijacking attacks. |
| PSA | Public Service Announcement | An informational message; in security contexts often used for community vulnerability advisories. |
| PSAD | Port Scan Attack Detector | A Linux tool monitoring firewall logs to detect and optionally block port scan activity. |
| PSIA | Physical Security Interoperability Alliance | An industry consortium developing standards for physical security system interoperability. |
| PSTN | Public Switched Telephone Network | The traditional circuit-switched telephone network; relevant to vishing attacks. |
| PTA | Permission-to-Attack | Formal written authorization from an organization allowing a security team to conduct offensive testing. |
| PTK | Pairwise Transient Key | A per-session encryption key derived from the PMK in WPA/WPA2, used to encrypt unicast traffic. |
| QCR | Quantum Computer Resistant | Describes cryptographic algorithms designed to withstand attacks from quantum computers. |
| QEMU | Quick Emulator | An open-source machine emulator and virtualizer; relevant to VM escape vulnerabilities. |
| QKD | Quantum Key Distribution | A method using quantum mechanics to securely distribute encryption keys, theoretically immune to eavesdropping. |
| QUIC | Quick UDP Internet Connections | A UDP-based transport protocol providing TLS 1.3 security and multiplexing; the foundation of HTTP/3. |
| R&D | Research and Development | Systematic work to increase knowledge and use it to develop new products or services. |
| RACI | Responsible, Accountable, Consulted and Informed | A responsibility assignment matrix clarifying Responsible, Accountable, Consulted, and Informed roles. |
| RADIUS | Remote Authentication Dial-In User Service | A networking protocol providing centralized authentication, authorization, and accounting for network access. |
| RAG | Retrieval-Augmented Generation | An AI architecture augmenting LLMs with real-time retrieval from external knowledge bases. |
| RASP | Runtime Application Self-Protection | Security integrated into an application detecting and blocking attacks in real time during execution. |
| RAX | Register A Extended | The 64-bit general-purpose register in x86-64; commonly used for function return values and syscall numbers. |
| RBAC | Role-Based Access Control | An access control model assigning permissions based on predefined roles aligned to job functions. |
| RBCD | Resource-Based Constrained Delegation | A Kerberos delegation variant allowing resource owners to specify trusted services for delegation. |
| RBI | Remote Browser Isolation | A security technology executing web browsing in an isolated environment to protect endpoints from web-based threats. |
| RBL | Real-Time Blackhole List | A list of IP addresses known to send spam used by mail servers to block unwanted email. |
| RBP | Register Base Pointer | A 64-bit CPU register pointing to the base of the current stack frame. |
| RBVM | Risk-Based Vulnerability Management | A vulnerability management approach prioritizing remediation based on actual exploitability and business risk. |
| RBX | Register B Extended | A 64-bit general-purpose x86-64 register used for data manipulation. |
| RC4 | Rivest Cipher 4 | A deprecated stream cipher; considered insecure and prohibited in TLS 1.3. |
| RCE | Remote Code Execution | A vulnerability class allowing attackers to execute arbitrary code on a remote target system. |
| RCX | Register C Extended | A 64-bit x86-64 register used for loop counters and as the first argument in the Windows calling convention. |
| RDI | Register Destination Index | A 64-bit x86-64 register used for destination operands in string operations. |
| RDNS | Reverse DNS | A DNS lookup returning the hostname associated with an IP address; used in spam filtering and logging. |
| RDP | Remote Desktop Protocol | Microsoft's protocol for graphical remote access to Windows systems; frequently targeted by attackers. |
| RDS | Relational Database Service | AWS's managed relational database service supporting MySQL, PostgreSQL, Oracle, and others. |
| RDX | Register D Extended | A 64-bit x86-64 register used for I/O operations and as the third function argument. |
| REL | Releasable To | A handling caveat in classified document markings indicating which parties may receive the information. |
| RELRO | Relocation Read-Only | A binary hardening technique making certain memory regions read-only after program startup to prevent exploitation. |
| REP | Reputation | In CVSS 4.0, a metric assessing the impact on an organization's reputation as part of environmental scoring. |
| REPL | Read-Evaluate-Print Loop | An interactive programming environment; some REPL interfaces can lead to code injection vulnerabilities. |
| REST | Representational State Transfer | An architectural style for APIs using HTTP methods; the basis for most modern web APIs. |
| RF | Radio Frequency | Electromagnetic frequencies used in wireless communication; relevant to wireless security assessments. |
| RFC | Request for Comments | A formal internet standards document published by the IETF describing protocols and best practices. |
| RFI | Remote File Inclusion | A web vulnerability allowing attackers to include remote files through a vulnerable server script. |
| RID | Relative Identifier | The final component of a Windows SID uniquely identifying a user or group within a domain. |
| RIP | Routing Information Protocol | A distance-vector routing protocol using hop count as metric; RIPv1 has no authentication. |
| RMF | Risk Management Framework | NIST's structured process for integrating security and privacy risk management into system development. |
| RNDC | Remote Name Daemon Control | A utility for controlling BIND DNS server; misconfigured RNDC can allow unauthorized DNS manipulation. |
| ROA | Route Origin Authorization | A cryptographically signed RPKI record authorizing an AS to originate specific IP prefixes. |
| ROE | Rules of Engagement | Documented rules and constraints governing the scope and conduct of a security engagement. |
| ROP | Return-Oriented Programming | An exploitation technique chaining existing code snippets (gadgets) to execute logic without code injection. |
| ROSI | Return on Security Investment | A metric expressing the financial value of security investments relative to their cost. |
| RPC | Remote Procedure Call | A protocol enabling a program to execute procedures on a remote system as if they were local. |
| RPKI | Resource Public Key Infrastructure | A cryptographic framework securing BGP routing through origin validation with digital certificates. |
| RRDNS | Round-Robin DNS | A load distribution technique returning multiple IP addresses for a single hostname in rotation. |
| RSA | Rivest-Shamir-Adleman | A widely used asymmetric algorithm for encryption and digital signatures, based on prime factorization. |
| RSI | Register Source Index | A 64-bit x86-64 register used for source operands in string operations. |
| RSP | Register Stack Pointer | A 64-bit CPU register pointing to the top of the current stack; critical in stack-based exploitation. |
| RTCO | Red Team Certified Operator | A professional certification for red team operators. |
| RTP | Real-Time Transport Protocol | A network protocol for delivering audio and video over IP; subject to eavesdropping without SRTP. |
| RTSP | Real-Time Streaming Protocol | A network control protocol for streaming media servers; relevant to IP camera security. |
| RX | Receiving | The receive channel or data path in a communication system. |
| S | Scope | Scope – a CVSS metric indicating whether a vulnerability's impact extends beyond the vulnerable component. |
| S-SDLC | Secure Software Development Lifecycle | A software development lifecycle with security practices integrated throughout every phase. |
| S/MIME | Secure/Multipurpose Internet Mail Extension | A standard for encrypting and digitally signing email messages for end-to-end security. |
| S3 | Simple Storage Service | Amazon's object storage service for data, backups, and static website hosting. |
| S4U | Service for User | A Kerberos extension allowing services to obtain tickets on behalf of users; abused in constrained delegation attacks. |
| SA | Security Association | A set of shared security parameters (algorithms, keys) between two IPsec endpoints. |
| SACL | System Access Control List | The Windows security descriptor component defining which accesses generate audit log entries. |
| SAIF | Secure AI Framework | Google's framework providing structured guidance for developing and operating AI systems securely. |
| SAM | Security Accounts Manager | The Windows database storing hashed passwords for local user accounts; a common attack target. |
| SAML | Security Assertion Markup Language | An XML standard for federated identity enabling SSO by exchanging authentication assertions. |
| SAMM | Software Assurance Maturity Model | An OWASP framework for measuring and improving software security practices across development teams. |
| SAN | Storage Area Network | A high-speed network providing block-level storage access to servers; misconfigurations can expose sensitive data. |
| SAS | Secure Attention Sequence | The Ctrl+Alt+Del key combination in Windows that triggers a trusted path preventing credential capture. |
| SASE | Secure Access Service Edge | A network architecture merging WAN capabilities with cloud-delivered security functions into one service. |
| SASL | Simple Authentication and Security Layer | A framework for authentication in protocols like SMTP and LDAP; supports multiple authentication mechanisms. |
| SAST | Static Application Security Testing | Security testing analyzing source code without execution to identify vulnerabilities before deployment. |
| SBOM | Software Bill of Materials | A formal inventory of all software components, libraries, and dependencies in a product. |
| SCA | Software Composition Analysis | Testing that identifies known vulnerabilities in open-source and third-party components. |
| SCADA | Supervisory Control and Data Acquisition | A control system architecture for monitoring and controlling industrial processes across large areas. |
| SCD | Source Code Disclosure | A vulnerability exposing application source code to unauthorized users, revealing logic and credentials. |
| SCEC | Security Construction and Equipment Committee | An Australian government body providing advice on physical security construction and equipment. |
| SCEP | Simple Certificate Enrollment Protocol | A protocol enabling devices to enroll for certificates from a CA automatically. |
| SCIM | System for Cross-domain Identity Management | An open standard protocol automating user provisioning and deprovisioning across identity systems. |
| SCM | Service Control Manager | The Windows component managing system services; a target for service-based privilege escalation. |
| SCP | Service Control Policy | AWS Organizations policy restricting what actions are permitted in member accounts. |
| SCTP | Stream Control Transmission Protocol | A transport protocol combining features of TCP and UDP; used in telecom and some security tools. |
| SCYTHE | SCYTHE Platform | A threat emulation platform for purple team exercises and adversary simulation. |
| SD | Security Descriptor | A Windows data structure defining the security attributes of a securable object. |
| SD-WAN | Software-Defined Wide Area Network | A networking approach using software to manage WAN connectivity and services across locations. |
| SDDL | Security Descriptor Definition Language | A text format representing Windows security descriptors used in GPO and registry configurations. |
| SDL | Security Development Lifecycle | Microsoft's security development process integrating security practices throughout the software lifecycle. |
| SDLC | Software Development Life Cycle | The structured process for planning, developing, testing, deploying, and maintaining software. |
| SDN | Software-Defined Network | A networking approach using software to control network configuration and behavior dynamically. |
| SDO | Statement of Applicability | An ISO 27001 document declaring which controls from Annex A are applicable and why. |
| SDP | Software-Defined Perimeter | A security model hiding infrastructure from unauthorized users and granting access only after verification. |
| SE | Search Engine Optimization | Techniques for improving website visibility in search results; relevant to phishing via typosquatting. |
| SEC | Securities and Exchange Commission | The US financial regulator; its 2023 cybersecurity rules require public companies to disclose material incidents. |
| SEV | Secure Encrypted Virtualization | AMD's hardware technology encrypting virtual machine memory to protect VMs from hypervisor-level attacks. |
| SFTP | SSH File Transfer Protocol | A secure file transfer protocol using SSH encryption; the secure replacement for FTP. |
| SHA-2 | Secure Hashing Algorithm 2 | A family of cryptographic hash functions (SHA-224, SHA-256, SHA-384, SHA-512) considered secure for current use. |
| SHA-256 | Secure Hash Algorithm 256-bit | A widely used cryptographic hash function from the SHA-2 family producing a 256-bit digest; used in TLS, code signing, and blockchain. |
| SHA-3 | Secure Hashing Algorithm 3 | The latest NIST-standardized hash function based on the Keccak algorithm; structurally different from SHA-2. |
| SHIM | First Stage Bootloader | A small program loading the main bootloader; used in Secure Boot bypass and bootkit attacks. |
| SID | Security Identifier | A unique value identifying a Windows user, group, or computer account; used in access control decisions. |
| SIEM | Security Information and Event Management | A platform aggregating and correlating security events from across an organization for threat detection. |
| SIKE | Supersingular Isogeny Key Encapsulation | A post-quantum cryptographic algorithm that was broken in 2022 by classical computing attacks. |
| SIM | Subscriber Identity Module | A smart card in mobile devices storing subscriber identity and authentication keys. |
| SIP | Session Initiation Protocol | A signaling protocol for VoIP communications; subject to eavesdropping, toll fraud, and DoS attacks. |
| SKEL | Skeleton | A template directory structure used as the base for new user home directories in Linux. |
| SLAAC | Stateless Address Auto-Configuration | An IPv6 mechanism for automatic address configuration without a DHCP server. |
| SMB | Server Message Block | A Windows network file sharing protocol; exploited in attacks like EternalBlue/WannaCry. |
| SMIME | Secure/Multipurpose Internet Mail Extension | A standard for encrypting and digitally signing email messages. See also S/MIME. |
| sMSA | Standalone Managed Service Account | A Windows managed service account for single-server use with automatic password management. |
| SMSS | Session Manager Subsystem | The first user-mode process in Windows responsible for creating user sessions. |
| SMTP | Simple Mail Transfer Protocol | The standard protocol for sending email between mail servers across the internet. |
| SNI | Server Name Indication | A TLS extension specifying the hostname during handshake, enabling virtual hosting of multiple TLS certificates. |
| SNMP | Simple Network Management Protocol | A protocol for collecting and managing information about network devices. |
| SNS | Amazon Simple Notification Service | AWS's managed pub/sub messaging service; misconfigurations can lead to unauthorized notifications. |
| SOA | Statement of Applicability | In ISO 27001, a document declaring applicable security controls. Also: Start of Authority DNS record. |
| SOAP | Simple Object Access Protocol | An XML-based messaging protocol for web services; subject to XML injection and XXE attacks. |
| SOAR | Security Orchestration, Automation, and Response | Technology automating security incident response using playbooks and tool integrations. |
| SOC | Security Operations Center | A centralized team using people, processes, and technology to continuously monitor and respond to threats. |
| SoC | System on Chip | An integrated circuit containing all components of a computer; relevant to hardware security and IoT. |
| SOE | Standard Operating Environment | A standardized configuration of hardware and software deployed across an organization for consistency and security. |
| SOP | Same-Origin Policy | A browser security mechanism preventing scripts from one origin from accessing resources of another. |
| SOQL | Salesforce Object Query Language | A query language for Salesforce; SOQL injection is an attack targeting Salesforce applications. |
| SOX | Sarbanes-Oxley Act | US legislation requiring public companies to implement internal controls and report on financial data security. |
| SP | Special Publication | NIST's publication series (e.g., SP 800-53, SP 800-171) defining cybersecurity standards and guidelines. |
| SPA | Sender Protocol Address | The IP address of the sender in an ARP packet; used in ARP spoofing attacks. |
| SPAN | Switched Port Analyzer | A network switch feature mirroring traffic from one port to another for monitoring and packet capture. |
| SPF | Sender Policy Framework | An email authentication method allowing domain owners to specify authorized mail servers. |
| SPI | Security Parameter Index | A value in IPsec packets identifying the Security Association for that packet. |
| SPN | Service Principal Name | A unique Kerberos identifier for a service instance in Active Directory; targeted in Kerberoasting. |
| SPX | Secure PDF Exchange | A format for distributing digitally signed and encrypted PDF documents. |
| SQL | Structured Query Language | A language for managing relational databases; SQL injection exploits insufficient input sanitization. |
| SQLI | SQL Injection | An attack exploiting insufficient input sanitization to manipulate database queries. |
| SRI | Subresource Integrity | A browser security feature verifying that fetched resources have not been tampered with. |
| SRS | Software Requirements Specification | A document describing what a software system should do; security requirements belong here. |
| SRTP | Secure Real-Time Transport Protocol | An extension of RTP providing encryption, authentication, and integrity for audio/video streams over IP. |
| SSAE | Statements on Standards for Attestation Engagements | The AICPA standard governing service organization control (SOC) reports. |
| SSAE18 | Statement on Standards for Attestation Engagements No. 18 | The standard governing SOC 1, SOC 2, and SOC 3 reports on service organization controls. |
| SSDLC | Secure Software Development Life Cycle | Variant of S-SDLC. See S-SDLC – an SDLC with security practices embedded throughout every phase of development. |
| SSDT | Secondary System Descriptor Table | An x86 data structure; patching the SSDT is a rootkit technique to hook system calls. |
| SSE | Server-Side Encryption | Encryption of data performed by the server before storing it at rest. |
| SSG | Static Site Generation | A technique generating static HTML at build time; XSS is still possible through template injection. |
| SSH | Secure Shell | A cryptographic protocol providing secure remote access and command execution; the secure replacement for Telnet. |
| SSI | Server-Side Includes | Web server directives embedded in HTML; SSI injection can lead to information disclosure or RCE. |
| SSID | Service Set Identifier | The name of a Wi-Fi network broadcast by an access point; evil twin attacks spoof legitimate SSIDs. |
| SSIS | SQL Server Integration Services | A Microsoft platform for data integration and workflow applications; relevant to SQL Server security. |
| SSL | Secure Sockets Layer | Secure Sockets Layer – the deprecated predecessor to TLS; vulnerable to POODLE and BEAST attacks. |
| SSN | Syscall Service Numbers | Numbers identifying system calls in Windows; manipulated in syscall hooking and evasion techniques. |
| SSO | Single Sign-On | Authentication allowing users to authenticate once and access multiple applications without re-entering credentials. |
| SSOT | Single Source of Truth | A practice ensuring all data originates from one authoritative source; relevant to identity management. |
| SSP | Security Service Provider | A Windows DLL implementing authentication functionality; malicious SSPs can capture credentials. |
| SSPM | SaaS Security Posture Management | Tools monitoring and improving security configurations of SaaS applications. |
| SSPR | Self-Service Password Reset | A feature allowing users to reset their own passwords without helpdesk assistance; requires secure implementation. |
| SSR | Server-Side Rendering | Generating HTML on the server for each request; SSRF and template injection are relevant risks. |
| SSRF | Server-Side Request Forgery | A vulnerability allowing attackers to make the server perform requests to internal or external resources. |
| SSSD | System Security Services Daemon | A Linux daemon providing access to identity and authentication resources including LDAP and Kerberos. |
| SSTF | Scroll to Text Fragment | A browser feature linking directly to text on a page; can be used for side-channel information leakage. |
| SSTI | Server-Side Template Injection | A vulnerability where user input embedded in a server-side template enables server-side code execution. |
| STAS | Sophos Transparent Authentication Suite | A Sophos tool enabling transparent user authentication for network devices. |
| STEM | Systematic, Threat, Evaluation, Methodology | A structured approach to security threat evaluation. |
| STIG | Security Technical Implementation Guide | Hardening guidelines published by DISA for DoD systems; widely used as security baselines. |
| STIX | Structured Threat Information Expression | A structured language for expressing cyber threat intelligence in a standardized, machine-readable format. |
| STRIDE | Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege | A threat modeling framework for six threat categories: Spoofing, Tampering, Repudiation, Information Disclosure, DoS, Elevation of Privilege. |
| STS | Security Token Service | A service issuing security tokens (SAML assertions, OAuth tokens) for authentication. |
| SWIFT | Society for Worldwide Interbank Financial Telecommunication | The global financial messaging network; SWIFT CSP mandates security controls for connected institutions. |
| SxS | Side-by-Side | A Windows mechanism for storing multiple versions of assemblies; abused in DLL hijacking attacks. |
| TA | Trust Algorithm | The process used by a Zero Trust policy engine to make the ultimate access grant or deny decision. |
| TAN | Transaction Authentication Number | A one-time code used to authorize a specific bank transaction. |
| TAP | Network TAP | A passive network monitoring device copying all traffic without affecting the network; used for forensics. |
| TAXII | Trusted Automated Exchange of Intelligence Information | A protocol for transporting STIX threat intelligence over HTTPS between trusted parties. |
| TCP | Transmission Control Protocol | A connection-oriented transport protocol providing reliable, ordered packet delivery; foundational to internet communications. |
| TCSEC | Trusted Computer System Evaluation Criteria | The 'Orange Book' – the original DoD standard for computer security evaluation. |
| TDIR | Threat Detection, Investigation, and Response | A security operations approach integrating detection, investigation, and response capabilities. |
| TDX | Intel Trust Domain Extensions | Intel's hardware technology for confidential computing, creating isolated virtual machine environments. |
| TE | Transfer-Encoding | An HTTP header specifying how the message body is encoded; abused in HTTP request smuggling attacks. |
| TEAP | Tunnel Extensible Authentication Protocol | An IETF standard EAP method providing a TLS tunnel for inner authentication; successor to PEAP. |
| TEE | Trusted Execution Environment | A secure, isolated processor area ensuring sensitive code and data are protected from the normal OS. |
| TELNET | Teletype Network | A legacy protocol for remote terminal access transmitting data in cleartext; replaced by SSH. |
| TGS | Ticket Granting Service | The Kerberos service issuing session tickets after a client presents a valid TGT. |
| TGT | Ticket Granting Ticket | A Kerberos credential obtained after initial authentication, used to request service tickets. |
| THA | Target Hardware Address | The MAC address field in an ARP packet identifying the target device; used in ARP spoofing. |
| TI | Threat Intelligence | Analyzed information about threats, adversaries, and TTPs used to inform security decisions. |
| TIBER-EU | Threat Intelligence-Based Ethical Red-Teaming | A European framework for threat intelligence-based ethical red team testing of financial entities. |
| TIP | Threat Intelligence Platform | A platform aggregating, correlating, and distributing threat intelligence from multiple sources. |
| TLD | Top-Level Domain | The last segment of a domain name (.com, .org, .uk); relevant to phishing via lookalike domains. |
| TLP | Traffic Light Protocol | A sharing framework using color codes (CLEAR, GREEN, AMBER, RED) to indicate permitted distribution of intelligence. |
| TLPT | Threat-Led Penetration Testing | Threat-Led Penetration Testing – structured, intelligence-driven red team exercises mandated by DORA. |
| TLS | Transport Layer Security | The cryptographic protocol securing communications over a network; the successor to SSL. |
| TLV | Type-Length-Value | An encoding scheme for data fields; used in network protocols and certificate extensions. |
| TOCTOU | Time Of Check To Time Of Use | A race condition vulnerability where a resource's state changes between a security check and its use. |
| TOS | Terms of Service | Legal agreements governing the use of services; relevant to bug bounty scope and authorized testing. |
| TOTP | Time-Based One-Time Password | A one-time password generated from the current time and a shared secret, expiring after 30–60 seconds. |
| TPM | Trusted Platform Module | A hardware chip providing tamper-resistant storage for cryptographic keys and system integrity measurements. |
| TPRM | Third-Party Risk Management | The process of identifying, assessing, and managing risks posed by vendors, suppliers, and partners. |
| TPS | Testing Procedure Specification | A document defining specific test procedures used to validate that security controls function as intended. |
| TRITON | TRITON/TRISIS Malware | A sophisticated ICS malware targeting Schneider Electric safety instrumented systems in industrial facilities. |
| TSIG | Transaction Signatures | A DNS security mechanism using shared HMAC secrets to authenticate zone transfers and dynamic DNS updates. |
| TTP | Tactics, Techniques and Procedures | Tactics (goals), Techniques (methods), and Procedures (specific steps) describing how threat actors operate. |
| TX | Transmitting | The transmit channel or data path in a communication system. |
| UAC | User Account Control | A Windows security feature prompting for elevated permissions; frequently targeted for bypass by malware. |
| UAF | Use-After-Free | A memory corruption vulnerability where freed memory is still accessible, enabling code execution or crashes. |
| UEBA | User and Entity Behavior Analytics | Security analytics using ML to establish behavioral baselines and detect anomalous user and device activity. |
| UEFI | Unified Extensible Firmware Interface | The modern firmware interface replacing BIOS; a target for sophisticated firmware-level and bootkit attacks. |
| UI | User Interface | User Interface; also a CVSS metric indicating whether user interaction is required to exploit a vulnerability. |
| UIPI | User Interface Privilege Isolation | A Windows security feature preventing low-privilege processes from sending messages to higher-privilege windows. |
| UPN | User Principal Name | A Windows username format (user@domain) used for logging into Active Directory domains. |
| URI | Uniform Resource Identifier | A string identifying a resource, broader than a URL (which specifies both location and access protocol). |
| URL | Uniform Resource Locator | The address of a web resource specifying its location and the protocol used to retrieve it. |
| USART | Universal Synchronous/Asynchronous Receiver-Transmitter | A hardware communication protocol used in embedded systems and IoT devices. |
| USB | Universal Serial Bus | A standard interface for connecting peripherals; USB devices can be used in BadUSB and HID attacks. |
| UUID | Universally Unique Identifier | A 128-bit identifier for generating universally unique values without central coordination. |
| VACM | View-Based Access Control Model | An SNMP security model defining which users can access which management information. |
| VBA | Visual Basic for Applications | A Microsoft programming language for automating Office applications; commonly used in macro-based malware. |
| VDP | Vulnerability Disclosure Program | A program allowing security researchers to report vulnerabilities without facing legal repercussions. |
| VECTR | VECTR Platform | A purple team management tool tracking ATT&CK-based adversary simulation exercises and detection coverage. |
| VEX | Vulnerability Exploitability eXchange | A format communicating whether vulnerabilities listed in an SBOM are actually exploitable in a product. |
| VICI | Versatile IKE Configuration Interface | A management interface for strongSwan VPN; access control is critical to prevent VPN misconfiguration. |
| VLAN | Virtual Local Area Network | A logical network segment isolating traffic within a physical network; VLAN hopping bypasses this isolation. |
| VOC | Video Operations Center | A facility monitoring and managing video surveillance infrastructure. |
| VoLTE | Voice over Long-Term Evolution | A 4G LTE standard for transmitting voice calls; subject to eavesdropping without proper encryption. |
| VPC | Virtual Private Cloud | An isolated private cloud network dedicated to a single customer within a public cloud provider. |
| VPN | Virtual Private Network | A technology creating an encrypted tunnel over a public network for secure remote access. |
| VSS | Volume Shadow Copy | A Windows service creating volume snapshots; commonly deleted by ransomware to prevent data recovery. |
| WADCOMS | WADComs | A curated list of offensive tools and their use cases for Windows/Active Directory environments. |
| WAF | Web Application Firewall | A security solution filtering and monitoring HTTP traffic to protect web applications from attacks. |
| WAN | Wide Area Network | A telecommunications network spanning large geographic areas, including the public internet. |
| WAP | Web Application Protection | A general term for solutions protecting web applications from attacks. |
| WASM | WebAssembly | A binary instruction format for web browsers enabling near-native performance; introduces new attack surfaces. |
| WAT | WebAssembly Text Format | The human-readable text representation of WebAssembly binary code. |
| WCD | Web Cache Deception | An attack tricking a cache into storing sensitive authenticated content as publicly accessible. |
| WDAC | Windows Defender Application Control | A Windows security feature allowing only trusted, signed code to run on a system. |
| WDM | Wavelength-Division Multiplexing | A fiber optic technology transmitting multiple signals simultaneously; relevant to physical layer security. |
| WEP | Wired Equivalent Privacy | An outdated Wi-Fi security protocol with known vulnerabilities; replaced by WPA2 and WPA3. |
| WHOIS | WHOIS Protocol | A query protocol for retrieving registration information about domain names and IP addresses; used in OSINT. |
| WinRM | Windows Remote Management | A Windows remote management service implementing WS-Management; frequently abused for lateral movement. |
| WinRS | Windows Remote Shell | A command-line tool using WinRM to execute commands on remote Windows systems. |
| WLAN | Wireless Local Area Network | A wireless network using Wi-Fi (IEEE 802.11) to connect devices within a local area. |
| WMI | Windows Management Instrumentation | A Windows management framework providing system access; abused by malware and attackers for lateral movement. |
| WMIC | Windows Management Instrumentation Command-Line | A command-line interface for WMI; commonly used by attackers for reconnaissance and lateral movement. |
| WOFF | Web Open Font Format | A compressed web font format; malicious fonts have been used in font parsing vulnerabilities. |
| WORM | Write Once, Read Many | A storage strategy allowing data to be written once and read many times, preventing modification. |
| WPA | Wi-Fi Protected Access | The original WPA protocol; superseded by WPA2 and WPA3 due to TKIP weaknesses. |
| WPA2 | Wi-Fi Protected Access 2 | The Wi-Fi security standard using AES-CCMP; vulnerable to KRACK, PMKID, and offline brute-force attacks. |
| WPA3 | Wi-Fi Protected Access 3 | The latest Wi-Fi security standard with SAE handshake and stronger encryption than WPA2. |
| WPAD | Web Proxy Autodiscovery Protocol | A protocol for auto-distributing proxy configurations; exploitable for credential interception. |
| WPS | Wi-Fi Protected Setup | A network security standard for easy wireless connection; vulnerable to brute-force PIN attacks. |
| WSGI | Web Server Gateway Interface | A Python standard for web server and web application communication. |
| WSH | Windows Script Host | A Windows runtime for executing scripts (VBScript, JScript); commonly abused by malware. |
| WSTG | Web Security Testing Guide | The OWASP comprehensive guide for testing web application security. |
| XAI | Explainable Artificial Intelligence | Methods enabling humans to understand, trust, and interpret decisions made by AI and ML models. |
| XDP | Express Data Path | A Linux kernel feature for high-performance packet processing; used in DDoS mitigation. |
| XDR | Extended Detection and Response | A security platform integrating telemetry from endpoints, network, cloud, and identity for unified detection. |
| XHR | XML HTTP Request | A browser API for making asynchronous HTTP requests from JavaScript; relevant to CORS misconfigurations and XSS. |
| XML | Extensible Markup Language | A markup language for encoding structured data; XXE attacks, XSLT injection, and SOAP vulnerabilities all target XML parsers. |
| XOP | XML-Binary Optimized Packaging | A mechanism for efficiently bundling binary data with SOAP messages. |
| XOR | Exclusive OR | A bitwise logical operation fundamental to many encryption algorithms and malware obfuscation. |
| XSLT | Extensible Stylesheet Language Transformations | A language for transforming XML documents; XSLT injection can lead to information disclosure or RCE. |
| XSS | Cross-Site Scripting | A vulnerability allowing attackers to inject malicious client-side scripts into pages viewed by other users. |
| XST | Cross-Site Tracing | An attack using HTTP TRACE method to steal cookies, mitigated by disabling TRACE on web servers. |
| XXE | XML External Entity | A vulnerability in XML processing allowing file reads, SSRF, or denial of service via external entity injection. |
| YAML | YAML Ain't Markup Language | A human-readable data serialization language used for configuration files. |
| YARA | YARA Rules | A pattern-matching tool used to identify and classify malware based on textual or binary patterns. |
| YUM | Yellowdog Updater Modified | A package manager for RPM-based Linux distributions; replaced by DNF in newer systems. |
| ZAP | Zed Attack Proxy | OWASP's open-source web application security scanner for finding vulnerabilities during testing. |
| ZKP | Zero-Knowledge Proof | A cryptographic method proving knowledge of information without revealing the information itself. |
| ZT | Zero Trust | A security model requiring strict identity verification for every user and device, regardless of network location. |
| ZTA | Zero Trust Architecture | A security architecture eliminating implicit trust and requiring continuous verification of every user and device. |
| ZTN | Zero Trust Network | A network architecture implementing Zero Trust principles, eliminating implicit trust based on network location. |
| ZTNA | Zero Trust Network Access | A technology granting secure application access based on identity and context, replacing traditional VPN. |

---

## Contributing

**[`^        back to top        ^`](#overview)**

Contributions are welcome! If you'd like to add abbreviations, improve definitions, or fix errors, please follow these steps:

1. **Fork** the repository
2. **Create a branch** for your changes (`git checkout -b add/new-terms`)
3. **Add your terms** – abbreviations go in the table above (sorted alphabetically)
4. **Keep it consistent** – use the existing format: `| ABBR | Full Name | Clear one-sentence definition |`
5. **Submit a Pull Request** with a clear description of what you added or changed

### Guidelines

**[`^        back to top        ^`](#overview)**

- Definitions should be clear and concise – aim for 1-2 sentences
- Abbreviations require three columns: Abbreviation, Full Name, Definition
- Terms should be relevant to cybersecurity, networking, or adjacent technical fields
- Avoid vendor marketing language – focus on technical accuracy
- If updating an existing entry, only submit if you are genuinely improving it