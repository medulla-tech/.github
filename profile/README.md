[English](README.md) | [Français](README.fr.md)

# Medulla RMM

Medulla RMM is an open-source IT automation and endpoint lifecycle management platform designed to automate repetitive tasks, deploy applications and operating systems at scale, and proactively manage distributed IT environments.

Built for modern IT teams, Medulla provides real-time management for complex, distributed, hybrid, and remote infrastructures using Python 3 and XMPP-based communications.

## Why Medulla?

Medulla helps IT teams simplify endpoint management by combining automation, deployment, inventory, patch management, remote access, and governance into a single platform.

Designed for organizations managing distributed infrastructures, Medulla enables IT administrators to:

- Automate repetitive IT operations
- Deploy operating systems and software at scale
- Maintain real-time visibility over endpoints
- Govern distributed environments securely
- Reduce operational complexity and total cost of ownership

---

## Supported Clients

- Windows 10 and later (including LTSC releases)
- Debian 12 (Bookworm)
- Ubuntu
- Zorin OS
- macOS 26.2 or later
- Android smartphones and tablets (via the MDM module)

**Upcoming support:** Debian 13.

## Supported Server Platform

- Debian 12 (Bookworm)

See the documentation for minimum server requirements:
https://docs.medulla-tech.io/books/installing-medulla

---

## Architecture

Medulla relies on a distributed architecture using:

- Python 3 backend services
- XMPP real-time communication
- Agent-based endpoint management
- PXE imaging infrastructure
- Apache Guacamole for remote access
- LDAP / Active Directory integration
- OIDC authentication

---

## Main Features

### Imaging & Operating System Deployment

- PXE boot support
- Multicast deployment
- System configuration builder
- Driver extraction and injection
- Bare-metal provisioning

### Package Deployment & Compliance

- Auto-packaging wizard
- Compliance management
- Automated remediation
- CVE scanning
- Scheduled deployments
- Group-based targeting
- Software lifecycle automation

### Complete Inventory & Visibility

- Real-time hardware and software inventory (XMPP-based)
- Online / offline / roaming endpoint visibility
- Network scan & device discovery
- Dynamic auto-populated groups
- Native GLPI integration

### Remote Access & Control

- SSH, RDP, and VNC access via Apache Guacamole
- Encrypted remote access — no VPN required
- Session logging and audit trail
- Secure access to remote and roaming devices

### Backup & Restore

- File-level backup (profiles and business data)
- Fast endpoint recovery
- Accelerated workstation restoration

### Patch Management (WSUS Replacement)

- Policy-based patching by endpoint group
- Real-time compliance dashboard
- Windows update governance
- Linux package updates, approved by rule
- Bandwidth optimization

### Monitoring with Probes (Reflex)

- Probes assigned to a machine, a group, an entity or the whole fleet
- Measurement frequency from five minutes upwards
- Different thresholds per entity on the same probe
- 24 shipped probes: security, system, storage, service and application
- Custom probes (sh on Linux and macOS, PowerShell on Windows)
- Alert follow-up, acknowledgement and history
- Measurement curves, machine by machine
- Email notifications
- Linux, Windows and macOS

### Self-Service Kiosk

- IT-governed application catalog
- Role and group-based access
- Pre-packaged applications
- Automated compliance integration

### Mobile Device Management (MDM)

- Android smartphone and tablet management, built on the open source Headwind MDM
- Enrollment by QR code or enrollment link
- Application and file deployment
- Security policies: kiosk mode, network restrictions, device lock
- Remote commands, messages and screen control

### Secure Remote Work

- Native encrypted tunnels
- No enterprise VPN required
- Secure governance continuity for remote endpoints

### N-Tier Governance

- Multi-level delegation (business unit, site, customer, country)
- Fine-grained permissions by endpoint scope
- Full audit trail
- Multi-tenant architecture (MSP-ready)

### Authentication & Integrations

- LDAP / Active Directory
- OIDC
- Native GLPI integration (on-premise)

---

## Quick Start

Want to test Medulla?

We provide an installable edition of Medulla, allowing you to deploy the solution directly in your own environment.

### Minimum Requirements

- Debian 12 (Bookworm)
- 8 vCPU minimum
- 16 GB RAM minimum
- Network connectivity for XMPP communications

### Installation

Request the installer and deployment guide here:

https://medulla-tech.io/en/try-medulla/

For detailed installation instructions and deployment documentation:

https://docs.medulla-tech.io/books/installing-medulla

Our team is available for technical questions and demonstration requests.

---

## Documentation

Read the full documentation:

https://docs.medulla-tech.io/

---

## Roadmap

Upcoming features and platform improvements:

- Debian 13 support
- Additional endpoint compliance capabilities
- Extended automation workflows

---

## License

Medulla RMM is distributed under the GPL license.

Commercial support contracts are available for organizations requiring:

- Technical support
- Security updates
- CVE feeds
- WSUS replacement services
- Store and repository services

---

## Community & Support

Questions, ideas, or feedback?

Open an issue or contact the Medulla team.

Website: https://medulla-tech.io/

---

## Topics

```txt
rmm
endpoint-management
it-automation
python
windows
linux
security
sysadmin
inventory
remote-management
patch-management
deployment
cve
open-source
xmpp
monitoring
mdm
```
