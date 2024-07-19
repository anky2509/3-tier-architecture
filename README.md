# Azure 3-Tier Architecture Project

This project demonstrates a 3-tier architecture deployed on Microsoft Azure, including a frontend web server, a backend server, and a SQL database. The architecture is designed to ensure scalability, security, and high availability.

## Project Components

- **Frontend Layer:**
  - Virtual Machine: Frontend-Server
  - Network Interfaces: frontend-server369_z1
  - Public IP Address: Frontend-VM-ip

- **Backend Layer:**
  - Virtual Machine: Backend-Server
  - Network Interfaces: backend-server400_z1
  - Disk: Backend-Server_OsDisk_1_fb809768afce4a958372deb548c35b9a

- **Database Layer:**
  - SQL Database: database-3-tier-architecture
  - SQL Server: database-server-3-tier
  - Private Endpoint: private-endpoint

- **Networking and Security:**
  - Virtual Network: VNET-3-TIER
  - Network Security Groups: NSG-Backend-Subnet, NSG-Frontend-Subnet

- **Monitoring and Management:**
  - Log Analytics Workspace: 3-Tier-Architecture-Workspace

## Architecture Diagram

![Azure 3-Tier Architecture](Azure_3_Tier_Architecture.pdf)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
