# Enterprise Network Simulation – Secure, Scalable & Highly Available Design 🌐

[![Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-blue?logo=cisco)](https://www.netacad.com/)
[![Network Security](https://img.shields.io/badge/Security-Hardened-red)](#network-security--hardening)

An enterprise-grade, highly available multi-tier network topology built and simulated using **Cisco Packet Tracer**. This project demonstrates complete network design, routing redundancy, physical/logical security, and dynamic host configuration.

---

## 📐 Network Architecture & Hardware Topology

* **Access Layer:** 9 Access Switches connecting **35 end devices** segmented across departments.
* **Distribution Layer:** 4 Layer-3 Distribution Switches handling Inter-VLAN routing via **SVI**.
* **Core Layer:** 4 Routers configured in a full/partial **Mesh Topology** for high availability.
* **Server Infrastructure:** 3 Dedicated Servers including **DHCP** for dynamic IP allocation.

---

## 🔑 Key Features & Configurations

### 1. High Availability & Redundancy
* **HSRP (Hot Standby Router Protocol):** Configured across router pairs to eliminate single points of failure (SPOF) for default gateways.
* **Physical Redundancy:** Dual uplinks configured on each switch for physical link failover.
* **STP (Spanning Tree Protocol):** Enabled across all switches to prevent switching loops.

### 2. Routing & Traffic Management
* **Dynamic Routing:** **OSPF** configured across routers for scalable route calculation.
* **Inter-VLAN Routing:** Managed via SVIs (Switch Virtual Interfaces) on Layer 3 switches.
* **VLAN Segmentation:** 7 departments fully isolated via custom VLANs.
* **Trunk Links:** Strictly configured only between switches to secure traffic.

### 3. Network Security & Hardening
* **Console Access Security:** Protected Console and Privileged EXEC modes with strong encryption.
* **Remote Management:** Secured **VTY lines (Telnet/SSH)** for safe administrative access.

---

## 🛠️ Tech Stack & Protocols
* **Simulation Tool:** Cisco Packet Tracer
* **Protocols:** OSPF, HSRP, STP, SVI, IEEE 802.1Q (Trunking), DHCP, SSH, Telnet
* **Architecture:** Multi-Tier Mesh Topology (Core, Distribution, Access)

---

## 👤 Author
**Khaled Ashraf**
* **LinkedIn:** [khaled-ashraf](www.linkedin.com/in/khaled-ashraf0)
* **GitHub:** [khaled-Ashraf0](https://github.com/khaled-Ashraf0)
* **Portfolio:** [5aled.xyz](https://5aled.xyz)
