Welcome to my hands-on networking portfolio! I am a Bachelor of Science in Information Technology (BSIT) graduate currently preparing for the Cisco Certified Network Associate (200-301 CCNA) certification.

This repository serves as a practical demonstration of my ability to design, configure, troubleshoot, and secure enterprise network infrastructures across multi-vendor environments, emulators (GNS3, Cisco Packet Tracer), and network automation scripts.

About Me
Degree: B.S. in Information Technology
Target Certification: Cisco Certified Network Associate (CCNA 200-301)
Core Competencies: Enterprise Routing & Switching, Network Security Hardening, IPAM/Subnetting, Packet Analysis (Wireshark), Network Automation (Python/Netmiko).
Connect with me: linkedin.com/mjjersey | mjjersey06@gmail.com 

Tech Stack & Toolchain
Emulation & Simulation: Cisco Packet Tracer, GNS3, VMware Workstation Pro
Operating Systems: Cisco IOS/IOS-XE, Juniper Junos OS, Linux (Ubuntu/Debian)
Analysis & Diagramming: Wireshark (Deep Packet Inspection), Draw.io (diagrams.net)
Automation & Scripting: Python 3, Netmiko, Git, VS Code


Lab Portfolio Index
Below is the complete 6-week roadmap of major labs, including topology diagrams, configuration files, and verification logs.

Week 1: Device Hardening & Static Routing
📄 Lab 1.1: Enterprise Management & Hardening Baseline
Focus: SSH v2 configuration, RSA key generation, privilege levels, service password encryption, MOTD banners, line lockdown.

📄 Lab 1.2: Dual-Stack Static & Floating Backup Routing
Focus: IPv4/IPv6 static default routes, Administrative Distance (AD) tuning, primary/secondary WAN automatic failover.

Week 2: Subnetting & Layer 2 Switching
📄 Lab 2.1: Multi-Branch VLSM Design & Allocation
Focus: Variable Length Subnet Masking (VLSM), route summarization, IP address management (IPAM), WAN link allocation.

📄 Lab 2.2: Enterprise VLANs, 802.1Q Trunking & Native VLAN Security
Focus: 802.1Q encapsulation, Native VLAN modification, DTP disabling (switchport nonegotiate), VLAN pruning.

Week 3: Inter-VLAN Routing & L2 Aggregation
📄 Lab 3.1: Router-on-a-Stick vs. Layer 3 Switch Inter-VLAN Routing
Focus: 802.1Q subinterfaces, Switch Virtual Interfaces (SVIs), routed ports (no switchport), performance comparison.

📄 Lab 3.2: LACP EtherChannel Aggregation & Rapid-PVST+ Tuning
Focus: 802.3ad LACP port bundling, Rapid Spanning Tree Protocol, Root Bridge priority election, PortFast, BPDU Guard.

Week 4: Dynamic Routing & High Availability
📄 Lab 4.1: Single-Area OSPFv2 Neighbor Adjacency & Cost Tuning
Focus: OSPF Area 0, Passive Interfaces, metric cost adjustments, DR/BDR election, Wireshark packet analysis.

📄 Lab 4.2: First-Hop Redundancy with HSRP Active/Standby Failover
Focus: HSRP v2 gateway redundancy, Virtual IP/MAC, preemption, interface priority tracking.

Week 5: Perimeter Services & Access Control
📄 Lab 5.1: Router DHCP Server, Relay & Dynamic NAT/PAT
Focus: Router DHCP pools, IP Helper-Address (Relay), Port Address Translation (PAT/Overload) for LAN internet access.

📄 Lab 5.2: Security Policy Enforcement with Standard & Extended ACLs
Focus: Standard & Extended Named ACLs, VTY SSH access filtering, Guest subnet isolation, ICMP vs HTTP traffic rules.

Week 6: Layer 2 Attack Mitigation & Automation Capstone
📄 Lab 6.1: Layer 2 Defense Infrastructure (Port Security, Snooping, DAI)
Focus: Port Security (sticky MACs, err-disabled recovery), DHCP Snooping, Dynamic ARP Inspection (DAI).

📄 Lab 6.2: Capstone - Cisco-to-Juniper OSPF Interoperability & Python Automation
Focus: Cross-vendor dynamic routing (Cisco IOS to Juniper Junos OS), Python Netmiko automated config backups.

Sample Verification & Packet Capture Proof
Every major lab folder includes raw evidence of network functionality:

1. Sanitized Configuration Files: Saved as .txt files in each project directory.
2. Wireshark Captures: Saved .pcap files for OSPF Hello exchanges, TCP handshakes, and DHCP messaging.
3. CLI Verification Reports: Terminal captures proving ping reachability

How to Navigate This Repository
To inspect a lab project, click on any of the lab links in the index above. Each directory contains:

- README.md detailing the topology, objectives, addressing scheme, and step-by-step CLI commands.
- Topology diagrams (.png).
- Raw CLI output logs (.txt).
- Packet trace captures (.pcap) where applicable.
