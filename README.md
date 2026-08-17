# Core Server Hybrid

Technical baseline and configuration repository for the Lenovo ThinkPad A475 Core Server Hybrid platform.

## Scope
- Fedora Linux 43 KDE Plasma Desktop Edition
- Linux Mint 22.3
- UEFI boot baseline
- Shared static IPv4: `192.168.1.29/24`
- Fedora and Mint are alternate-boot environments and are not operated concurrently.

## Layer model
The core layer is intentionally separated from upper-layer workloads such as gaming, daily-use software, development, containers, and VMs.

## Current baseline
**v1.1 — VALIDATED / BASELINE**

See `VERSION`, `CHANGELOG.md`, and `docs/release/RELEASE-v1.1.md`.

Full system archives are excluded from Git and retained on external/local storage.
