# GRE-Tunnel-Lab

📌 Lab Objective

The objective of this lab is to configure and verify a GRE tunnel between two routers to provide connectivity between remote LAN networks across a WAN connection.

🎯 Lab Purpose

Generic Routing Encapsulation (GRE) allows encapsulation of traffic between two routers across a public or WAN network. This enables:

Site-to-site connectivity for private networks.

Routing of different protocols through the tunnel.

Simplified static routing between LANs.

This lab demonstrates how to build and verify GRE tunnels, an important skill for Cisco engineers and CCNA-level networking.

🖥️ Lab Topology

R1 – Remote router with LAN 192.168.1.0/24.

R2 – Central router with LAN 192.168.2.0/24.

WAN link between R1 and R2 using 172.16.1.0/30.

GRE Tunnel between R1 and R2 using 10.10.10.0/30.
