Enterprise Infrastructure Planning for a Startup Company

ITEP 414 - System Administration and Maintenance | Week 2 Portfolio Project
Prepared by: Sandoval, Geoff P. | Bachelor of Science in Information Technology

📋 Project Overview

This project presents an enterprise infrastructure plan for QWERTY Solution Inc., a fictional 20-person software development and IT consulting startup in Brgy. Palasan Santa Cruz Laguna, Philippines. The project covers the company's hardware and software inventory, enterprise network infrastructure, network topology, system administration roles, and infrastructure recommendations.

The plan is designed to show how a Junior System Administrator can plan and organize the IT infrastructure of a startup based on its business requirements, number of employees, departmental needs, security requirements, and future expansion.

🎯 Learning Objectives
Explain the roles and responsibilities involved in system administration
Identify appropriate hardware and software requirements for a small business
Plan enterprise network infrastructure for a startup company
Understand the importance of network security, backup, and infrastructure planning
Connect hardware, software, networking, and system administration into one infrastructure plan
🏢 Company Profile

QWERTY Solution Inc. is a software development and IT consulting startup that builds custom web and mobile applications and provides digital transformation services for small and medium sized enterprises in the Philippines.

Vision: To become a leading Philippine based software solutions provider recognized across Southeast Asia for innovation, reliability, and client centered technology.

Mission: To deliver high quality, scalable, and secure software solutions; to nurture a culture of continuous learning and technical excellence among our people; and to help our clients grow through well engineered technology.

Office Location: Brgy. Palasan Santa Cruz Laguna, Philippines

The company has 20 employees distributed across four departments:

Department	Employees
Information Technology	5
Human Resources	4
Finance	5
Sales	6
TOTAL	20
🖥️ Hardware Inventory Summary

The hardware inventory includes 14 desktop computers and 6 laptops for the 20 employees, along with shared infrastructure for the office.

Major infrastructure includes:

14 desktop computers
6 laptops
1 rack mount server
1 router
2 managed 24 port switches
4 network printers
6 UPS units
3 wireless access points
1 NAS storage device
2 external backup drives
16 monitors

The full hardware inventory includes asset IDs, quantities, departments, purposes, and specifications.

💾 Software Inventory Summary

The software inventory includes:

Windows 11 Pro
Ubuntu Server 22.04 LTS
Microsoft 365 / Office
VS Code
Git
GitHub Desktop
VirtualBox
Google Chrome
Microsoft Defender
AnyDesk
7-Zip

The software inventory identifies the version, license type, and purpose of each software solution.

🌐 Enterprise Network Diagram

The network topology shows the logical flow of the company's network infrastructure. Internet access flows through the ISP modem, firewall, and router before reaching the core switch. The core switch distributes connectivity to the server room, shared services, wireless access points, and the LAN segments of each department.

Network flow:

Internet → ISP Modem → Firewall → Router → Core Switch → Server / Shared Services / Wireless Access Points → Department LAN Segments

The network design also uses VLAN segmentation to separate the different departments and improve network security.

🛠️ System Administration Roles

The project covers four important system administration roles:

Helpdesk Technician: Provides first line technical support, troubleshoots hardware and software issues, resets accounts, and prepares new employee workstations.
Network Administrator: Maintains routers, switches, firewalls, wireless access points, VLANs, and network security policies.
Linux System Administrator: Manages the Ubuntu Server, user accounts, permissions, updates, backups, automation scripts, and server security.
Cloud Administrator: Manages cloud resources such as offsite backups, evaluates cloud migration options, monitors cloud spending, and plans infrastructure scaling.

These roles work together as an interconnected support chain, covering the user's workstation, internal network, server infrastructure, and offsite storage.

🔐 Infrastructure Recommendations

The infrastructure plan recommends:

A business grade fiber internet connection with an SLA
A secondary ISP or LTE failover connection for redundancy
A rack mount server with server grade hardware and ECC RAM
RAID storage for resilience
Ubuntu Server 22.04 LTS
A 3-2-1 backup strategy
VLAN segmentation for departments
Firewall protection at the network perimeter
Regular system patching
Least privilege access
Microsoft Defender for Business or Endpoint
Strong password policies and multi factor authentication
A company password manager
Infrastructure that can support future company growth

The plan also recommends evaluating a hybrid cloud model when the company grows beyond approximately 50 employees.

🚧 Challenges Encountered

One of the most challenging parts of the project was creating the enterprise network diagram. It was easier to list the network equipment, but connecting the modem, firewall, router, switches, server, wireless access points, and department LAN segments required careful planning.

The project also required connecting the company's employee distribution and business requirements to specific hardware, software, networking, security, and backup decisions. This helped demonstrate why infrastructure planning should happen before deployment.

💭 Reflection

The project helped provide a clearer understanding of what a System Administrator does when planning an IT infrastructure. It showed that infrastructure planning is not only about choosing hardware and software, but also about understanding the needs of the business and its employees.

The project also demonstrated the importance of network design, security, backups, and proper planning before deployment. Creating the network diagram and organizing the different infrastructure components helped develop a better understanding of how hardware, software, networking, and security work together.

Overall, the activity provided an opportunity to think like a Junior System Administrator and apply different IT concepts to one realistic enterprise infrastructure plan.

📚 References
CompTIA. "Your Next Move: Systems Administrator."
Cisco. "CCNA Certification."
Linux Professional Institute. "LPIC-1 Overview."
Red Hat. "Red Hat Certified System Administrator (RHCSA)."
Amazon Web Services. "AWS Certified Cloud Practitioner."
Microsoft. "Microsoft Certified: Azure Fundamentals (AZ-900)."
National Institute of Standards and Technology (NIST). "SP 800-63B: Digital Identity Guidelines - Authentication and Lifecycle Management."
Cybersecurity and Infrastructure Security Agency (CISA). "Back Up Business Data."