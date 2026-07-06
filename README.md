<p align="center">
  <a href="https://www.uit.edu.vn/" title="University of Information Technology" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="University of Information Technology">
  </a>
</p>

<h1 align="center"><b>DESIGN NETWORK</b></h1>

## TABLE OF CONTENTS
* [Course Introduction](#courseintroduction)
* [Instructor](#instructor)
* [Team Members](#teammembers)
* [Course Project](#courseproject)
* [Technologies Used](#technologies)
* [PBX System Configuration Details](#configuration)
* [Installation and Deployment](#installation)

## COURSE INTRODUCTION
<a name="courseintroduction"></a>
* **Course Name**: Design Network
* **Course Code**: NT113
* **Class**: NT113.Q22

## INSTRUCTOR
<a name="instructor"></a>
* MSc. **Bui Van Binh**

## TEAM MEMBERS
<a name="teammembers"></a>
| No. | Student ID | Full Name | Github | Email | 
| --- | --- | --- | --- | --- | 
| 1 | 23520164 | Nguyen Huu Cam | [nghuucam](https://github.com/nghuucam) | 23520164@gm.uit.edu.vn | 

## COURSE PROJECT
<a name="courseproject"></a>
**Project Title:** FastPay Enterprise Network & Hybrid Cloud Infrastructure

**Overview:** FastPay is a financial company headquartered in District 1, Ho Chi Minh City, with two regional branches in Hanoi and Da Nang. As a provider of online payment services, the company requires a robust network infrastructure that guarantees high security, low latency, and flexible scalability.

## TECHNOLOGIES USED
<a name="technologies"></a>
* **Environment:** Cisco Packet Tracer
* **Technologies & Protocols:** VLAN, Site-to-Site VPN, Firewall, Captive Portal, Hybrid Cloud (AWS/GCP), Open-source Network Monitoring (e.g., Zabbix)

## NETWORK CONFIGURATION DETAILS
<a name="configuration"></a>

### 1. Headquarters (District 1, Ho Chi Minh City)
* **VLAN Segmentation:** The internal network is strictly isolated using dedicated VLANs for specific departments (Accounting, Risk Management, IT) to ensure data safety and prevent unauthorized access.
* **High Security:** Implemented robust security configurations, including firewall rules, secure user authentication, and wireless security protocols.
* **Hybrid Cloud Deployment:** Utilized Hybrid Cloud architecture (integrating AWS/GCP) to securely host and operate the online transaction systems, ensuring high availability.
* **Wireless Network:** Deployed separated wireless networks for Corporate (Staff) and Guest users. The Guest Wi-Fi requires authentication via a **Captive Portal**.

---

### 2. Regional Branches (Hanoi & Da Nang)
* **Secure Connectivity:** Established **Site-to-Site VPN** tunnels to securely connect the branch offices to the main Data Center at the Headquarters.

---

### 3. System Monitoring
* **Performance Tracking:** Integrated an open-source network management tool to continuously monitor network performance, track bandwidth usage, and ensure system reliability across all branches.

## INSTALLATION AND DEPLOYMENT
<a name="installation"></a>

**To test the simulation in Cisco Packet Tracer:** 
- Open the provided `.pkt` project file using Cisco Packet Tracer (version 8.x or newer recommended).
- Wait a few seconds for the network to converge (switch ports turn green).
- **Testing Inter-VLAN & Security:** Open the command prompt on the IT PC and attempt to ping devices in the Accounting VLAN to verify access control list (ACL) and firewall rules.
- **Testing VPN:** Ping from a PC in the Hanoi/Da Nang branch to the Headquarters' Data Center Server to verify the Site-to-Site VPN tunnel.
- **Testing Captive Portal:** Open the web browser on a Guest Wireless Device and attempt to access a webpage to see the Captive Portal login screen.
