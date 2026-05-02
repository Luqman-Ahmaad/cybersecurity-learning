# 🌐 IP Addressing

## 🎯 Objective
To understand IP addressing, its types, and how devices are identified in a network.

---

## 🧠 What is an IP Address?

An IP (Internet Protocol) address is a unique identifier assigned to each device on a network.

Example:

192.168.1.10


---

## 🔢 Types of IP Addresses

### 1️⃣ IPv4
- 32-bit address
- Format: 4 octets (0–255)

Example:

192.168.0.1


---

### 2️⃣ IPv6
- 128-bit address
- Longer and more secure

Example:

2001:0db8:85a3::8a2e:0370:7334


---

## 🌍 Public vs Private IP

### 🔓 Public IP
- Assigned by ISP
- Accessible over the internet

---

### 🔒 Private IP
- Used داخل local networks
- Not accessible from internet

Ranges:

192.168.0.0 – 192.168.255.255
10.0.0.0 – 10.255.255.255
172.16.0.0 – 172.31.255.255


---

## 🔄 Static vs Dynamic IP

| Type | Description |
|------|------------|
| Static | Fixed IP |
| Dynamic | Changes automatically (DHCP) |

---

## 📡 Loopback Address


127.0.0.1


- Refers to the local machine
- Used for testing

---

## 🔍 Finding Your IP

### Linux:

ip a


### Windows:

ipconfig


---

## 🌐 Subnet Basics

IP address consists of:
- Network part
- Host part

Example:

192.168.1.10/24


---

## 🔐 Importance in Cybersecurity

- Used in scanning (Nmap)
- Identifying targets
- Network mapping
- Tracking attackers

---

## 🧠 What I Learned

- IP addresses identify devices
- Private vs public IPs behave differently
- Understanding IP is required for all network attacks

---

## ✅ Conclusion

IP addressing is a core concept in networking and cybersecurity, forming the base for scanning, enumeration, and exploitat