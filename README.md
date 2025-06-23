# Task 1: Scan Your Local Network for Open Ports

## 🔧 Tools Used:
- Nmap (TCP SYN Scan)
- Command Prompt / Terminal
- Wireshark (Optional)

---

## 🧠 Objective:
To scan devices on my local network, find open ports, and understand the security risks they may present.

---

## 📍 My IP Address:
Found using `ipconfig`:
- IPv4: 192.168.1.5
- Subnet Range: 192.168.1.0/24

![IP Address Screenshot](screenshots/ipconfig.png)

---

## 🔎 Nmap TCP SYN Scan:
Command used:
```bash
nmap -sS 192.168.1.0/24
