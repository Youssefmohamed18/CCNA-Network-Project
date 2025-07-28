# 🛠️ CCNA Network Design Project

## 📌 Overview

This project is a complete network design and configuration built using **Cisco Packet Tracer** as part of the CCNA training.  
It simulates a real-world business with **two branches** connected together and provides full internal and external communication for all devices.

---

## 🗺️ Network Topology

The network is divided into **two main branches**:

### 🔹 Main Branch
- Contains **two multilayer switches (MLS)**: one is the primary, and the other is a backup.
- Each MLS is connected to:
  - A **local server**
  - Two **VLANs** (Virtual LANs) for device separation.
- Connected to:
  - **DHCP Server** (external) – provides dynamic IPs to all devices.
  - **Internet Server** – gives all devices access to the outside internet.

### 🔹 Remote Branch
- Has its own **router** connected to:
  - Contains **two multilayer switches (MLS)**: one is the primary, and the other is a backup.
  - A **local server** with 2 VLANs (same setup as main branch).

### 🔁 Both branches are connected via **routing between the two routers**.

✅ **All devices can:**
- Communicate within their VLANs.
- Ping devices in other VLANs and branches.
- Access the internet.
- 
---

## 📌 Features

- 🔌 VLAN segmentation for department isolation  
- 🌐 Inter-VLAN routing using Multilayer Switch  
- 🔁 Redundant connection with backup switch  
- 🔐 Secured switch configuration (SSH, port security)  
- 🧪 Ping tests and troubleshooting applied  

---

## 🖥️ Tools Used
- **Cisco Packet Tracer**
- Static and Dynamic Routing
- VLANs, Inter-VLAN Routing
- DHCP Relay
- Internet Simulation

---

## 📸 Screenshot of the Topology

![Network Topology](Network/Screenshot.png)

---

## 📂 Files Included

- `.pkt` file (Packet Tracer project)
- `Summary.txt` 
- `Screenshot .png` (topology image)

---

## 🚀 How to Open

1. Download the `.pkt` file.
2. Open it using Cisco Packet Tracer.
3. Explore the devices and configurations inside each router/switch.

---

## 💡 Author

**Youssef Mohamed**  
CCNA Certified – July 2025  
[Youssef Mohamed](https://www.linkedin.com/in/youssef-mohamed00/)

