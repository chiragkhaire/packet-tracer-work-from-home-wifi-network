# Home Wi-Fi Network Simulation

A Cisco Packet Tracer simulation of a secure home Wi-Fi network demonstrating fundamental networking concepts including DHCP, static IP addressing, wired and wireless connectivity, and basic network troubleshooting.

---

## Project Objective

Design and configure a functional home network where multiple wired and wireless devices can communicate with each other and access the internet through a wireless router.

---

## Network Topology

```
                    Internet Cloud
                           │
                     Cable Modem
                           │
                    Wireless Router
        ┌────────────┼──────────────┐
        │            │              │
   Desktop PC   Network Printer   Wi-Fi
                                  │
                        ┌─────────┴─────────┐
                        │         │         │
                     Laptop   Smartphone  Tablet
```

---

## Devices Used

| Device | Purpose |
|---------|---------|
| Internet Cloud | Simulated ISP |
| Cable Modem | Internet Connection |
| Wireless Router | Gateway & DHCP Server |
| Desktop PC | Wired Client |
| Laptop | Wireless Client |
| Smartphone | Wireless Client |
| Tablet | Wireless Client |
| Network Printer | Static IP Device |

---

## IP Addressing

| Device | Address |
|---------|----------|
| Router | 192.168.0.1 |
| Desktop PC | DHCP |
| Laptop | DHCP |
| Smartphone | DHCP |
| Tablet | DHCP |
| Printer | 192.168.0.10 (Static) |

Subnet Mask

```
255.255.255.0
```

---

## Features Implemented

- DHCP Configuration
- Static IP Assignment
- Wired Ethernet Connectivity
- Wireless LAN Connectivity
- Internet Access
- Network Printer
- Connectivity Verification

---

## Verification Performed

- DHCP lease obtained successfully
- Router reachable via ICMP (ping)
- Printer reachable via ICMP
- Wireless devices connected successfully
- Internet connectivity verified
- Cisco server accessed successfully

---

## Skills Demonstrated

- Network Design
- TCP/IP Addressing
- DHCP Configuration
- Static IP Configuration
- Wireless Networking
- Connectivity Testing
- Basic Network Troubleshooting
- Cisco Packet Tracer

---

## Software Used

- Cisco Packet Tracer

---

## Author

**Chirag Khaire**

Aspiring IT Support Specialist building practical networking and system administration projects.
