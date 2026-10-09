# Cisco Enterprise Network Design — Four-Site Simulation

A Cisco Packet Tracer enterprise network simulation for a fictional company, Excel-Tec Inc., spanning **London, Leeds, Liverpool and Leicester**.

## Overview

The design documents a multi-site network with departmental segmentation and inter-site routing. The accompanying report describes the intended architecture, configuration steps, and test evidence.

## Networking concepts

- **VLANs:** VLAN 30 (Finance), VLAN 40 (Executive), VLAN 50 (Employees), and a London DMZ VLAN
- **Inter-VLAN routing:** Router subinterfaces with 802.1Q tagging
- **OSPF:** Dynamic routing between sites
- **DHCP:** Address assignment for client devices
- **ACLs:** Traffic filtering and access restrictions
- **SSH:** Remote device administration
- **WAN links:** Point-to-point links between four sites
- **Validation:** Connectivity checks and router configuration screenshots in the report

## Files

```text
Cisco-Enterprise-Network-Design/
├── README.md
├── packet-tracer/
│   └── Enterprise-Network.pkt
└── docs/
    └── Network-Design-Report.docx
```

## How to explore

1. Install Cisco Packet Tracer (requires appropriate Cisco Networking Academy access).
2. Open `packet-tracer/Enterprise-Network.pkt`.
3. Inspect the network topology and individual router/switch configurations.
4. Use Packet Tracer simulation tools or ping commands to test connectivity.
5. Consult `docs/Network-Design-Report.docx` for the design, addressing plan and documented tests.

## Notes

This is an educational **simulation**, not a production deployment. The documentation describes the proposed and configured features; results should be independently verified in Packet Tracer. Sample passwords visible in the original coursework report should not be reused in real networks.
