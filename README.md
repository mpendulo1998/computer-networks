Computer Networks Project – IPv6, VLANs & Routing

This project is part of the Computer Networks IVA (PNA117V) module and demonstrates the design, configuration, and verification of an enterprise network using Cisco Packet Tracer.

It focuses on VLAN segmentation, IPv6 addressing, inter-VLAN routing, OSPFv3 implementation, Frame Relay, and ACL configurations.

 Project Files

Assigmen1.pkt – Cisco Packet Tracer simulation file of the full network.

khoza.docx – Documentation of the design, planning, configurations, and verification outputs.

Features

VLAN & Port Planning

Multiple VLANs created for different departments and sites.

Proper port-to-VLAN mapping applied.

IPv6 Address Planning & Assignment

Unique /64 subnets assigned per VLAN, WAN, and site.

Addressing scheme ensures scalability and simplicity.

Network Topology

Core Routers, LAN Distribution Routers, Edge Distribution Routers, WAN Router, Remote Branch (RB), and Recovery Site (RS).

Hierarchical design with redundancy.

Routing & Connectivity

OSPFv3 enabled across routers and multilayer switches.

Inter-VLAN routing configured.

Frame Relay for WAN simulation.

Access Control Lists (ACLs)

Implemented for traffic filtering and security.

Testing & Verification

ping tests between devices across VLANs and remote sites.

show commands outputs included in documentation (show vlan brief, show running-config, show ipv6 route).

 Setup Instructions

Install Cisco Packet Tracer

Download Cisco Packet Tracer
 (version 8.2 or higher recommended).

Install and launch the application.

Open the Project

Clone or download this repository.

Open Assigmen1.pkt in Cisco Packet Tracer.

Explore the Network

Check the logical topology and device connections.

Open CLI on routers and switches to view configurations.

Run Verification Commands

On any router/switch CLI, run:

show vlan brief
show running-config
show ipv6 route
ping <IPv6 address>


Verify connectivity between VLANs and across WAN links.

Modify & Extend

Try adding new VLANs or IPv6 subnets.

Implement additional ACLs or routing policies.

Test resilience by shutting down links and verifying OSPFv3 convergence.

 Technologies Used

Cisco Packet Tracer

IPv6 Addressing

OSPFv3 Routing Protocol

VLANs & Inter-VLAN Routing

Frame Relay

ACLs

 Learning Outcomes

Understand and apply hierarchical network design principles.

Configure IPv6 addressing across multiple sites.

Implement VLANs and inter-VLAN routing.

Deploy OSPFv3 for dynamic routing.

Test and troubleshoot connectivity with Cisco IOS commands.

 Author

Mpendulo Justice Khoza
Advanced Diploma in Information Technology
Tshwane University of Technology
