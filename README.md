# azure-secure-linux-vm-lab
Deployed and hardened an Ubuntu VM in Microsoft Azure implementing RBAC, MFA, NSG policies, UFW firewall, SSH key authentication, and Azure Monitor.
## 🔐 Azure Secure Linux VM – Infrastructure & Security Lab

This project demonstrates the deployment, configuration, and hardening of a Linux virtual machine in Microsoft Azure using production-style security best practices.

The lab focuses on infrastructure provisioning, identity governance, layered security controls, and operational monitoring. It simulates real-world cloud engineering tasks including role-based access control (RBAC), multi-factor authentication (MFA) enforcement, network security configuration, host-level firewall management, and SSH key-only authentication.

This project was built to strengthen hands-on cloud engineering skills aligned with Azure infrastructure and security roles.
---

## 🏗 Architecture

- Azure Virtual Machine (Ubuntu Server 22.04 LTS)
- Azure Virtual Network
- Network Security Group (NSG)
- Azure RBAC (Role-Based Access Control)
- Microsoft Entra ID (Azure AD)
- Azure Monitor (VM Insights)
- Boot Diagnostics
- UFW (Linux firewall)
- SSH key-based authentication

---

## 🚀 Deployment Steps

### 1. Infrastructure Provisioning
- Created Resource Group
- Deployed Ubuntu Server 22.04 LTS (Gen2)
- Configured VM size (D2als_v7)
- Enabled SSH (Port 22)

### 2. Web Server Configuration
- Installed Apache2
- Enabled and started service
- Configured NSG rule to allow HTTP (Port 80)
- Verified public web access

### 3. Identity & Access Control
- Created Microsoft Entra ID user
- Assigned Reader role via Azure RBAC
- Validated least-privilege access
- Enforced MFA via Security Defaults

### 4. Monitoring & Diagnostics
- Enabled Azure VM Insights
- Enabled Boot Diagnostics
- Verified telemetry data collection

### 5. Host-Level Security Hardening
- Enabled UFW firewall
- Allowed only SSH and HTTP
- Generated SSH key pair in Cloud Shell
- Configured key-based authentication
- Disabled password authentication
- Validated secure access

---

## 🔐 Security Controls Implemented

- Defense-in-depth (NSG + UFW)
- Least privilege RBAC
- MFA enforcement
- SSH key-only authentication
- Disabled password-based SSH login
- Monitoring and diagnostics enabled

---

## 🧠 Key Skills Demonstrated

- Azure Infrastructure Deployment
- Virtual Networking & NSG Configuration
- Linux Server Administration
- SSH Key Management
- Identity & Access Management (IAM)
- Cloud Security Hardening
- Troubleshooting & Recovery

---

## 📈 Outcome

Successfully deployed and secured a cloud-hosted Linux web server in Azure using production-style security best practices and identity controls.
