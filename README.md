**Cisco Packet Tracer – Skills Integration Challenge**

Medium WriteUp : https://medium.com/@wafulalynnette 

**Overview**

This project is a Skills Integration Challenge completed as part of my cybersecurity training at Tech4Dev. It demonstrates the design and configuration of a multi-department enterprise network with both IPv4 and IPv6 addressing, VLAN segmentation, inter-router connectivity, and external internet access.

**Network Topology**

The network consists of the following devices:

R1 – Core router connecting three internal departments to the Central router and the internet

Central – Border router connecting R1 to the ISP via a serial link

S1, S2, S3 – Three managed switches, each serving a separate department VLAN - Staff, Sales IT

ISP – Internet Service Provider router

Web Server – External server hosting www.cisco.srv and www.cisco6.srv

**Key Configurations**

Dual-stack addressing – Both IPv4 and IPv6 (2001:db8 addressing scheme) configured on all router interfaces

Serial WAN link – R1 to Central via 172.16.1.0/30 for simulated ISP connectivity

External connectivity – Central router connects to ISP at 209.165.200.226/30, enabling access to the external web server

DNS & Default routing – DNS configured at 64.100.0.2, default gateway at 64.100.0.1

VLAN segmentation – Each department isolated on its own switch with appropriate subnetting

**Skills Demonstrated**

- IPv4 and IPv6 dual-stack network design

- Subnetting and IP address planning for multiple departments

- Router and switch configuration in Cisco Packet Tracer

- Serial WAN link configuration between routers

- VLAN setup and inter-VLAN awareness

- DNS and default gateway configuration

- Network troubleshooting and verification

**Tools Used**

- Cisco Packet Tracer

**Screenshot**

<img width="843" height="554" alt="image" src="https://github.com/user-attachments/assets/f1f503cc-2309-4451-91c1-19c85a6307f8" />




