# Core Server Hybrid v1.0

A documented hybrid server-core configuration project built from Lenovo ThinkPad hardware.

## Project Status

**Version:** v1.0  
**Status:** FROZEN / VALIDATED  
**Release Target:** Core Layer  
**Core Freeze:** Until further development is intentionally resumed

## Project Objective

The project establishes a stable, reusable Core Server configuration that can serve as a foundation for future server workloads.

The principle is:

> Keep the Core Layer stable. Build and experiment above the Core Layer.

Future workloads can be added without unnecessarily modifying the validated Core Layer.

## Hardware Platform

### Lenovo ThinkPad A475

The A475 serves as the primary reference platform for the desktop/server hybrid Core configuration.

Validated Core OS:

- Fedora Linux 43 KDE Plasma Desktop Edition
- Linux Mint 22.3

Both configurations were independently audited and archived as master configurations.

## Core Components

The validated Core configuration includes the following foundational components where applicable:

- UEFI boot environment
- NetworkManager
- OpenSSH
- firewalld
- Cockpit Web Console
- libvirt / QEMU-KVM virtualization layer
- Headless-capable system operation
- Stable network-based administration

## Fedora Core

**Status: COMPLETE / VALIDATED**

Documentation:

`docs/A475-Fedora43-Core-Audit.md`

Master archive:

`A475-Fedora43-Core-Master/fedora43-core-master.tar`

The Fedora master archive is maintained separately from this Git repository.

## Linux Mint Core

**Status: COMPLETE / VALIDATED**

Documentation:

`docs/A475-Mint22.3-Core-Audit.md`

Master archive:

`A475-Mint22.3-Core-Master/mint22.3-core-master.tar`

The Mint master archive is maintained separately from this Git repository.

## Repository Scope

This repository contains:

- Core configuration documentation
- Audit records
- Configuration methodology
- Project structure
- Release documentation
- Future configuration records

The repository does **not** contain the full operating-system master archives.

Large OS master archives are stored separately on local storage and backup media.

## Core Layer Policy

The validated Core Layer should be treated as a stable baseline.

Future experimentation should preferably occur above the Core Layer through:

- Virtual machines
- Containers
- Application services
- Server workloads
- Monitoring
- Storage services
- Local AI workloads
- Game servers
- Media services

Core modifications should be documented and versioned.

## Versioning

### v1.0

Initial validated Core Server Hybrid baseline.

Included:

- Fedora Linux Core
- Linux Mint Core
- Core networking
- SSH administration
- Firewall baseline
- Cockpit management layer
- Virtualization foundation
- Master filesystem archives
- Audit documentation

**Status: FROZEN**

## Validation

The Core configurations were independently audited before being declared complete.

The master archives were successfully created and stored outside GitHub.

The project is therefore considered ready for the next development phase.

---

**Core Server Hybrid v1.0 — CORE LAYER VALIDATED**

**Status: FROZEN**
