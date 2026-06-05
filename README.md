# Hi, I'm Quentin 👋

I'm training as a junior system and network administrator, with a strong interest in infrastructure, virtualization, networking, automation, monitoring and homelab operations.

I use my homelab to build practical projects around Linux, Windows Server, Proxmox, Active Directory, firewalling, cloud identity and infrastructure automation.

## Featured Projects

### Windows Server Active Directory + OPNsense Homelab

An enterprise-style virtual lab built on Proxmox VE to practice system and network administration.

The project includes:

* OPNsense firewall/router
* Segmented LAN / SERVERS / DMZ networks
* Windows Server Active Directory Domain Services
* Internal DNS
* Windows 11 domain-joined client
* Organizational Units, users and security groups
* Group Policy Objects
* Network share with AD group-based permissions
* Debian/Nginx web server in a DMZ
* WAN-to-DMZ NAT publication
* Firewall hardening and validation tests
* Proxmox snapshots and vzdump backups
* Network architecture diagram

Repository: https://github.com/quentinprevi-tech/windows-server-ad-opnsense-homelab

### Microsoft Entra ID Security Lab

A cloud and hybrid identity lab using Microsoft Entra ID, focused on IAM, least privilege, MFA baseline and hybrid synchronization.

The project includes:

* Cloud-only users, security groups and role-based access
* Least privilege role assignment (Groups Administrator, no Global Admin)
* Security Defaults and MFA baseline
* App registration with Microsoft Graph read-only permissions
* Audit and sign-in log review
* Hybrid identity with Microsoft Entra Cloud Sync
* On-premises AD OU scoped synchronization
* Password hash synchronization
* TLS 1.2 / Schannel / .NET Strong Crypto troubleshooting
* OPNsense firewall hardening for sync agent outbound traffic
* Microsoft Graph PowerShell inventory script

Repository: https://github.com/quentinprevi-tech/microsoft-entra-id-security-lab

### Wazuh SIEM Homelab

A centralized security monitoring and SIEM lab built on Proxmox VE with Wazuh.

The project includes:

* Wazuh all-in-one SIEM deployment
* Dedicated SIEM VM on the SERVERS network
* Windows Server Active Directory log collection
* Microsoft Entra Cloud Sync server monitoring
* Windows 11 endpoint monitoring
* Debian/Nginx DMZ web server monitoring
* Wazuh agents on Windows and Linux
* Windows failed logon detection
* Domain Controller audit policy configuration
* Nginx HTTP 400/404 event detection
* OPNsense firewall rules for agent communication
* Proxmox maintenance, repository fix and thinpool cleanup
* Screenshots and technical documentation

Repository: https://github.com/quentinprevi-tech/wazuh-siem-homelab

### Proxmox Discord Bot Hosting Platform

A Proxmox-based hosting platform for Discord bots, built as a portfolio project around infrastructure automation.

The project includes:

* Proxmox VE and LXC containers
* Flask customer panel
* SQLite order database
* Automated LXC provisioning
* Bash workers managed by systemd
* Stripe Checkout and webhook workflow concepts
* Prometheus dynamic service discovery
* Grafana monitoring with Node Exporter
* Security notes, screenshots and technical documentation

Repository: https://github.com/quentinprevi-tech/proxmox-discord-bot-hosting

## Skills Practiced

* Proxmox VE, LXC and virtual networking
* Linux server administration
* Bash scripting and systemd services
* Windows Server, Active Directory, DNS and Group Policy
* OPNsense firewalling, NAT and network segmentation
* Microsoft Entra ID, hybrid identity and Cloud Sync
* Microsoft Graph permissions and PowerShell
* Debian and Nginx
* Prometheus, Grafana and infrastructure monitoring
* Wazuh SIEM and centralized log collection
* Security event detection and SIEM alert validation
* Windows Security event monitoring
* Linux/Nginx log monitoring
* Git, GitHub and technical documentation
* Backup, recovery and validation practices

## Currently Learning

* Advanced Linux administration
* Windows Server administration
* Network administration and firewalling
* Cloud identity and hybrid infrastructure (Microsoft Entra ID)
* Infrastructure automation
* Monitoring and alerting
* SIEM and log analysis
* Security best practices
* DevOps fundamentals

## Goals

My goal is to grow as a system and network administrator by building practical, real-world infrastructure projects.

I am especially interested in:

* Linux and Windows Server administration
* Proxmox and virtualization
* Networking and firewalling
* Cloud and hybrid identity
* Automation and monitoring
* Secure self-hosted infrastructure
* Infrastructure documentation and troubleshooting
