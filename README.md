# Networking Fundamentals Portfolio 📡

Welcome! 👋  
This repository documents my **practical and theoretical understanding of Networking Fundamentals**.  
It reflects what I have **studied, understood, and practiced at a foundational–intermediate level**, with a focus on real-world networking and cybersecurity relevance.

---

## 📌 Table of Contents
1. Networking Basics  
2. Network Topologies  
3. Networking Devices  
4. IP Addressing, Ports & Protocols  
5. Data Communication Models  
6. Routing & Switching  
7. Network Security Fundamentals  
8. Tools & Hands-on Exposure  
9. Learning Progress  

---

## 1️⃣ Networking Basics
- Definition and purpose of computer networks  
- Why networking is important in cybersecurity  
- Types of networks:
  - LAN (Local Area Network)
  - WAN (Wide Area Network)
  - MAN (Metropolitan Area Network)
  - PAN (Personal Area Network)

**Key Focus:**  
Understanding how data moves between systems inside and outside a network.

---

## 2️⃣ Network Topologies
- Star Topology  
- Bus Topology  
- Ring Topology  
- Mesh Topology  
- Hybrid Topology  

**Understanding:**  
- Physical vs Logical topology  
- How topology impacts performance, scalability, and fault tolerance  

---

## 3️⃣ Networking Devices
- **Router**
  - Routes packets between different networks  
  - Works at Network Layer (Layer 3)
- **Switch**
  - Connects devices inside a LAN  
  - Uses MAC address table  
- **Hub**
  - Broadcasts traffic to all ports (no intelligence)  
- **Access Point**
  - Extends wireless network access  
- **Modem**
  - Converts ISP signal to usable network signal  

---

## 4️⃣ IP Addressing, Ports & Protocols

### IP Addressing
- IPv4 & IPv6 basics  
- Public IP vs Private IP  
- Private IP ranges:
  - 10.0.0.0 – 10.255.255.255  
  - 172.16.0.0 – 172.31.255.255  
  - 192.168.0.0 – 192.168.255.255  
- Default Gateway concept  
- Introduction to Subnetting (network & host separation)

### MAC Address & ARP
- MAC address as a hardware identifier  
- Used at Data Link Layer  
- ARP resolves IP → MAC mapping inside a LAN  

### Ports
- Port numbers identify services on a host  
- Common ports:
  - HTTP – 80  
  - HTTPS – 443  
  - FTP – 21  
  - SSH – 22  
  - DNS – 53  

### Protocols
- **TCP**
  - Reliable, connection-oriented  
  - Used for web, email, file transfer  
- **UDP**
  - Fast, connectionless  
  - Used for streaming, DNS  
- **ICMP**
  - Error reporting and diagnostics  
  - Used by ping and traceroute  

---

## 5️⃣ Data Communication Models

### OSI Model (7 Layers)
1. Physical – Transmission of bits  
2. Data Link – MAC addressing & frames  
3. Network – IP addressing & routing  
4. Transport – TCP/UDP & ports  
5. Session – Session management  
6. Presentation – Encryption & formatting  
7. Application – User-level protocols  

### TCP/IP Model (4 Layers)
- Network Access  
- Internet  
- Transport  
- Application  

**Understanding:**  
Mapping OSI layers to real-world networking tools and protocols.

---

## 6️⃣ Routing & Switching
- Router vs Switch (Layer-based comparison)  
- Static Routing vs Dynamic Routing (basic idea)  
- Routing table fundamentals  
- Switch MAC address table  
- Difference between:
  - Packet forwarding  
  - Frame forwarding  

---

## 7️⃣ Network Security Fundamentals
- HTTP vs HTTPS  
- Role of encryption in secure communication  
- Phishing attacks and suspicious links  
- Firewalls (basic filtering concept)  
- Access Control Lists (ACLs)  

**Cybersecurity Angle:**  
How weak networking concepts can lead to security vulnerabilities.

---

## 8️⃣ Tools & Hands-on Exposure

### Networking Commands
```bash
ping 8.8.8.8        # Connectivity testing
traceroute google.com  # Path analysis
ipconfig            # Windows IP configuration
ifconfig / ip a     # Linux network configuration