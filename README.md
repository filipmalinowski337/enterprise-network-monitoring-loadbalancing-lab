# Enterprise Network Monitoring and DNS Load Balancing Lab

![Proxmox](https://img.shields.io/badge/Proxmox-VE-orange)
![GNS3](https://img.shields.io/badge/GNS3-Network%20Emulation-blue)
![BIND9](https://img.shields.io/badge/BIND9-DNS-green)
![dnsdist](https://img.shields.io/badge/dnsdist-Load%20Balancing-blueviolet)
![Cisco](https://img.shields.io/badge/Cisco-HSRP%20%7C%20OSPF-red)
![SNMP](https://img.shields.io/badge/SNMP-Monitoring-lightgrey)

This project demonstrates the implementation of an enterprise-style network infrastructure focused on:

- DNS load balancing
- High availability
- Network monitoring
- Dynamic routing
- Redundancy and failover
- Virtualized network services

The environment was built using Proxmox, GNS3, Linux DNS servers and Cisco network devices.

---

# Architecture

<img width="993" height="476" alt="topologia" src="https://github.com/user-attachments/assets/84e3a5c9-9986-4e42-8566-d93feb6f6590" />


---

# Technologies Used

- Proxmox VE
- GNS3
- BIND9 DNS
- dnsdist
- Cisco IOS
- HSRP
- OSPF
- VLAN segmentation
- DHCP
- SNMP
- MikroTik The Dude
- Linux Server Administration

---

# Infrastructure Components

## Virtualization Layer

- Proxmox VE hypervisor
- Multiple virtual machines
- Segmented virtual networking

## DNS Infrastructure

- Two BIND9 DNS servers
- dnsdist load balancer
- DNS failover validation
- DNS traffic distribution

## Routing & High Availability

- OSPF dynamic routing
- HSRP redundancy
- VLAN segmentation
- Gateway failover testing

## Monitoring

- SNMP monitoring
- MikroTik The Dude
- Network device supervision
- Service health validation

---

# Implemented Features

- DNS Load Balancing
- DNS Redundancy
- Dynamic Routing (OSPF)
- Gateway Redundancy (HSRP)
- VLAN Segmentation
- SNMP Monitoring
- DNS Failover
- Network Monitoring
- DHCP Services
- Traffic Distribution Testing

---

# Validation & Testing

The environment was tested using:

- ping
- nslookup
- failover simulations
- DNS resolution verification
- routing validation
- monitoring alerts
- network traffic analysis

---

# Screenshots

---

## DNS Load Balancing

The environment uses `dnsdist` as a DNS load balancer to distribute DNS traffic between multiple BIND9 servers using a round-robin policy.

<img width="1031" height="393" alt="sprawdzanie aktywnosci" src="https://github.com/user-attachments/assets/52c26782-ad82-492d-ae47-fe20bfbb1042" />


---

## OSPF Routing

OSPF was implemented to provide dynamic routing between network segments and improve redundancy and scalability of the infrastructure.

<img width="924" height="425" alt="routing ospf r1" src="https://github.com/user-attachments/assets/55982d8d-b962-4317-b37f-6b05cd1a3650" />


---

## HSRP High Availability

HSRP was configured to provide gateway redundancy and high availability between routers in multiple VLAN segments.

<img width="858" height="430" alt="komunikatHSRP, komunikacja miedzy routerami r2" src="https://github.com/user-attachments/assets/9d70f28a-e100-4b43-b135-a804123adeb0" />


---

## Infrastructure Monitoring (The Dude & SNMP)

The Dude was used for real-time SNMP-based infrastructure monitoring, service availability checks and network topology visualization.

<img width="837" height="483" alt="monitoringdude" src="https://github.com/user-attachments/assets/f2da83ea-f88e-4d18-a91b-2408c23e724c" />


---

# Skills Demonstrated

- Enterprise network design
- Linux administration
- DNS administration
- High availability configuration
- Dynamic routing
- Network virtualization
- Monitoring and observability
- Fault tolerance testing
- Infrastructure troubleshooting
- Network segmentation
- Infrastructure documentation

---

# Documentation

Full project documentation is available in the PDF file:

- `Enterprise_Network_Monitoring_and_Load_Balancing_Lab_Filip_Malinowski.pdf`

---

# Author

Filip Malinowski
