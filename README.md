
# Retail Store Network Security Lab

## 📌 Project Overview
Designed and secured a segmented network for a retail store using Cisco Packet Tracer. The goal is to isolate IoT surveillance cameras (VLAN 20) from employee devices (VLAN 10) to prevent lateral movement in case of a camera compromise.

## 🛠️ Technologies Used
- **VLANs** (Network Segmentation)
- **Router-on-a-Stick** (Inter-VLAN Routing)
- **Extended ACLs** (Access Control Lists for traffic filtering)
- **Cisco Packet Tracer**

## ⚙️ Key Implementations
- Configured VLAN 10 for Employees and VLAN 20 for IP Cameras.
- Applied an Extended ACL on the router to **permit** management traffic from Employees to Cameras, but **deny** any initiated traffic from Cameras to Employees.
- Verified the configuration using `ping` and `show access-lists` commands.

## 📁 Repository Contents
- Network_Segmentation_VLAN_ACL.pkt: The working Cisco Packet Tracer file.
- Retail_Network_Security_Project.pdf`: Detailed project report with configuration steps and verification results.
  [MAHMOOD ABDULLAH HASSAN SAEED]
- Aspiring Network Security & IT Support Specialist
  
