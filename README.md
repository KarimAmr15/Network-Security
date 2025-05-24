# Secure Multi-Branch Enterprise Network (Cisco Packet Tracer)

## 📌 Project Overview
This project simulates the design and configuration of a secure, scalable enterprise network for a mid-sized company using Cisco Packet Tracer. The company operates across two floors in its main branch (Egypt) and is expanding to a second branch (Lebanon). The network emphasizes layered security, connectivity, and centralized management.

## 🏗️ Project Milestones

### 🔹 Milestone 1: Initial Network Setup (Egyptian Branch)
- **Topology Design**:
  - First Floor:
    - **Server Room** with Router R1, SYSLOG server, AAA TACACS+ server, and admin access.
    - **IT Room** with Router R2, Switch S2, and IT PCs.
    - **Management Office** with one PC.
  - Second Floor:
    - **Router R3** and Switch S3.
    - **Sales, Marketing, and Meeting Room PCs**.
- **Network Configuration**:
  - OSPF routing on R1, R2, and R3 for full connectivity.
  - AAA TACACS+ server for user authentication.
  - SYSLOG server for centralized logging.
  - IOS IPS on R2 to prevent threats.
  - ACLs and security measures to block brute-force attacks and unauthorized access.

### 🔹 Milestone 2: Branch Expansion (Lebanese Branch)
- **New Branch (Lebanon)**:
  - One-floor office with Router, Core Switch (3560), IT/Management/Sales/Marketing Rooms.
  - TACACS+ and SYSLOG servers for local authentication and logging.
- **Network Integration**:
  - Fiber link between Egypt and Lebanon (30.0.0.0/24).
  - OSPF routing and site-to-site VPN between branches.
  - Brute-force protection and inter-branch ACL restrictions.
  - Port security configured:
    - **Shutdown** mode for critical devices (e.g., SYSLOG, AAA, CEO PC).
    - **Restrict** mode for all other devices.

## 🔐 Key Security Features
- AAA authentication with TACACS+ servers.
- Centralized logging via SYSLOG.
- IOS IPS deployment for intrusion prevention.
- Access Control Lists (ACLs) for traffic filtering and restrictions.
- VPN tunnel for secure branch-to-branch communication.
- Port security to limit unauthorized access.
- Login lockout after repeated failed attempts (brute-force protection).

## 💻 Tools Used
- **Cisco Packet Tracer**
- **Networking Protocols**: OSPF, ACL, VPN, AAA (TACACS+), SYSLOG


