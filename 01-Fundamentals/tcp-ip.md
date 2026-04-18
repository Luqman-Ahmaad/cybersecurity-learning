# 🌐 TCP/IP Model

## 🎯 Objective
To understand the TCP/IP model and how data is transmitted over the internet.

---

## 🧠 What is TCP/IP?

TCP/IP (Transmission Control Protocol / Internet Protocol) is the standard communication model used on the Internet.

It defines how data is sent, received, and routed across networks.

---

## 🧱 TCP/IP Layers

The TCP/IP model has **4 layers**:

| Layer | Name | Function |
|------|------|----------|
| 4 | Application | User-level protocols |
| 3 | Transport | End-to-end communication |
| 2 | Internet | Routing & IP addressing |
| 1 | Network Access | Physical transmission |

---

## 🔍 Layer Explanation

### 🟣 Application Layer
- Combines OSI layers: Application, Presentation, Session
- Protocols:
  - HTTP
  - FTP
  - SMTP
  - DNS

---

### 🟡 Transport Layer
- Ensures data delivery
- Protocols:
  - TCP (reliable)
  - UDP (fast, unreliable)

---

### 🟠 Internet Layer
- Handles routing
- Uses IP addresses
- Protocol:
  - IP (IPv4 / IPv6)

---

### ⚫ Network Access Layer
- Physical transmission of data
- Includes hardware and MAC addressing

---

## 🔄 TCP vs UDP

| Feature | TCP | UDP |
|--------|-----|-----|
| Reliability | High | Low |
| Speed | Slower | Faster |
| Connection | Connection-oriented | Connectionless |

---

## 🔐 Importance in Cybersecurity

- Helps understand:
  - Packet flow
  - Network attacks
  - Protocol vulnerabilities

### 🔍 Examples:
- TCP SYN Flood → Transport layer
- IP Spoofing → Internet layer

---

## 🧠 What I Learned

- TCP/IP is used in real-world networking
- It is simpler than OSI model
- Understanding protocols is key to hacking and defense

---

## 🔗 OSI vs TCP/IP Mapping

| OSI Model | TCP/IP Model |
|----------|-------------|
| Application | Application |
| Presentation | Application |
| Session | Application |
| Transport | Transport |
| Network | Internet |
| Data Link | Network Access |
| Physical | Network Access |

---

## ✅ Conclusion

TCP/IP is the foundation of modern networking and cybersecurity. Understanding it is essential for analyzing network communication and attacks.