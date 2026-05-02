# 🌐 Subnetting Basics

## 🎯 Objective
To understand subnetting and how networks are divided for better organization and security.

---

## 🧠 What is Subnetting?

Subnetting is the process of dividing a network into smaller networks (subnets).

---

## 📦 Why Subnetting?

- Improves network performance  
- Enhances security  
- Organizes large networks  

---

## 🔢 IP Structure

An IP address has:
- Network part
- Host part

Example:

192.168.1.10/24


---

## 🧮 What is /24?

`/24` = 24 bits for network

Equivalent subnet mask:

255.255.255.0


---

## 🔢 Common Subnet Masks

| CIDR | Subnet Mask | Hosts |
|------|------------|-------|
| /24 | 255.255.255.0 | 254 |
| /25 | 255.255.255.128 | 126 |
| /26 | 255.255.255.192 | 62 |
| /27 | 255.255.255.224 | 30 |

---

## 🔍 Example

IP:

192.168.1.10/24


- Network: 192.168.1.0  
- Broadcast: 192.168.1.255  
- Usable: 192.168.1.1 – 192.168.1.254  

---

## 🔁 Subnetting Concept

Divide:

192.168.1.0/24


Into:
- 192.168.1.0/25  
- 192.168.1.128/25  

---

## 🧪 Practical Use

Used in:
- Network design  
- IP allocation  
- Security segmentation  

---

## 🔐 Importance in Cybersecurity

- Helps identify network ranges  
- Used in scanning targets  
- Helps avoid detection  

---

## 🧠 What I Learned

- Subnetting divides networks into smaller parts  
- CIDR notation defines network size  
- Useful for scanning and network mapping  

---

## ⚠️ Common Mistakes

- Confusing network and host bits  
- Wrong subnet calculations  

---

## ✅ Conclusion

Subnetting is essential for understanding network structure and is widely used in cybersecurity operations.