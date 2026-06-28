# University Campus Networking Project (Cisco Packet Tracer)

## 📌 Overview
This project simulates a **University/Campus Network** using Cisco Packet Tracer.  
It is based on a case study of Albion University with **two campuses** located 20 miles apart, hosting multiple faculties and departments.  
The design demonstrates VLAN segmentation, RIP v2 routing, DHCP services, and server connectivity.

## 🏫 Network Requirements
- **Main Campus**
  - **Building A:** Administrative staff (Management, HR, Finance) + Faculty of Business  
    - VLANs used for department separation  
    - DHCP server provides dynamic IPs to staff PCs  
  - **Building B:** Faculty of Engineering & Computing + Faculty of Art & Design  
  - **Building C:** Student labs + IT Department (hosts University Web Server and other servers)  
  - External Email Server hosted on the cloud  

- **Smaller Campus**
  - Faculty of Health & Sciences (staff and student labs on separate floors)

## ⚙️ Configuration Highlights
- Each faculty/department on its own IP network  
- Switches configured with VLANs and security settings  
- **Routing:**  
  - RIP v2 for internal routers  
  - Static route for external email server  
- DHCP configured on Building A router for dynamic IP allocation  

## 🛠️ Tasks Completed
1. **Topology Design:** Planned and prototyped full network in Packet Tracer  
2. **Configuration:** Implemented VLANs, RIP v2, DHCP, and static routing  
3. **Evaluation:** Tested connectivity, scalability, reliability, and security  

## 📂 Files
- `University-Campus-Networking-Project.pkt` → Main Packet Tracer simulation file  

## 🚀 How to Run
1. Download the `.pkt` file from this repository  
2. Open it in Cisco Packet Tracer (v8.x recommended)  
3. Explore the topology, VLANs, and routing setup  

## 📸 Screenshots
(Add screenshots of your topology here for better presentation)

## 📑 License
This project is licensed under the MIT License.
