# Core Recovery Procedure

1. Identify the correct target disk/filesystem.
2. Verify the archive checksum when available.
3. Preserve user data before destructive restoration.
4. Restore only the intended OS filesystem.
5. Validate UEFI boot and filesystem mounts.
6. Validate NetworkManager and `192.168.1.29/24`.
7. Validate gateway and internet reachability.
8. Review `systemctl --failed`.
9. Do not deploy upper-layer workloads until baseline validation passes.

Do not blindly extract a full-system archive onto an arbitrary mounted root.
