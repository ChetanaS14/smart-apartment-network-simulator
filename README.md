# Smart Apartment Network Simulation  
A Computer Networks Mini Project using Cisco Packet Tracer

## Overview
This project simulates a Smart Apartment Network using Cisco Packet Tracer. It demonstrates how DHCP, wireless connectivity, IoT devices, and basic home networking concepts work together in a real-world scenario. The project includes router configuration, device communication, DHCP automation, and simulation testing.

---

## Features
- Fully designed home/apartment network  
- DHCP-enabled IP assignment  
- Wireless network configuration  
- Integration of IoT devices (smart bulb, fan, AC, etc.)  
- PC, laptop, and smartphone connectivity  
- Testing using ping and simulation mode  
- Simple star topology for clean communication flow  

---

## Technologies Used
- Cisco Packet Tracer 8.x  
- Networking Concepts:  
  - DHCP  
  - DORA (Discover → Offer → Request → Acknowledge)  
  - Router Configuration  
  - Wireless Networks  
  - IoT Device Setup  

---

## Network Topology
The apartment network includes:  
- Router (DHCP Server enabled)  
- Switch  
- Wireless Access Point  
- PC  
- Laptop  
- Smartphone  
- IoT Devices:
  - Smart Bulb  
  - Smart Fan  
  - Smart AC  

All devices automatically receive IP addresses via DHCP.

---

## Why DHCP Instead of OSPF?
- **DHCP**: Assigns IP addresses automatically within a single network.  
- **OSPF**: Used for routing between multiple networks.  

Since this project contains **only one network**, OSPF is not required. DHCP is the correct protocol for home/apartment networks.

---

## DHCP DORA Process
1. **Discover** – Client searches for a DHCP server  
2. **Offer** – Server offers an IP  
3. **Request** – Client requests the offered IP  
4. **Acknowledge** – Server confirms and assigns the IP  

Every device in the apartment follows this process to obtain its IP.

---

## Configuration Summary

### Router
- DHCP pool created  
- Default gateway set  
- Wireless SSID + password configured  
- IP addressing done  

### End Devices
- PC and Laptop set to DHCP mode  
- Wireless devices connected to Wi-Fi  

### IoT Devices
- Connected via Wi-Fi  
- Controlled through Home Gateway  

---

## Testing and Verification
- Ping test between all devices  
- DHCP IP assignment checked  
- IoT device connectivity verified  
- Packet flow viewed in Simulation Mode  

(You can add screenshots in a `/screenshots` folder if needed.)

---

## File Structure
Smart-Apartment-Network/
│── SmartApartment.pkt
│── README.md
---

## Learning Outcomes
- Designing a basic home network  
- DHCP configuration and verification  
- Wireless network setup  
- IoT integration in Packet Tracer  
- Troubleshooting using simulation tools  

---

## Future Improvements
- VLAN implementation  
- CCTV camera module  
- Cloud connectivity  
- Routing protocols (if additional networks added)

---

## Author
**Chetana S**  
Data Science Student & Networking Enthusiast
