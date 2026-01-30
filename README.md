Horizon Community College – Multi‑Campus Network Design
This project is a complete enterprise‑level network design created for my Computer Networking Capstone at Clark State. It simulates a real‑world deployment for a three‑campus educational institution using Cisco Packet Tracer, with a focus on scalability, security, VLAN segmentation, wireless design, and structured IP addressing.

📌 Project Overview
The goal of this project was to design a secure, scalable, and fully segmented network infrastructure for:
- 1 Main Campus
- 2 Branch Campuses
- 20 Administrative Offices
- 10 Classrooms (20 student stations each)
- Instructor stations, servers, printers, and wireless networks
The design includes physical layout planning, logical topology, VLAN segmentation, DHCP, NAT, ACL security, port security, and firewall configuration.

🏛️ Network Architecture
Main Campus
- 10 classrooms (20 student stations each)
- 20 administrative offices
- Instructor stations
- Core switch + ASA firewall
- Structured cabling and access switches per room
Branch Campuses
- 5 classrooms + 5 offices each
- ISR router + ASA firewall
- VLANs for students and instructors

🌐 Logical Topology
- Core router handles inter‑VLAN routing
- Access switches connected via trunk links
- ASA 5505 firewall filters inbound/outbound traffic
- WAN links simulated between campuses

🔐 Security Features
- VLAN isolation between students, instructors, admin, servers, printers, and wireless
- ACLs blocking student access to admin/servers
- Port security with sticky MAC + violation shutdown
- WPA2‑Enterprise for staff Wi‑Fi
- WPA2‑PSK for guest VLAN
- Physical security: locked closets, badge access, secured server room

🧩 VLAN & IP Segmentation
|  |  |  | 
|  |  |  | 
|  |  |  | 
|  |  |  | 
|  |  |  | 
|  |  |  | 
|  |  |  | 
|  |  |  | 


Each VLAN uses a /24 subnet for simplicity, scalability, and troubleshooting.

🔧 DHCP & NAT Configuration
- DHCP pools configured on routers for each VLAN
- Reserved static IPs for infrastructure devices
- NAT overload (PAT) for internet access
- Public‑facing interface routes through ASA firewall

🛡️ Firewall & ACL Policies
- ASA firewall enforces inbound/outbound rules
- ACLs restrict lateral movement
- Students cannot access servers, printers, or admin VLANs
- Only required inter‑VLAN traffic is permitted

🔄 Backup & Redundancy Planning
- Local + cloud backup strategy
- Nightly full backups with off‑site replication
- Planned redundant WAN paths (conceptual due to Packet Tracer limitations)
- Fiber‑based intercampus links (simulated)

📁 Included Files
- Packet Tracer (.pkt) full network simulation
- PDF documentation (final report + slides)
- Topology diagrams (logical + physical)
- VLAN map and addressing plan

🧠 Skills Demonstrated
- Enterprise network design
- VLAN segmentation & inter‑VLAN routing
- Cisco ASA firewall configuration
- DHCP, NAT, ACLs, port security
- Wireless network planning
- Structured IP addressing
- Documentation & diagramming
- Real‑world deployment simulation

🏁 Conclusion
This project demonstrates a complete, scalable, and secure multi‑campus network design suitable for a real educational institution. It integrates best practices in routing, switching, security, wireless, and documentation, and serves as a strong example of practical networking and cybersecurity skills.

