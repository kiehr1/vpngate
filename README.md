# VPNGate Android Configs

## Dual Protocol Support

This repository contains OpenVPN configurations optimized for **Android**, with **both TCP and UDP** support.

### Protocol Selection

- **UDP**: Faster performance, preferred for most use cases
- **TCP**: More reliable in restrictive networks

### Directory Structure

```
├── JP/
│   ├── tcp/
│   │   ├── server_1_tcp.ovpn
│   │   └── ...
│   └── udp/
│       ├── server_1_udp.ovpn
│       └── ...
├── US/
│   ├── tcp/
│   └── udp/
└── index.json
```

### Usage

1. Download config files from your country/protocol directory
2. Import into OpenVPN for Android
3. Connect and enjoy

### Index

The `index.json` file provides metadata for all servers including:
- Protocol (TCP/UDP)
- Speed and uptime
- Hostname and IP

Generated automatically from VPNGate API.