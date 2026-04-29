# 🌐 Lab Network Configuration

## 🎯 Objective
To configure networking in a virtual lab environment for safe cybersecurity practice.

---

## 🧠 Why Network Configuration Matters

- Enables communication between machines
- Required for scanning and exploitation
- Simulates real-world network environments

---

## 🛠️ Network Modes in Virtual Machines

### 1️⃣ NAT (Network Address Translation)
- Default setting
- VM can access internet
- Cannot be accessed from host easily

---

### 2️⃣ Bridged Network
- VM gets IP from same network as host
- Acts like a real device on network

---

### 3️⃣ Host-Only Network ⭐ (Recommended for Labs)
- Communication only between host and VM
- Isolated and safe environment

---

## ⚙️ Recommended Setup

Use:
- Kali Linux (Attacker)
- Another VM (Target, e.g., Metasploitable)

---

## 🔧 Steps (VirtualBox Example)

### Step 1: Open Network Settings
- Select VM → Settings → Network

---

### Step 2: Choose Adapter

Set:
- Adapter 1 → Host-Only Adapter

---

### Step 3: Start Both Machines

- Kali Linux
- Target VM

---

## 🔍 Check IP Address

Run in Kali:

ip a


Look for:
- IP like: `192.168.x.x`

---

## 🔁 Test Connectivity


ping <target-ip>


If ping works → network is configured correctly

---

## 🧪 Example Lab Setup

| Machine | Role | IP |
|--------|------|----|
| Kali Linux | Attacker | 192.168.56.101 |
| Metasploitable | Target | 192.168.56.102 |

---

## 🔐 Security Benefits

- Isolated testing environment
- No risk to real network
- Safe for practicing attacks

---

## ⚠️ Common Issues

- No IP assigned → check adapter
- Ping not working → firewall issue
- Wrong network mode

---

## 🧠 What I Learned

- Networking is critical for labs
- Host-only mode is safest
- Communication is required for scanning

---

## ✅ Conclusion

Proper network configuration is essential for performing real-world cybersecurity testing in a controlled environment.