# Network Topology: Anatolian & European LAN Connection

## Project Overview
This project demonstrates a **two-LAN network topology** designed and simulated using **Cisco Packet Tracer**.  
It represents two geographically separated local networks — **Anatolian Side (LAN-1)** and **European Side (LAN-2)** — connected via routers and configured with static IP addressing.

---

## 🖧 Network Structure

### Anatolian Side (LAN-1)
- **Network:** 192.168.10.0/24  
- **Devices:**
  - Laptop0 — 192.168.10.2  
  - Server0 — 192.168.10.3  
  - PC0 — 192.168.10.4  
- **Gateway:** 192.168.10.1

### European Side (LAN-2)
- **Network:** 192.168.20.0/24  
- **Devices:**
  - Printer0 — 192.168.20.2  
  - PC1 — 192.168.20.3  
  - Laptop1 — 192.168.20.4  
- **Gateway:** 192.168.20.1

---

## Interconnection
- **Router-to-Router Connection:**  
  - Interface: `Gig0/0 ↔ Gig0/1`  
  - IP: 168.192.20.1 (link network)  
- Enables communication between both LANs.

---

## Key Features
- Static IP addressing  
- Layer 2 switching  
- Basic routing configuration  
- Simulated client-server communication  
- Printer integration

---

## Tools Used
- Cisco Packet Tracer 8.x  
- Basic networking devices: Routers (1941), Switches (2960), PCs, Laptops, Server, and Printer

---

## Author
**Atahan**  
💻 Networking & IT Enthusiast  

