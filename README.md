#  Bank Secure Network Design (Cisco Packet Tracer)
This project is a complete enterprise-level banking network simulation designed using Cisco Packet Tracer. It demonstrates how a real banking infrastructure is structured using VLAN segmentation, Layer 3 routing, inter-network communication, and security policies using ACLs.

The design focuses on **security, scalability, and service segregation**.

##  Network Architecture

The network is divided into multiple layers:

### 🔹 Access Layer
- End devices (PCs, laptops, printers)
 
- VLAN segmentation for departments
  
- Connected via Layer 2 switches

### 🔹 Distribution / Core Layer
- Layer 3 switches used for:
  
  - Inter-VLAN routing
  
  - Routing between departments
    
  - SVIs configured for each VLAN

### 🔹 Edge / WAN Layer
- Routers connected to distribution layer
  
- Provides external connectivity (ISP/Internet simulation)


##  Services Implemented

###  Server Infrastructure
- DHCP Server → Automatic IP assignment for multiple VLANs
  
- DNS Server → Domain name resolution (e.g. bank.local)
  
- HTTP/HTTPS Server → Web services for banking portal

  ##  Security Implementation

###  VLAN Segmentation
- Departments isolated using VLANs
  
- Reduces broadcast traffic and improves security

###  Inter-VLAN Routing
- Controlled via Layer 3 switches

###  ACL (Access Control Lists)
- Inbound ACLs applied to restrict unauthorized access
  
- Outbound ACLs used for traffic filtering
  
- Controls access between:
  
  - Users and servers
    
  - Internal departments
    
  - Sensitive banking services

##  Key Features

- Multi-VLAN enterprise design
  
- Centralized DHCP for multiple networks
  
- DNS-based service access
  
- HTTP server for banking portal simulation
  
- Secure inter-department communication
  
- ACL-based traffic control
  
- Scalable hierarchical design

##  Author
Nimra Tahir
