# 🔌 Ports and Protocols

## 🎯 Objective
To understand network ports, protocols, and their role in communication and cybersecurity.

---

## 🧠 What is a Port?

A port is a logical endpoint used by a system to communicate over a network.

- Each service runs on a specific port
- Ports help identify services on a system

---

## 🔢 Port Ranges

| Range | Type |
|------|------|
| 0 – 1023 | Well-known ports |
| 1024 – 49151 | Registered ports |
| 49152 – 65535 | Dynamic/Private ports |

---

## 🌐 Common Protocols and Ports

| Port | Protocol | Description |
|------|----------|------------|
| 21 | FTP | File Transfer |
| 22 | SSH | Secure Remote Login |
| 23 | Telnet | Remote Access (insecure) |
| 25 | SMTP | Email Sending |
| 53 | DNS | Domain Name System |
| 80 | HTTP | Web Traffic |
| 110 | POP3 | Email Retrieval |
| 143 | IMAP | Email Retrieval |
| 443 | HTTPS | Secure Web Traffic |
| 3306 | MySQL | Database |
| 3389 | RDP | Remote Desktop |

---

## 🔐 TCP vs UDP Ports

### TCP (Transmission Control Protocol)
- Reliable communication
- Used in:
  - HTTP
  - HTTPS
  - SSH

---

### UDP (User Datagram Protocol)
- Faster but less reliable
- Used in:
  - DNS
  - Streaming
  - VoIP

---

## 🧪 Checking Open Ports

### Using Nmap

nmap <target>

### Service Detection

nmap -sV <target>

---

## ⚠️ Security Importance

- Open ports = potential entry points
- Attackers scan ports to find vulnerabilities

---

## 🔍 Examples

- Port 22 open → SSH attack possible  
- Port 80 open → Web vulnerabilities  
- Port 3306 open → Database exposure  

---

## 🧠 What I Learned

- Ports identify services running on a system
- Open ports can be exploited
- Knowing ports is essential for scanning and enumeration

---

## ✅ Conclusion

Ports and protocols are fundamental to networking and cybersecurity. Understanding them is critical for identifying vulnerabilities and performing penetration testing.