# Fedora Core v1.1

- OS: Fedora Linux 43 KDE Plasma Desktop Edition
- Validation kernel: `7.1.7-100.fc43.x86_64`
- Boot: UEFI
- Default target: `multi-user.target`

Validated core services:
- NetworkManager
- sshd
- firewalld
- cockpit.socket
- libvirtd

NetworkManager:
- Method: manual
- IPv4: `192.168.1.29/24`
- Gateway: `192.168.1.1`
- DNS: `192.168.1.1`, `1.1.1.1`

Validation: gateway ping PASS; `1.1.1.1` ping PASS.

External backup artifact:
`/mnt/data/SERVER/A475-Fedora43-Core-v1.1/fedora43-core-v1.1.tar`
