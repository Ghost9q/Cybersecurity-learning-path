# 🌐 Network Simulation and Subnetting Project (Cisco Packet Tracer)

I recently learned about creating and simulating networks in **Cisco Packet Tracer**, including how to divide them into subnets. To put my knowledge into practice, 
I designed and built a simple network setupusing subnetting and basic device configuration.

---

## 🧮 Subnetting the Network

I started with the IP network **192.168.0.0/24**, and divided it into **two /26 subnets**:

1. **Subnet 1**: `192.168.0.0/26`  
   - IP range: 192.168.0.1 – 192.168.0.62  
   - Used for devices connected via a **wired switch**

2. **Subnet 2**: `192.168.0.64/26`  
   - IP range: 192.168.0.65 – 192.168.0.126  
   - Used for **wireless devices** connected through a **Wireless Access Point (WAP)**

---

## 📶 Wireless Network

I configured a **Wireless Access Point (WAP)** for the second subnet, allowing mobile devices (like phones or tablets) to connect to the network wirelessly. 
The wireless network is secured using **WPA2-PSK encryption**, ensuring that only authorized users can join.

---

## 🖧 Wired Network

For the first subnet, I used a **switch** to connect wired devices like desktop PCs. This subnet is separate from the wireless network but still has access to the same services (like DHCP).

---

## ⚙️ DHCP Server Setup

I also set up a **DHCP server** to automatically assign IP addresses to devices in both subnets. The server is configured with two address pools—one for each 
subnet—ensuring efficient IP management without manual configuration.

---

## 🏁 Summary

This project helped me understand:
- How to subnet a Class C network
- Basic network design using Cisco Packet Tracer
- Configuring WAPs and switches
- Securing wireless networks with WPA2
- Setting up and configuring a DHCP server for multiple subnets

It was a great way to apply the theoretical knowledge I gained in Cisco’s **Networking Basics** course.

