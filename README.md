# oscp-guide
OSCP Writeup


Hi Guys ❤️ 
In this repository I have put some useful information and tips about the OSCP certificate. I hope you like the article. Let's begin. 


├── OffSec OSCP Writeup 
│   ├── OSCP Content
│   │   ├── 1 - Penetration Testint With Kali : General Information
|   |   ├── 2 - Getting Comfortable With Kali Linux 
│   │   ├── 3 - Command Line Fun
│   │   ├── 4 - Practical Tools
│   │   ├── 5 - Bash Scripting 
│   │   ├── 6 - Passive Information Gathering
|   |   ├── 7 - Active Information Gathering
|   |   ├── 8 - Vulnerability Scanning
|   |   ├── 9 - Web Applications Attacks
|   |   ├── 10 - Into To Buffer OverFlows
|   |   ├── 11 - Windows Buffer OverFlows
|   |   ├── 12 - Linux Buffer OverFlows
|   |   ├── 13 - Client Side Attacks 
|   |   ├── 14 - Locating Public Exploits
|   |   ├── 15 - Fixing Exploits
|   |   ├── 16 - File Transfer
|   |   ├── 17 - Antivirus Evasion
|   |   ├── 18 - Privilege Escalation
|   |   ├── 19 - Password Attacks
|   |   ├── 20 - Port Redirection And Tunneling
|   |   ├── 21 - Ative Directory Attacks
|   |   ├── 22 - The Metasploit Framework
|   |   ├── 23 - PowerShell Empire
|   |   ├── 24 - Assembling The Pieces : Penetration Testing BreakDown
|   |   └── 25 - Trying Harder : The Labs
|   |   
│   ├── PWK Curriculum
│   │   ├── Linux and Bash 
│   │   │   ├── Linux Journey
│   │   │   ├── Bash for Beginners
│   │   │   ├── OverTheWire Bandit
|   |   |   └── Explainshell
│   │   ├── Basic tools
│   │   |    ├── Netcat
│   │   |    ├── Wireshark
│   │   |    └── TCPdump
|   |   ├── Passive Recon
|   |   |  ├─ Google dorks 
|   |   |  ├─ Whois
|   |   |  ├─ Netcraft
|   |   |  └─ Recon-ng
|   |   ├── Active Recon
|   |   |   ├─ Understand what DNS is, how it works, how to perform forward and reverse lookup, what zone transfers are and how to perform them. 
|   |   |   ├─ Nmap: One of the most used tools(if not the most).The Best start by reading the man pages, understand different scanning techniques and other capabilities it has (scripts, OS detection, Service detection,)
|   |   |   └─ Services enumeration: SMTP, SNMP, SMB, and a lot others. Don’t just enumerate them, understand what they’re used for and how they work
|   |   ├── Buffer Overflow
|   |   ├── Using public exploits 
|   |   |   └─ Occasionally, you’ll need to use a public exploit, maybe even modify the shellcode or other parts. Just go to Exploit-db and pick one of the older more reliable exploits (FTP ones for example). The vulnerable version is usually present with the exploit code.
|   |   ├── File Transfer 
|   |   |   └─ Not every machine has netcat installed, you’ll need to find a way around it to upload exploits or other tools you need
|   |   ├── Privilege Escalation
|   |   |   ├─ never ending topic, there are a lot of techniques, ranging from having an admin password to kernel exploits. Great way to practice this is by using Vulnhub VMs for practice.
|   |   |   ├─ Windows:Elevating privileges by exploiting weak folder permissions
|   |   |   |   └─ http://www.greyhathacker.net/?p=738
|   |   |   ├─ Windows: Privilege Escalation Fundamentals
|   |   |   |   └─ http://www.fuzzysecurity.com/tutorials/16.html
|   |   |   ├─ Windows: Windows-Exploit-Suggester: 
|   |   |   |   └─ https://github.com/GDSSecurity/Windows-Exploit-
|   |   |   ├─ Windows: Privilege Escalation Commands:
|   |   |   |   └─ http://pwnwiki.io/#!privesc/windows/index.md
|   |   |   └─ Linux: Basic Linux Privilege Escalation:
|   |   |      └─ https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/
|   |   ├── Client Side Attacks
|   |   |    └─ See This : https://www.offensive-security.com/metasploit-unleashed/client-side-attacks/
|   |   ├── Web Application Attacks
|   |   |    └─ Another lengthy subject, understand what XSS is, SQL injection, LFI, RFI, directory traversal, how to use a proxy like Burp Suite. Solve as much as you can from OverTheWire: Natas. It has great examples on Code Injection, Session hijacking and other web vulnerabilities.
|   |   ├── Password Attacks
|   |   |    └─ Understand the basics of password attacks, difference between online and offline attacks. How to use Hydra, JTR, Medusa, what rainbow tables are, the list goes on. Excellent post on this topic here.
|   |   ├── Port redirection/tunneling
|   |   |    └─ Not all machines are directly accessible, some are dual homed, connected to an internal network. You’ll use such techniques a lot in non-public networks.
|   |   |        └─ 
│   └── Cybersecurity Fundamentals
│       ├── CIA Triad
│       ├── Risk Management
│       ├── Threat Models
│       └── Attack Vectors
├── Threat Intelligence
│   ├── OSINT
│   │   ├── Tools (Maltego, Recon-ng)
│   │   └── Data Sources (Shodan, Censys)
│   ├── Threat Hunting
│   │   ├── Hypothesis-Driven Hunting
│   │   ├── TTPs
│   │   └── Use Cases Development
│   └── IOCs
│       ├── IP Addresses
│       ├── Hash Values
│       ├── Domains
│       └── File Names
├── Security Operations
│   ├── Monitoring and Logging
│   │   ├── SIEM
│   │   │   ├── Tools (Splunk, ELK Stack, QRadar)
│   │   │   └── Log Parsing and Correlation
│   │   └── Log Analysis
│   │       ├── Log Sources (Windows Event Logs, Syslog)
│   │       └── Log Aggregation and Storage
│   ├── Incident Response
│   │   ├── IR Plan Development
│   │   ├── Incident Handling Procedures
│   │   └── Digital Forensics
│   │       ├── Memory Analysis
│   │       └── Disk Forensics
│   ├── EDR
│   │   ├── Tools (CrowdStrike, Carbon Black)
│   │   └── Endpoint Visibility and Control
│   └── NSM
│       ├── Tools (Zeek, Suricata)
│       └── Traffic Analysis
├── Vulnerability Management
│   ├── Vulnerability Assessment
│   │   ├── Scanning Tools (Nessus, OpenVAS)
│   │   └── Assessment Methodologies
│   ├── Patch Management
│   │   ├── Patch Deployment Strategies
│   │   └── Patch Testing and Validation
│   └── Configuration Management
│       ├── Secure Configuration Guides
│       └── Configuration Monitoring
├── Identity and Access Management
│   ├── Authentication Methods
│   │   ├── MFA
│   │   └── SSO
│   ├── Authorization
│   │   ├── RBAC
│   │   └── ABAC
│   └── Identity Governance
│       ├── User Lifecycle Management
│       └── Access Reviews and Recertification
├── Secure Architecture
│   ├── Network Segmentation
│   │   ├── VLANs
│   │   └── Microsegmentation
│   ├── Zero Trust Architecture
│   │   ├── Principles and Implementation
│   │   └── Identity-Centric Security
│   └── Encryption
│       ├── Data at Rest
│       │   ├── Disk Encryption
│       │   └── Database Encryption
│       └── Data in Transit
│           ├── TLS/SSL
│           └── VPNs
├── Awareness and Training
│   ├── Security Awareness Programs
│   │   ├── Regular Training Sessions
│   │   └── Security Newsletters
│   ├── Phishing Simulations
│   │   ├── Phishing Campaigns
│   │   └── Analysis of Results
│   └── User Training
│       ├── Role-Based Training
│       └── Just-in-Time Training
├── Compliance and Governance
│   ├── Regulatory Requirements
│   │   ├── GDPR
│   │   ├── HIPAA
│   │   └── PCI-DSS
│   └── Policy Development
│       ├── Security Policies
│       ├── Incident Response Policies
│       └── Data Protection Policies
├── Advanced Defense Techniques
│   ├── Deception Technologies
│   │   ├── Honeypots
│   │   └── Honeytokens

