# Hi, I'm Quentin 👋

I'm training as a junior system and network administrator, with a strong interest in infrastructure, virtualization, networking, automation, monitoring, backup, security and homelab operations.

I use my homelab to build practical projects around Linux, Windows Server, Proxmox, Active Directory, firewalling, cloud identity, security monitoring, backup and infrastructure automation.

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

### Zabbix Infrastructure Monitoring Lab

An infrastructure monitoring lab built with Zabbix to supervise Linux servers, Windows Server, Veeam Backup & Replication and OPNsense in a segmented Proxmox homelab.

The project includes:

* Zabbix Server 7.4 installation on Debian 13
* PostgreSQL-backed Zabbix deployment
* Linux monitoring with Zabbix Agent 2
* Windows Server monitoring with Zabbix Agent
* Nginx HTTP service check with response code validation
* Active Directory DNS TCP 53 monitoring
* DNS alert trigger tested from PROBLEM to RESOLVED
* Veeam Backup & Replication server monitoring
* Veeam repository disk usage monitoring
* Critical Veeam service triggers
* OPNsense firewall monitoring through SNMP
* Network interface, ICMP and SNMP availability monitoring
* Screenshots and technical documentation

Repository: https://github.com/quentinprevi-tech/zabbix-infrastructure-monitoring-lab

### Windows Server AD CS / PKI Homelab

A Microsoft Active Directory Certificate Services lab built on Proxmox to practice internal PKI deployment and certificate-based trust.

The project includes:

* Windows Server AD CS Enterprise Root CA
* Integration with an Active Directory domain
* Internal CA trust validation from a domain-joined Windows client
* Custom Web Server certificate template
* Linux/OpenSSL CSR generation
* Certificate issuance for a Debian/Nginx web server
* HTTPS configuration for `web01.homelab.local`
* Trusted HTTPS validation from Windows 11
* Zabbix monitoring of the CA server and CertSvc service
* Security notes and production PKI improvement considerations

Repository: https://github.com/quentinprevi-tech/windows-server-adcs-pki-lab

### Veeam Backup & Replication Proxmox Lab

A backup and disaster recovery lab using Veeam Backup & Replication 13 with Proxmox VE.

The project includes:

* Veeam Backup & Replication 13 installation on Windows Server
* Proxmox VE host integration
* Dedicated Proxmox Veeam worker appliance
* ReFS backup repository with 64K allocation unit size
* OPNsense firewall rules for segmented networks
* Successful VM backup job
* Full VM restore to a new Proxmox VM
* Application-level restore validation with Nginx
* Worker networking and firewall troubleshooting
* Screenshots and technical documentation

Repository: https://github.com/quentinprevi-tech/veeam-backup-replication-proxmox-lab

### Ansible Infrastructure Automation Lab

An infrastructure automation lab using Ansible to configure and validate Linux servers from a dedicated control node.

The project includes:

* Dedicated Ansible control node
* SSH key-based authentication
* Ansible inventory management
* Linux baseline automation
* Nginx web server deployment
* Automated service validation
* Wazuh agent configuration checks
* Idempotent playbooks with changed=0 validation
* Mermaid architecture diagram
* Screenshots and technical documentation

Repository: https://github.com/quentinprevi-tech/ansible-infrastructure-automation-lab

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

### Backup & Recovery Homelab

A practical backup and recovery lab built on Proxmox VE to validate VM backup, restore and service recovery.

The project includes:

* Proxmox VM backup with vzdump
* Backup storage validation on backup-nvme
* Restore into a separate test VM
* IP conflict prevention during restore testing
* Debian/Nginx service validation after restore
* Screenshots and technical documentation

Repository: https://github.com/quentinprevi-tech/backup-recovery-homelab

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
* Zabbix infrastructure monitoring
* SNMP monitoring
* ICMP availability checks
* HTTP service monitoring
* DNS service monitoring
* Zabbix triggers and alert validation
* Windows service monitoring
* Backup repository capacity monitoring
* Firewall monitoring with SNMP
* Wazuh SIEM and centralized log collection
* Security event detection and SIEM alert validation
* Windows Security event monitoring
* Linux/Nginx log monitoring
* Ansible automation and YAML playbooks
* Infrastructure as Code basics
* Configuration management
* Idempotent server automation
* Veeam Backup & Replication
* ReFS backup repositories
* Proxmox backup and restore
* VM backup and full restore validation
* Backup infrastructure troubleshooting
* Proxmox worker appliance deployment
* Disaster recovery validation
* Service recovery testing
* Git, GitHub and technical documentation
* Backup, recovery and validation practices

## Currently Learning

* Advanced Linux administration
* Windows Server administration
* Network administration and firewalling
* Cloud identity and hybrid infrastructure with Microsoft Entra ID
* Infrastructure automation
* Infrastructure automation with Ansible
* Infrastructure monitoring with Zabbix
* SNMP-based network device monitoring
* Monitoring and alerting
* SIEM and log analysis
* Backup infrastructure and disaster recovery
* Security best practices
* DevOps fundamentals

## Goals

My goal is to grow as a system and network administrator by building practical, real-world infrastructure projects.

I am especially interested in:

* Linux and Windows Server administration
* Proxmox and virtualization
* Networking and firewalling
* Cloud and hybrid identity
* Backup and disaster recovery
* Automation and monitoring
* Monitoring, alerting and infrastructure troubleshooting
* Secure self-hosted infrastructure
* Infrastructure documentation and troubleshooting
