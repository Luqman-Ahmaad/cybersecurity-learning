# 🐉 Kali Linux Installation Guide

## 🎯 Objective
To install and configure Kali Linux for cybersecurity and penetration testing.

---

## 🧠 What is Kali Linux?

Kali Linux is a Debian-based Linux distribution designed for:
- Penetration testing
- Ethical hacking
- Digital forensics

It comes pre-installed with hundreds of security tools.

---

## 🛠️ Requirements

- Minimum 4GB RAM (8GB recommended)
- 40GB storage
- Virtualization software (VirtualBox / VMware)

---

## 🔽 Step 1: Download Kali Linux

- Visit official website:
  https://www.kali.org/get-kali/

- Download:
  - Installer ISO (recommended)

---

## ⚙️ Step 2: Create Virtual Machine

1. Open VirtualBox / VMware
2. Click "New"
3. Select:
   - Type: Linux
   - Version: Debian (64-bit)

---

## 💾 Step 3: Allocate Resources

- RAM: 4GB+
- CPU: 2 cores
- Disk: 40GB+

---

## 📀 Step 4: Attach ISO

- Select downloaded Kali ISO file
- Set as boot device

---

## 🚀 Step 5: Start Installation

1. Start VM
2. Choose:
   - Graphical Install
3. Follow steps:
   - Language
   - Time zone
   - Keyboard

---

## 👤 Step 6: Set Credentials

- Username
- Password

---

## 💽 Step 7: Disk Partition

- Select:
  - Guided - use entire disk
- Continue installation

---

## 🔄 Step 8: Complete Installation

- Wait for installation to finish
- Reboot system
- Remove ISO when prompted

---

## ⚙️ Step 9: Install Guest Additions

Improves:
- Screen resolution
- Performance
- Clipboard sharing

---

## 🔐 Post Installation Updates

Run:

sudo apt update && sudo apt upgrade -y


---

## 🧠 What I Learned

- Kali Linux is essential for cybersecurity practice
- Proper installation ensures smooth lab experience
- System updates are important for security tools

---

## ⚠️ Ethical Note

Use Kali Linux only:
- In lab environments
- With permission

---

## ✅ Conclusion

Kali Linux provides a complete platform for ethical hacking and will be used throughout this learning journey.
