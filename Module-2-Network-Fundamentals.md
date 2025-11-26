# Module 2: Network Fundamentals

**Platform:** TryHackMe and Youtube (Free tutorials)  
**Completed:** November 2025  
**Previous Module:** Introduction to Cyber Security  
**Next Module:** Advanced Networking & Security  

---

## 📌 Overview

This module introduces the fundamentals of networking, essential for cybersecurity.  
It covers IP addressing, MAC addresses, ports, protocols, OSI model, LAN/WAN concepts, subnetting, and basic network security.  
By completing this module, I built a strong foundation for understanding network traffic, monitoring, and analyzing cybersecurity threats.

---

## 📘 Topics Covered

### 1️⃣ What is a Network?
- A network is a group of devices that communicate to share data and resources.  
- Common uses: internet access, file sharing, printer sharing, managing systems.  

### 2️⃣ IP Addresses
- IPv4 example: `192.168.1.10`  
- IPv6 example: `2001:0db8:85a3::8a2e:370`  
- Static vs Dynamic IP addresses  

### 3️⃣ MAC Address
- Unique hardware address of each device  
- Example: `A0-B1-C2-D3-E4-F5`  
- Used to identify devices on a local network  

### 4️⃣ Ports
- A “door” for specific types of network traffic  
- Common ports:
  - HTTP: 80  
  - HTTPS: 443  
  - SSH: 22  
  - FTP: 21  
  - DNS: 53  

### 5️⃣ Protocols
- TCP: Reliable, ensures data delivery  
- UDP: Faster, no guarantee  
- HTTP/HTTPS, DNS, DHCP, ICMP  

### 6️⃣ TCP vs UDP
| Feature | TCP | UDP |
|---------|-----|-----|
| Reliability | Guaranteed | Not guaranteed |
| Speed | Slower | Faster |
| Use Cases | Web, Email | Video streaming, Gaming |

### 7️⃣ OSI Model (7 Layers)
1. Physical – cables, electricity  
2. Data Link – MAC addresses  
3. Network – IP addresses  
4. Transport – TCP/UDP  
5. Session – session management  
6. Presentation – encryption/translation  
7. Application – software applications  

### 8️⃣ LAN vs WAN
- LAN: Local Area Network – small, private network  
- WAN: Wide Area Network – large, spans multiple locations  

### 9️⃣ Subnetting
- Dividing large networks into smaller subnets  
- Example: `192.168.1.0/24` → 256 addresses  

### 🔟 DHCP
- Automatically assigns IP addresses, subnet masks, gateways, and DNS servers  

### 1️⃣1️⃣ NAT
- Allows multiple devices on a private network to share a single public IP  

### 1️⃣2️⃣ Firewalls
- Monitor traffic, allow or deny based on rules  
- Network firewall vs Host firewall  

### 1️⃣3️⃣ Network Threats
- MITM (Man in the Middle)  
- ARP Spoofing  
- DNS Hijacking  
- Packet Sniffing  
- Port Scanning  

---

## 🎯 Skills Gained
- Understanding IP, MAC, and subnetting  
- OSI model comprehension  
- Knowledge of protocols and ports  
- Ability to analyze network traffic  
- Preparedness for SOC Analyst or Red Teaming tasks  

---

## 🔗 References
- TryHackMe – Network Fundamentals (Free)
- TryHackMe – Subnetting (Free)
- YouTube Networking Tutorials (NetworkChuck, Jeremy’s IT Lab, Cisco Basics)
- Cisco Official Docs – IP, Subnetting, OSI Model
- Wireshark Documentation – Understanding Network Traffic
