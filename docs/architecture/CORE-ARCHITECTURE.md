# Core Architecture

```text
Hardware
  └─ UEFI / GPT baseline
      ├─ Fedora Core v1.1
      └─ Mint Core v1.1
          └─ Upper Layer
              ├─ Daily
              ├─ Gaming
              ├─ Development
              ├─ Containers
              └─ Future workloads
```

## Network identity
- IPv4: `192.168.1.29/24`
- Gateway: `192.168.1.1`
- DNS: `192.168.1.1`, `1.1.1.1`

The identical address is intentional because Fedora and Mint are alternate-boot environments. Do not operate both simultaneously with the same address.
