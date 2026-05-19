# 🔎 Google Dorking (Google Hacking)

## 🎯 Objective

To understand Google Dorking techniques and how search engines can be used for Open Source Intelligence (OSINT) and security assessments.

---

# 🧠 What is Google Dorking?

Google Dorking (also called Google Hacking) is the use of advanced Google search operators to discover sensitive information exposed on the internet.

It is widely used in:
- Penetration Testing
- Bug Bounty Hunting
- OSINT Investigations
- Security Research

---

# ⚠️ Important Ethical Note

Google Dorking must only be used:
- For educational purposes
- On authorized targets
- In legal environments

Unauthorized access or exploitation is illegal.

---

# 🌐 Why Google Dorking is Powerful

Search engines index huge amounts of public data, including:
- Login portals
- PDF documents
- Backup files
- Exposed credentials
- Misconfigured servers

Attackers often use Google before launching attacks.

---

# 🔍 Basic Google Search Operators

| Operator | Purpose |
|----------|---------|
| site: | Search within a domain |
| filetype: | Search for file types |
| intitle: | Search page titles |
| inurl: | Search URLs |
| cache: | View cached pages |
| ext: | Search file extensions |

---

# 🧪 Basic Google Dork Examples

---

## 🔹 Search Within a Website

```bash
site:example.com

Shows indexed pages from a domain.

🔹 Find PDF Files
site:example.com filetype:pdf
🔹 Find Login Pages
inurl:login
🔹 Find Admin Panels
intitle:"admin login"
🔹 Find Open Directories
intitle:"index of"
🔥 Advanced Google Dorking
🔹 Find Exposed Configuration Files
ext:env OR ext:ini OR ext:conf
🔹 Search for Password Files
filetype:txt password
🔹 Search for Database Dumps
filetype:sql
🔹 Find Cameras / IoT Devices
inurl:view/view.shtml
🌐 Google Dorking for OSINT

Google Dorks can reveal:

Employee names
Internal documents
Emails
Technologies used
Public infrastructure
🔍 Useful Search Combinations
🔹 Search Specific Domain + File Type
site:example.com filetype:xls
🔹 Search Specific Technology
inurl:php?id=
🔹 Search Exposed Backup Files
ext:bak OR ext:old OR ext:backup
🛠️ Real-World Applications

Google Dorking is used in:

Bug bounty hunting
Reconnaissance
Digital investigations
Security audits
🔐 Defensive Perspective

Organizations should:

Avoid exposing sensitive files
Configure robots.txt properly
Restrict indexing of sensitive pages
🧠 Common Risks Discovered
Risk	Example
Exposed documents	PDFs, spreadsheets
Login portals	Admin pages
Backup files	.bak files
Sensitive configs	.env files
🧪 Safe Practice Suggestions

Practice only on:

Your own lab
Test environments
Authorized platforms
🛡️ Security Best Practices
Remove sensitive files from public access
Use authentication
Monitor indexed content
Configure web servers securely
🧠 What I Learned
Search engines can expose sensitive information
Google Dorking is a powerful OSINT technique
Reconnaissance often begins with search engines