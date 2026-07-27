# Enterprise Network Simulation

A Cisco Packet Tracer project that models routing, VLAN segmentation, NAT,
access control, and wireless connectivity across a small enterprise network.
It preserves the topology and device configurations as a completed networking study.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)](#project-status)
[![Platform](https://img.shields.io/badge/Platform-Packet%20Tracer-informational.svg)](#requirements)

## Overview

This repository provides a complete Packet Tracer topology and separate router
and switch configuration files. The simulated environment demonstrates how
multiple network services and segmentation rules work together in an enterprise
deployment.

## Features

- RIP dynamic routing between network segments.
- VLAN segmentation with access and trunk port configuration.
- Network Address Translation and access-control lists.
- Core and access-layer switch configuration.
- Wireless VLAN integration.
- Multi-device validation in Cisco Packet Tracer.

## Requirements

- Cisco Packet Tracer

Compatibility depends on the Packet Tracer version used to open the `.pkt` file.

## Contents

```text
.
├── Enterprise_Network.pkt
└── config/
    ├── Core-Switch.cfg
    ├── R0.cfg
    ├── R1.cfg
    ├── S1.cfg
    ├── S2.cfg
    ├── S3.cfg
    └── S4.cfg
```

## Usage

1. Open `Enterprise_Network.pkt` in Cisco Packet Tracer.
2. Inspect the files under `config/` for device-specific configuration.
3. Test routing, inter-VLAN communication, NAT, wireless access, and ACL behavior
   in simulation mode.

## Academic Use

This repository is shared for learning and reference. Do not submit it as
original coursework or misrepresent its authorship.

## Project Status

Complete. The topology is retained as a finished educational project and is not
under active development.

## License

Copyright 2025 Yixuan Huang

Distributed under the [MIT License](LICENSE).

## Contact

For questions or collaboration, use the contact details below or consult the
website for the latest information.

- Website: [yixuanhuang.com](https://yixuanhuang.com)
- Email: [yixnhuang@gmail.com](mailto:yixnhuang@gmail.com)
