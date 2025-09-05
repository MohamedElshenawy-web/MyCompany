# 🚀 Multi-Branch Network Topology Project

## 📖 Overview
I’ve been working on designing and implementing a **multi-branch network topology** that ensures **scalability, security, and efficiency** across multiple locations.  

This project demonstrates real-world enterprise networking concepts, from **VLAN design** to **dynamic routing with OSPF**.  

---

## 📍 Branches & Zones

### 🟧 Alexandria Branch (Orange Zone)  
- **3 VLANs**: Admins, Servers, IP Phones  
- Web Server 🌐 | DNS Server 📡 | DHCP Server 📦  
- Core Switches | L2 Switches  

### 🟥 Cairo Branch (Red Zone)  
- **5 VLANs**: Management, IT, Sales, HR, IP Phones  
- Core Switches | L2 Switches | Access Point 📶  

### 🟦 Giza Branch (Blue Zone)  
- **5 VLANs**: Management, IT, Sales, HR, IP Phones  
- Core Switches | L2 Switches | Access Point 📶  

### 🟩 Asuit Branch (Teal Zone)  
- **5 VLANs**: Management, IT, Sales, HR, IP Phones  
- Core Switches | L2 Switches | Access Point 📶  

### 🟪 Tanta Branch (Purple Zone)  
- **5 VLANs**: Management, IT, Sales, HR, IP Phones  
- Core Switches | L2 Switches | Access Point 📶  

### 🟨 Damnhour Branch (Yellow Zone)  
- **5 VLANs**: Management, IT, Sales, HR, IP Phones  
- Core Switches | L2 Switches | Access Point 📶  

---

## ⚙️ Key Highlights
- 🔗 **28 VLANs in total** with full inter-VLAN connectivity  
- 🛠️ Initially deployed with **Static Routing** → Migrated to **OSPF Dynamic Routing**  
- 📡 **DHCP Services** covering all wired & wireless devices  
- 🧩 **Classless Subnetting (VLSM)** to optimize IP usage  
- ⚡ **EtherChannel** implemented between Core Switches (L3) in each branch  
- 🔒 **Security Best Practices**: All unused ports closed & mapped to a blackhole VLAN  

---

## 🛰️ Routing Update
I successfully implemented the **Open Shortest Path First (OSPF) protocol** in this network:  

- ✅ Reduced time wasted with static routing  
- ✅ Minimized misconfiguration risks  
- ✅ Improved network redundancy and resiliency  
- ✅ Streamlined configuration scripts for efficiency  

---

## 💡 Outcome
This setup ensures:  
- High availability  
- Efficient IP allocation  
- Strong security across all branches  
- Scalable design for future expansion  

---

## 📌 Next Steps
- 🔄 Explore **BGP for external routing**  
- 📊 Add **network monitoring tools** (SNMP, Syslog, NetFlow)  
- ☁️ Consider **Cloud integration** for hybrid networking  
