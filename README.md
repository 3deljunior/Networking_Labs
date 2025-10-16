# 🧠 Networking Labs Collection

A collection of hands-on networking labs demonstrating core routing protocols and concepts using **Cisco Packet Tracer**.  
Each lab includes a `.pkt` file and network topology image for visualization.

---

## 📘 Overview

This repository contains practical implementations of key routing techniques used in real-world networks.  
All configurations were built and tested in **Cisco Packet Tracer**, focusing on understanding the logic and verification of routing behaviors.

---

## 🧩 Labs Included

| Lab Name | Routing Type | Description |
|-----------|--------------|--------------|
| [Static Routing](./Static_Routing/) | Manual Routing | Routes are manually configured on each router, providing full control but no scalability. |
| [RIP (Routing Information Protocol)](./RIP/) | Dynamic Distance-Vector | Simple dynamic routing using hop count as a metric (RIPv2). |
| [EIGRP (Enhanced Interior Gateway Routing Protocol)](./EGRIP/) | Dynamic Hybrid | Cisco-proprietary protocol offering fast convergence and efficient routing. |
| [OSPF (Open Shortest Path First)](./OSPF/) | Dynamic Link-State | Industry-standard link-state routing protocol with area-based design for scalability. |

---

## 🧠 Learning Objectives

- Understand the difference between **static** and **dynamic** routing.
- Learn how routers exchange routes using different algorithms (Distance Vector vs. Link State).
- Practice verifying and troubleshooting routing tables.
- Build and interpret small-to-medium enterprise topologies.

---

## ⚙️ Tools Used

- **Cisco Packet Tracer** (version 8.2.1)

## ✔ Deliverables
- **Network Diagrams (.png)**
- **Routing Configurations (.pkt)**

---

## 📂 Repository Structure
Networking_Labs/
│
├── static-routing/
│ ├── static-routing.pkt
│ ├── topology.png
│ └── README.md
│---
├── rip/
│ ├── rip.pkt
│ ├── topology.png
│ └── README.md
│
├── eigrp/
│ ├── eigrp.pkt
│ ├── topology.png
│ └── README.md
│
└── ospf/
├── ospf.pkt
├── topology.png
└── README.md

