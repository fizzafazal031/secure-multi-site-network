
# 🌐 Secure Multi-Site Enterprise Network (Cisco Packet Tracer)

## 📌 Project Overview
This project simulates a secure and scalable **multi-site enterprise network** using Cisco Packet Tracer.  
It includes a Main Office and Branch Office connected through secure routing and proper network segmentation.

The design focuses on VLAN configuration, inter-VLAN routing, DHCP, DNS, static routing, and network security.



## 🏢 Network Design

### Main Office
The Main Office is divided into multiple VLANs:

- VLAN 10 → HR Department  
- VLAN 20 → Finance Department  
- VLAN 30 → Operations Department  

Each VLAN is logically separated for better security, scalability, and traffic management.

### Branch Office
- Separate LAN network for branch users  
- Independent subnet from Main Office  
- Connected via router-to-router link  
- Communication enabled using static routing  



## ⚙️ Technologies Used

- Cisco Packet Tracer  
- VLAN Configuration  
- Switch Trunking  
- Router-on-a-Stick (Inter-VLAN Routing)  
- DHCP Server Configuration  
- DNS Configuration  
- Static Routing (Inter-site communication)  
- Web Server (HTTP Service)  
- Network Security Configuration  



## 🔐 Security Features

- Console password protection  
- Enable secret password  
- Password encryption enabled  
- MOTD Banner: Unauthorized Access Prohibited  

### 🔑 Device Access Credentials (Lab Simulation)

- Console Password: 123456  
- Enable Secret: 123456  
- VTY Password: 123456  

⚠️ These credentials are strictly for **academic and simulation purposes only** in Cisco Packet Tracer.



## 🌍 Key Functionalities

✔ Communication within same VLAN  
✔ Inter-VLAN routing between departments  
✔ Automatic IP assignment using DHCP  
✔ DNS-based web access simulation  
✔ Web server accessibility via browser (IP/DNS)  
✔ Branch ↔ Main Office connectivity using static routing  
✔ Secure network access with authentication  


## 📊 Project Files

- Cisco Packet Tracer file (.pkt)  
- Screenshots of:
  - VLAN configuration  
  - Trunking setup  
  - Router configuration  
  - DHCP setup  
  - Static routing  
  - Web server testing  
- Project report (if included)



## 💡 Learning Outcome

This project helped in understanding:
- Enterprise network design principles  
- VLAN segmentation and trunking  
- Routing techniques (inter-VLAN + static routing)  
- DNS and web server integration  
- Network security implementation  
- Real-world multi-site connectivity concepts  



## 📁 How to Use

1. Download the `.pkt` file  
2. Open it in Cisco Packet Tracer  
3. Run simulation mode  
4. Test:
   - VLAN communication  
   - Inter-VLAN routing  
   - DHCP IP assignment  
   - DNS web access  
   - Branch connectivity  



## 🔗 Author
Academic Networking Project (Student Submission)
