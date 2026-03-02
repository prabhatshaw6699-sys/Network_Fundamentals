# Networking Fundamentals

Hi 
This repository contains the networking fundamentals that I have learned while building my foundation in networking and cybersecurity.

I am still learning, so this repository reflects my understanding at a beginner to intermediate level.

---

## Networking Basics
- What is a computer network  
- Why networking is important  
- How devices communicate in a network  
- Types of networks:
  - LAN (Local Area Network)
  - WAN (Wide Area Network)
  - MAN (Metropolitan Area Network)
  - PAN (Personal Area Network)

---

## Communication Models

### Client-Server Model
- One system works as a **server** and other systems work as **clients**  
- Client sends request and server sends response  
- Server controls data and resources  
- If server is down, service will not work  

**Examples:**
- Web browser and web server  
- Email client and mail server  

---

### Peer-to-Peer (P2P) Model
- All systems work as both **client and server**  
- No central server is required  
- Systems share resources directly with each other  

**Examples:**
- File sharing between two computers  
- Small local networks  

---

### Client-Server vs Peer-to-Peer

| Client-Server | Peer-to-Peer |
|--------------|-------------|
| Central server present | No central server |
| More secure | Less secure |
| Easy to manage | Hard to manage |
| Used in large networks | Used in small networks |

---

## Network Topologies
- Star topology  
- Bus topology  
- Ring topology  
- Mesh topology  
- Hybrid topology  

Topology defines how devices are connected and how data flows in a network.

---

## Networking Devices
- **Router** – Connects different networks and routes packets  
- **Switch** – Connects devices in a LAN using MAC addresses  
- **Bridge** – Connects two LAN segments and filters traffic  
- **Hub** – Sends data to all connected devices  
- **Access Point** – Provides wireless network access  
- **Modem** – Connects ISP network to the local network  

---

## IP Addressing

### What is an IP Address
- IP address is a logical address used to identify a device on a network  
- It helps devices communicate with each other  

### IPv4 and IPv6
- IPv4 is a 32-bit address  
- IPv6 is a 128-bit address  

### Public and Private IP
- Public IP is used on the internet  
- Private IP is used inside local networks  

Private IP ranges:
- 10.0.0.0 – 10.255.255.255  
- 172.16.0.0 – 172.31.255.255  
- 192.168.0.0 – 192.168.255.255  

---

## IP Address Classes (IPv4)

### Class A
- Range: 1.0.0.0 – 126.255.255.255  
- Default Subnet Mask: 255.0.0.0  

### Class B
- Range: 128.0.0.0 – 191.255.255.255  
- Default Subnet Mask: 255.255.0.0  

### Class C
- Range: 192.0.0.0 – 223.255.255.255  
- Default Subnet Mask: 255.255.255.0  

### Class D
- Range: 224.0.0.0 – 239.255.255.255  
- Used for multicast  

### Class E
- Range: 240.0.0.0 – 255.255.255.255  
- Used for research and testing  

---

## MAC Address and ARP
- MAC address is a unique hardware address  
- Works at Data Link Layer  
- ARP maps IP address to MAC address  

---

## Ports and Protocols

### Common Ports
- HTTP – 80  
- HTTPS – 443  
- FTP – 21  
- SSH – 22  
- DNS – 53  

### Protocols
- **TCP** – Reliable and connection-oriented  
- **UDP** – Fast and connectionless  
- **ICMP** – Error reporting and diagnostics  

---

## Data Communication Models

### OSI Model (7 Layers)
Physical, Data Link, Network, Transport, Session, Presentation, Application  

### TCP/IP Model
Network Access, Internet, Transport, Application  

These models help me understand how data travels in real networks.

---

## Routing and Switching
- Difference between router and switch  
- Static and dynamic routing (basic understanding)  
- Routing table basics  
- Switch MAC address table  
- Packet forwarding vs frame forwarding  

---

## Network Security Basics
- HTTP vs HTTPS  
- Importance of encryption  
- Phishing attacks  
- Basic firewall concept  
- Access Control Lists (ACLs)  

---

## Tools and Practice

### Commands I have used
```bash
ping 8.8.8.8
traceroute google.com
ipconfig
ifconfig