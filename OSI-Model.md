# OSI Model – Networking Fundamentals

**Platform:** TryHackMe & Free Tutorials  
**Completed:** November 2025  
**Module:** Network Fundamentals  

---

## 📌 Overview

The **OSI (Open Systems Interconnection) Model** is a conceptual framework used to understand how different networking protocols interact.  
It divides network communication into **7 layers**, each with specific responsibilities.  
Understanding OSI is crucial for troubleshooting, network analysis, and cybersecurity tasks.

---

## 📘 OSI Layers

### 1️⃣ Physical Layer
- Deals with **hardware transmission** of raw bits over a medium.  
- Devices: cables, switches (layer 1), hubs  
- Key concept: signals, electrical/optical transmission  
- Example: Fiber optic or Ethernet cable transmitting 1s and 0s

### 2️⃣ Data Link Layer
- Responsible for **node-to-node data transfer**  
- Uses **MAC addresses** for device identification  
- Frames data for transmission  
- Devices: switches (layer 2), bridges  
- Example: ARP resolves IP → MAC

### 3️⃣ Network Layer
- Responsible for **routing and addressing**  
- Uses **IP addresses** to deliver packets across networks  
- Devices: routers  
- Example: Sending a packet from your computer to google.com

### 4️⃣ Transport Layer
- Ensures **end-to-end communication**  
- Protocols: TCP (reliable), UDP (fast)  
- Segments data, ensures delivery, error checking  
- Example: TCP guarantees delivery of an HTTP request

### 5️⃣ Session Layer
- Manages **sessions between applications**  
- Establishes, maintains, terminates connections  
- Example: logging into a remote server via SSH and maintaining the session

### 6️⃣ Presentation Layer
- Translates data between **application and network formats**  
- Handles **encryption, compression, data conversion**  
- Example: HTTPS encrypts web traffic

### 7️⃣ Application Layer
- Closest to the end-user  
- Provides **network services to applications**  
- Protocols: HTTP, FTP, SMTP, DNS  
- Example: Browsing a website, sending emails, file transfer

---

## 📌 Key Points
- Each layer only communicates with **adjacent layers**  
- Helps **troubleshoot networks** by isolating problems  
- Security can be applied at different layers (firewalls, encryption)  

---

## 🎯 Skills Gained
- Understanding how data flows from application to physical layer  
- Ability to map network issues to specific OSI layers  
- Knowledge of layer-specific attacks and defenses  
- Preparedness for SOC analysis, packet sniffing, and penetration testing  

---

## 🔗 References
- Cisco – OSI Model Overview  
- TryHackMe – Networking Fundamentals  
- YouTube – NetworkChuck, Jeremy’s IT Lab  

