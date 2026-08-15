# Core Server Hybrid v1.0 — Release

## Release Status

**Version:** v1.0  
**Status:** FROZEN / VALIDATED  
**Release Type:** Core Configuration Baseline

## Scope

Core Server Hybrid v1.0 establishes the validated Core Layer for the project.

The Core Layer is designed to provide a stable foundation for future server workloads while minimizing changes to the underlying system.

## Validated Platforms

### Lenovo ThinkPad A475

#### Fedora Linux 43 KDE Plasma Desktop Edition

Status:

**COMPLETE / VALIDATED**

Core functions validated:

- UEFI boot
- NetworkManager
- SSH
- firewalld
- Cockpit
- libvirt / QEMU-KVM
- systemd health
- Network connectivity
- Storage layout
- Filesystem configuration

Master archive:

`A475-Fedora43-Core-Master/fedora43-core-master.tar`

#### Linux Mint 22.3

Status:

**COMPLETE / VALIDATED**

Core system audit completed.

Master archive:

`A475-Mint22.3-Core-Master/mint22.3-core-master.tar`

## Master Backup Policy

The full operating-system master archives are intentionally stored outside GitHub.

GitHub is used for:

- Documentation
- Configuration records
- Audit results
- Version history
- Release information
- Project methodology

The master archives are maintained separately on local storage and backup media.

## Core Freeze

After validation, the Core Layer is frozen.

No unnecessary changes should be made to the validated baseline.

Future development should preferably take place above the Core Layer.

## Future Development Layer

After the Core Layer is reopened for development, planned workloads may include:

- Virtual machines
- Containers
- NAS
- Local media streaming
- LAN game servers
- Local AI
- Monitoring
- Storage and backup services
- Other server workloads

These workloads are considered part of the development/application layer and are not part of the frozen Core Layer.

## Validation Statement

The Core Server Hybrid v1.0 baseline has been audited, validated, documented, and backed up.

The resulting configuration is considered suitable as a reusable Core Server reference/template.

### FINAL STATUS

**CORE SERVER HYBRID v1.0**

**VALIDATED**

**BACKED UP**

**DOCUMENTED**

**FROZEN**
