# Virtualized-Network-Infrastructure-with-Proxmox-pfSense-FreeRADIUS-daloRADIUS-and-Snipe-IT
This project demonstrates the design and implementation of a virtualized enterprise network infrastructure using Proxmox VE, pfSense, FreeRADIUS (daloRADIUS), and Snipe-IT.

The infrastructure consists of two physical servers:

•	Server 1 hosts pfSense, which provides firewall, routing, DHCP, and network management services.

•	Server 2 runs Proxmox VE as a virtualization platform and hosts two Ubuntu Server virtual machines:

    o	Ubuntu VM 1: FreeRADIUS + daloRADIUS for Authentication, Authorization, and Accounting (AAA).

    o	Ubuntu VM 2: Docker-based Snipe-IT for IT asset management.

Architecture

Physical Server 1

    
    └── pfSense
        ├── Firewall
        ├── DHCP Server
        ├── Routing
        └── IP Address Management

    
    


Physical Server 2

    └── Proxmox VE
    │
    ├── Ubuntu VM 1
    │   ├── FreeRADIUS
    │   ├── daloRADIUS
    │   └── MariaDB
    │
    └── Ubuntu VM 2
        ├── Docker
        └── Snipe-IT

            



Features

    •	Installed and configured pfSense on a dedicated physical server.
    •	Configured DHCP server, firewall rules, and network routing using pfSense.
    •	Installed Proxmox VE and created Ubuntu Server virtual machines.
    •	Deployed FreeRADIUS and daloRADIUS for centralized AAA services.
    •	Deployed Snipe-IT using Docker containers on Ubuntu Server.
    •	Configured DHCP reservations and IP assignments through pfSense.
    •	Verified connectivity and communication between all virtual machines and services.
    •	Performed Linux administration, virtualization management, and network troubleshooting.



Technologies Used

    •	Proxmox VE
    •	pfSense
    •	Ubuntu Server 
    •	FreeRADIUS
    •	daloRADIUS
    •	Docker & Docker Compose
    •	Snipe-IT
    •	MySQL
    •	Linux Administration
    •	TCP/IP Networking
    •	Virtualization



Skills Demonstrated

    •	Linux System Administration
    •	Virtual Machine Management
    •	Firewall and Network Configuration
    •	DHCP and Routing
    •	Docker Container Management
    •	Authentication and Authorization Services (AAA)
    •	Asset Management Systems
    •	Database Administration
    •	Troubleshooting and System Integration

Future Improvements

    •	Implement HTTPS with SSL certificates.
    •	Integrate LDAP/Active Directory authentication.
    •	Deploy monitoring tools such as Zabbix or Prometheus.
    •	Configure VLANs and advanced firewall policies in pfSense.
    •	Deploy services using Kubernetes.
















  





 


