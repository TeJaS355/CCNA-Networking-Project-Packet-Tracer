# CCNA-Networking-Project-Packet-Tracer
CCNA-level enterprise network project using Cisco Packet Tracer featuring OSPF, VLANs, ACLs, NAT, DHCP, RADIUS, NTP, and network security.

## 🔹 Project Overview
This project demonstrates an enterprise-style network designed and implemented using **Cisco Packet Tracer**, based on **CCNA-level networking concepts**.  
The network spans multiple locations (Mumbai, Chennai, and Hyderabad) and includes routing, switching, security, and network services configuration.

---

## 🛠 Technologies Used
- Cisco Packet Tracer
- OSPF Routing Protocol
- VLAN & Inter-VLAN Routing
- Access Control Lists (ACL)
- Network Address Translation (NAT – Static)
- DHCP (IPv4)
- LLDP
- NTP
- RADIUS
- Telnet
- STP PortFast

---

## 📋 Tasks Implemented

1. Renamed all routers
2. Assigned IP addresses to all router interfaces
3. Configured **OSPF routing** on all routers
4. Blocked **PC (192.168.1.2)** from accessing **Web Server (192.168.3.100)** using ACL
5. Restricted **192.168.2.0/24** from accessing the internet while allowing access to internal networks
6. Enabled **LLDP** on all network devices
7. Created **VLANs 10, 20, and 30** on switches connected to the Mumbai router
8. Configured the middle switch connected to Mumbai router in **VTP Transparent mode**
9. Assigned PCs to their respective VLANs
10. Enabled **Inter-VLAN communication**
11. Enabled **STP PortFast** on all switch ports connected to end devices
12. Configured **Static NAT** for Hyderabad PCs with public IP addresses:
    - 2.2.2.1  
    - 2.2.2.2  
    - 2.2.2.3
13. Enabled **Telnet access** on all routers
14. Configured **Console and Enable passwords** (`cisco`) on all routers
15. Configured **NTP** on the Mumbai router
16. Configured **RADIUS authentication** using the server connected to Mumbai router
17. Configured **DHCP (IPv4)** on the Chennai router
18. Created a local user `admin` with password `admin` on all network devices

---

## 🧠 Learning Outcomes
- Designed and implemented a multi-site enterprise network
- Gained hands-on experience with OSPF routing
- Implemented VLAN segmentation and inter-VLAN routing
- Applied ACLs for traffic control and security
- Configured NAT, DHCP, and AAA services
- Improved troubleshooting and network management skills

---

## ▶️ How to Use This Project
1. Download the `.pkt` file from this repository
2. Open it using **Cisco Packet Tracer**
3. Explore router and switch configurations via CLI
4. Verify connectivity, routing tables, and VLAN communication

---

## 👤 Author
**Tejas**  
CCNA Networking Enthusiast
