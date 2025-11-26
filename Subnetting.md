# Subnetting – Networking Fundamentals

**Platform:** TryHackMe & Free Tutorials  
**Completed:** November 2025  
**Module:** Network Fundamentals  

---

## 📌 Overview

Subnetting is the practice of **dividing a larger network into smaller, manageable networks (subnets)**.  
It improves network performance, security, and management.  
Understanding subnetting is essential for cybersecurity roles like SOC Analyst, PenTester, or Network Engineer.

---

## 📘 Key Concepts

### 1️⃣ IP Address Structure
- IPv4 address: 32 bits, divided into 4 octets (8 bits each)  
  Example: `192.168.1.10` → 11000000.10101000.00000001.00001010  
- IPv6 address: 128 bits, hexadecimal notation

### 2️⃣ Network vs Host
- **Network portion:** identifies the subnet  
- **Host portion:** identifies the device within the subnet  

Example:  
- IP: 192.168.1.10  
- Subnet Mask: 255.255.255.0  
- Network: 192.168.1.0  
- Hosts: 192.168.1.1 → 192.168.1.254  

---

### 3️⃣ Subnet Mask
Defines which part of the IP is network vs host.  
- Example Masks:  
  - /24 → 255.255.255.0 → 256 addresses (254 usable)  
  - /25 → 255.255.255.128 → 128 addresses (126 usable)  
  - /26 → 255.255.255.192 → 64 addresses (62 usable)  

---

### 4️⃣ CIDR Notation
CIDR (Classless Inter-Domain Routing) shortens subnet mask notation:  
- /24 = 255.255.255.0  
- /26 = 255.255.255.192  

**Formula for Hosts:**  
Number of usable hosts = (2^(32 - subnet_bits)) - 2

---

### 5️⃣ Subnetting Steps (Quick Method)
1. Determine network requirements (number of subnets / hosts)  
2. Calculate subnet mask  
3. Determine network addresses for each subnet  
4. Assign host addresses  
5. Configure routers and gateways  

---

### 6️⃣ Example: /26 Subnetting
- Network: 192.168.1.0/26  
- Subnets: 4  
  1. 192.168.1.0 → Hosts 192.168.1.1 – 192.168.1.62 → Broadcast 192.168.1.63  
  2. 192.168.1.64 → Hosts 192.168.1.65 – 192.168.1.126 → Broadcast 192.168.1.127  
  3. 192.168.1.128 → Hosts 192.168.1.129 – 192.168.1.190 → Broadcast 192.168.1.191  
  4. 192.168.1.192 → Hosts 192.168.1.193 – 192.168.1.254 → Broadcast 192.168.1.255  

💡 Key tip: always remember to subtract 2 for network & broadcast addresses.

---

## 🎯 Skills Gained
- Calculate subnets quickly using CIDR  
- Assign IP addresses to hosts properly  
- Understand network and broadcast addresses  
- Apply subnetting in real-world scenarios (network design, scanning, penetration testing)  

---

## 🔗 References
- TryHackMe – Subnetting Room: https://tryhackme.com/room/subnetting  
- Cisco Subnetting Guide  
- YouTube: NetworkChuck, Jeremy’s IT Lab  
