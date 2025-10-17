ACL (Access Control List)
This repository contains a Cisco Packet Tracer project demonstrating the use of Access Control Lists (ACLs) in networking.
The project includes routers, switches, and PCs connected in a topology where ACL rules are applied to control traffic between networks.

📂 Project Files

ACL -Practical.pkt → Cisco Packet Tracer project file
ACL.png → Network topology diagram

🔑 What is ACL?
An Access Control List (ACL) is a set of rules used in routers (or switches) to filter traffic.
It decides whether to permit or deny data packets based on conditions like:

Source IP address
Destination IP address
Protocol (TCP, UDP, ICMP, etc.)
Port numbers (HTTP, FTP, Telnet, etc.)

✨ Types of ACL:
Standard ACL → Filters traffic using only the source IP address.
Extended ACL → Filters traffic using source, destination, protocol, and ports.
📌 Topology Overview
The topology has 3 routers, each connected to its own LAN, and interconnected with serial links.

IP Addressing Scheme
Router0 (LAN 1)

LAN: 10.0.0.0/24
Router IP: 10.0.0.1
PCs: 10.0.0.2, 10.0.0.3
Router1 (LAN 2)

LAN: 20.0.0.0/24
Router IP: 20.0.0.1
PCs: 20.0.0.2, 20.0.0.3
Router2 (LAN 3)

LAN: 30.0.0.0/24
Router IP: 30.0.0.1
PCs: 30.0.0.2, 30.0.0.3
Serial Links (WAN Connections)

Router0 ↔ Router1: 192.168.1.1 / 192.168.1.2
Router1 ↔ Router2: 192.168.2.1 / 192.168.2.2

🎯 Objective
The main goals of this project are:

To configure ACLs on routers.
To control which PCs or networks are allowed or denied communication.
To practice both Standard and Extended ACLs in Cisco Packet Tracer.
