# Lenovo ThinkPad A475 — Fedora Linux 43 Core Audit

## Status

**Core Setup: TUNTAS**  
**Validation: PASSED**  
**Master Backup: COMPLETED**  
**Release Scope: Core Layer**  
**Freeze: ACTIVE for v1.0**

## System

- Device: Lenovo ThinkPad A475
- OS: Fedora Linux 43 KDE Plasma Desktop Edition
- Version: Fedora 43
- Kernel: 7.1.7-100.fc43.x86_64
- Boot Mode: UEFI
- RAM: 16 GB
- Network: Wi-Fi (`wlp3s0`)
- Server IP during validation: `192.168.1.20`

## Core Configuration Completed

- NetworkManager enabled and active
- System default target set to `multi-user.target`
- OpenSSH server enabled and active
- firewalld enabled and active
- Cockpit enabled and listening on TCP 9090
- libvirt enabled and active
- QEMU/KVM virtualization layer prepared
- No failed systemd units at final validation

## Firewall

The active Fedora firewall configuration was verified.

Enabled services included:

- Cockpit
- SSH
- DHCPv6 client
- Samba
- Samba client

## Final Validation

The final Master Backup Readiness audit verified:

1. OS identity and version
2. Kernel
3. UEFI boot mode
4. Network interfaces
5. Storage layout
6. Disk space
7. Failed systemd units
8. Package state
9. `/etc/fstab`
10. Memory and swap
11. NetworkManager
12. SSH
13. firewalld
14. Cockpit
15. libvirt

Final service validation confirmed:

- NetworkManager: **active**
- sshd: **active**
- firewalld: **active**
- cockpit.socket: **active**
- libvirtd: **active**
- Failed units: **none**

## Master Backup

Master archive:

`/mnt/data/A475-Fedora43-Core-Master/fedora43-core-master.tar`

Recorded archive size:

**Approximately 26 GB**

The archive was created using:

- `--xattrs`
- `--acls`
- `--one-file-system`

Runtime UNIX sockets were skipped by `tar`. This is expected behavior for filesystem archives and does not invalidate the master archive.

The full OS master archive is stored separately from GitHub.

GitHub stores the documentation, configuration methodology, and project records rather than the full OS image.

## Core Layer Boundary

This release establishes the **Core Layer**.

The Core Layer is intended to remain stable while future development occurs above it.

Future work may include:

- Virtual machines
- Containers
- NAS and storage services
- Media streaming
- LAN game servers
- Local AI
- Monitoring
- Application stacks
- Other server workloads

Changes to the Core Layer should be deliberate, documented, and versioned.

## Final Validation Statement

The Fedora Linux 43 Core Server Desktop configuration on the Lenovo ThinkPad A475 has been audited, validated, and archived as a reusable master configuration.

**FEDORA CORE SETUP — COMPLETE / TUNTAS**

**Core Server Hybrid v1.0 — VALIDATED**

The configuration is now considered the frozen Fedora Core reference/template for the Core Server Hybrid project.
