# 🕵️ Open Source Intelligence (OSINT)

## 🎯 Objective

To understand Open Source Intelligence (OSINT), reconnaissance methodologies, intelligence gathering techniques, and the role of publicly available information in cybersecurity operations.

---

# 🧠 What is OSINT?

Open Source Intelligence (OSINT) is the process of collecting, analyzing, and interpreting publicly available information from various sources.

OSINT is widely used in:
- Ethical Hacking
- Penetration Testing
- Threat Intelligence
- Digital Forensics
- Incident Response
- Cyber Investigations

---

# 🌐 Sources of OSINT

OSINT data can come from multiple public sources:

| Source Type | Examples |
|-------------|----------|
| Search Engines | Google, Bing |
| Social Media | LinkedIn, Twitter, Facebook |
| Domain Information | WHOIS |
| DNS Data | DNSDumpster |
| Public Records | Government databases |
| Breach Databases | HaveIBeenPwned |
| IoT Search Engines | Shodan |
| GitHub Repositories | Exposed credentials |
| Metadata | Documents, images |

---

# ⚔️ Types of Reconnaissance

## 🔹 Passive Reconnaissance

Information gathering without directly interacting with the target.

### Examples:
- Google searches
- WHOIS lookup
- Social media analysis

### Advantages:
- Hard to detect
- Safe and stealthy

---

## 🔹 Active Reconnaissance

Direct interaction with the target system.

### Examples:
- Port scanning
- DNS brute forcing
- Banner grabbing

### Risks:
- Can trigger alerts
- Detectable by IDS/IPS

---

# 🔍 Importance of OSINT in Cybersecurity

OSINT helps attackers and defenders understand:
- Attack surface
- Public exposure
- Employee information
- Technologies used
- Potential vulnerabilities

---

# 🛠️ Common OSINT Tools

| Tool | Purpose |
|------|---------|
| theHarvester | Gather emails/subdomains |
| Maltego | Relationship mapping |
| Recon-ng | Recon framework |
| Shodan | Search exposed devices |
| SpiderFoot | Automated OSINT |
| Amass | Subdomain enumeration |
| WHOIS | Domain ownership |

---

# 🌐 Search Engine Intelligence

Search engines reveal:
- Sensitive documents
- Login pages
- Exposed directories
- Internal information

---

# 🔥 Google Dorking

Advanced search operators used to discover sensitive information.

### Example:
```bash
site:example.com filetype:pdf
Purpose:
Discover exposed files
Find admin portals
Identify vulnerabilities
📧 Email Intelligence Gathering

Information that can be collected:

Employee emails
Breached accounts
Password leaks
Tools:
theHarvester
Hunter.io
HaveIBeenPwned
🌍 Domain & WHOIS Information

WHOIS records can reveal:

Owner information
Registrar
Contact emails
DNS servers
Example Command:
whois example.com
🌐 DNS Enumeration

DNS records reveal:

Subdomains
Mail servers
Internal infrastructure
Common Record Types:
Record	Purpose
A	Maps domain to IP
MX	Mail servers
TXT	Verification data
NS	Name servers
🔎 Subdomain Enumeration

Finding hidden subdomains:

admin.example.com
dev.example.com
api.example.com
Tools:
Amass
Subfinder
Assetfinder
🛰️ Shodan Intelligence

Shodan searches internet-connected devices.

Can Discover:
Cameras
Routers
Servers
Open ports
Example:
apache country:"US"
📱 Social Media Intelligence

Information attackers gather:

Employee names
Job roles
Technologies used
Internal projects

Platforms:

LinkedIn
Twitter
Facebook
🧬 Metadata Analysis

Metadata may expose:

Usernames
GPS locations
Software versions
Tools:
ExifTool
FOCA
🌑 Deep Web & Dark Web

OSINT may involve:

Threat monitoring
Data breach monitoring
Underground forums
Access:
Tor Browser

⚠️ Only for legal and educational purposes.

🔐 Ethical & Legal Considerations

OSINT must:

Respect privacy
Avoid illegal access
Follow authorization rules

Unauthorized access or misuse is illegal.

🧪 Practical OSINT Workflow
Example Investigation
Step 1 — Identify Target
example.com
Step 2 — WHOIS Lookup
whois example.com
Step 3 — DNS Enumeration
nslookup example.com
Step 4 — Subdomain Discovery
amass enum -d example.com
Step 5 — Search for Exposed Services
Shodan search
🧠 Real-World Applications

OSINT is used in:

Bug bounty hunting
Red teaming
Threat intelligence
Corporate investigations
Digital forensics
🧠 What I Learned
OSINT is the foundation of reconnaissance
Public data can reveal security weaknesses
Ethical information gathering is critical