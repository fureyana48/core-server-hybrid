# Core Server Hybrid v1.0

A documented hybrid server-core configuration project built from refurbished ThinkPad hardware.

## Project Status

**Version:** v1.0  
**Status:** RELEASED / FROZEN  
**Release Date:** 17 August 2026

The v1.0 release represents the completed and validated **Core Layer**.

The Core Layer is intentionally frozen before higher-level services and experiments are added.

---

## Objective

Build a stable, reusable server-core foundation that can support:

- Virtualization
- Container workloads
- Web-based server administration
- Network services
- Storage services
- Local game servers
- Local AI workloads
- Future homelab experimentation

The core principle is:

> **Keep the server core stable. Experiment above the core.**

---

## Hardware Platform

### Lenovo ThinkPad A475

Two validated Core Server Desktop configurations:

- Fedora Linux 43 KDE Plasma
- Linux Mint 22.3 Cinnamon

Both configurations are designed as reusable Core Server templates.

The operating systems share the same physical machine and operate alternately rather than simultaneously.

---

## Core Architecture

### Network

- UEFI boot
- GPT storage layout
- Wi-Fi based network connectivity
- SSH enabled
- Firewall enabled
- Cockpit Web UI enabled
- Local and LAN administration supported

### Server Management

- Cockpit
- systemd
- NetworkManager
- OpenSSH
- firewalld

### Virtualization Layer

- libvirt
- QEMU/KVM

Virtual machines and higher-level services are considered **above the Core Layer**.

---

## Validation

The Core Layer was validated through:

- OS identification
- Kernel verification
- UEFI boot verification
- Network interface verification
- Storage verification
- Filesystem/mount verification
- Failed-systemd-unit audit
- Package-state verification
- NetworkManager validation
- SSH validation
- Firewall validation
- Cockpit validation
- libvirt validation
- Master backup creation

---

## Master Backups

Validated master archives were created for:

### Fedora

`A475-Fedora43-Core-Master/fedora43-core-master.tar`

### Linux Mint

`A475-Mint22.3-Core-Master/mint22.3-core-master.tar`

The master archives are retained separately from this Git repository.

The Git repository contains documentation and configuration methodology, not the full OS images.

---

## Release Policy

### v1.0 — Core Layer

Frozen configuration.

No unnecessary changes should be introduced into the Core Layer after release.

### v1.x — Controlled Core Updates

Only deliberate, documented changes to the Core Layer.

Example:

- permanent network configuration
- security hardening
- hardware-specific corrections
- backup methodology improvements

### Higher Layers

Future work will be performed above the Core Layer:

- VMs
- containers
- NAS
- media server
- game servers
- local AI
- monitoring
- additional services
- application stacks

---

## Project Philosophy

This project separates:

**Core Layer**

Stable operating-system and server foundation.

from

**Service Layer**

Applications, containers, virtual machines and experiments.

This separation allows experimentation without unnecessarily destabilizing the underlying server foundation.

---

## Status

**CORE SERVER HYBRID v1.0 — COMPLETE**

**Core configuration:** TUNTAS  
**Validation:** PASSED  
**Master backup:** COMPLETED  
**Release:** PUBLIC  
**Core freeze:** ACTIVE

Further development continues above the Core Layer.
