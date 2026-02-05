# CCNA Mega Lab – Cisco Packet Tracer (Jeremy’s IT Lab)

Dit repository bevat mijn **CCNA Mega Lab**, uitgewerkt in **Cisco Packet Tracer**, gebaseerd op de **Jeremy’s IT Lab CCNA Mega Lab opdracht**. Tijdens mijn opleiding zijn de belangrijkste netwerkonderwerpen behandeld, maar niet alle onderwerpen die binnen het CCNA-domein vallen. Omdat het Cisco CCNA-certificaat een belangrijke standaard is binnen netwerkbeheer, vind ik het essentieel om deze kennis zelfstandig te verdiepen en praktische ervaring op te doen door middel van deze mega lab.

Het lab behandelt **alle configuratie- en netwerktopics** die vereist zijn voor het **Cisco CCNA (200-301) certificaat** en is bedoeld om **praktische netwerkvaardigheden** aan te tonen.

---

## 🎯 Doel van dit lab
- Praktische toepassing van **alle CCNA-onderwerpen**
- Oefenen met **enterprise-netwerkconfiguraties**
- Verdieping in **routing, switching, security en troubleshooting**

---

## 🧠 Behandelde CCNA Onderwerpen



---

## 🧪 Lab Omgeving

Dit CCNA Mega Lab is opgebouwd als een **enterprise netwerkontwerp** met meerdere locaties, redundantie en gescheiden netwerkrollen.

### 🌐 Netwerkarchitectuur
- **Twee locaties:** Office A en Office B
- **Hiërarchisch netwerkmodel:**
  - Core layer
  - Distribution layer
  - Access layer
- Redundante verbindingen voor hoge beschikbaarheid

### 🧱 Apparatuur
- **Routers**
  - R1 (edge router)
  - Verbinding met meerdere ISP’s (ISP A & ISP B)
- **Core Switches**
  - CSW1
  - CSW2
- **Distribution Switches**
  - Office A: DSW-A1, DSW-A2
  - Office B: DSW-B1, DSW-B2
- **Access Switches**
  - Office A: ASW-A1, ASW-A2, ASW-A3
  - Office B: ASW-B1, ASW-B2, ASW-B3
- **Wireless**
  - Wireless LAN Controller (WLC)
  - Lightweight Access Points (LWAPs)
- **Eindapparatuur**
  - PCs
  - Laptops
  - IP Phones
  - Server (SRV1)

### 🔁 Redundantie & High Availability
- Redundante uplinks tussen:
  - Core ↔ Distribution
  - Distribution ↔ Access
- EtherChannel configuraties
- Spanning Tree Protocol (STP) om loops te voorkomen
- Meerdere WAN-verbindingen via verschillende ISP’s

### 🔐 Netwerkdiensten & configuraties
- VLAN segmentatie (data, voice, wireless)
- Inter-VLAN routing
- OSPF routing
- DHCP & DNS
- NAT richting internet
- ACLs voor netwerkbeveiliging
- SSH & device hardening
- Wireless netwerkconfiguratie

### 🛠️ Tooling
- **Cisco Packet Tracer**
- Cisco IOS CLI configuratie

Deze labomgeving simuleert een **realistische enterprise netwerkomgeving** en biedt uitgebreide **hands-on ervaring** met CCNA-gerelateerde configuraties en troubleshooting.

---
