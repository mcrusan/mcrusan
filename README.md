<!--
==============================================================================
File:        README.md
Description: Official GitHub Profile README for Marc F. Crusan — Founder & Chief Systems Architect of Crusan & Co. and Creator of AxisOS™.
Author:      Marc F. Crusan (MFC) / Crusan & Co. w/ PP & AGY (AXEL)
Date:        2026110901
Version:     v2.0.0-Silicon
==============================================================================
-->
<!-- 2026110901 (MFC/PP/AGY) Upgraded GitHub Profile README to Crusan & Co. / AxisOS™ v2.0.0-Silicon standard. -->

# Marc F. Crusan (`@mcrusan`)
### **Founder & Chief Systems Architect — Crusan & Co. // Creator of [AxisOS™](https://axisos.pro)**
> **30+ yrs exp. ([see Bio](./BIO.md)) | Former U.S. Army Infantry SSG (`11B3G`). Founder, Crusan & Co. — building AxisOS™, a distributed micro-enterprise solution. Updated: `20261109`**

[![AxisOS™: HONEST • AUDITABLE • OWNED](https://img.shields.io/badge/AxisOS%E2%84%A2-HONEST%20%E2%80%A2%20AUDITABLE%20%E2%80%A2%20OWNED-brightgreen.svg)](https://axisos.pro)
[![Architecture: Freestanding C99 & Bare-Metal Silicon](https://img.shields.io/badge/Stack-Freestanding%20C99%20%E2%80%A2%20ARM64%20%E2%80%A2%20RP2350-blue.svg)](https://axisos.pro)
[![Company: Crusan & Co.](https://img.shields.io/badge/Enterprise-Crusan%20%26%20Co.-gold.svg)](https://axisos.pro)

- **Enterprise:** **Crusan & Co.**
- **Flagship Platform:** **[AxisOS™](https://axisos.pro)** (*U.S. Trademark Application Serial No. `99878469`*)
- **Contact:** `marc@crusan.net`
- **Full Background:** **[Read BIO.md](./BIO.md)**

---

## 🛠️ What We Build at Crusan & Co.

After more than three decades building, securing, and operating mission-critical military, government, and enterprise systems—from the U.S. Army (`11B3G` Staff Sergeant, United Nations Command Security Force & War Fighter automation) to supervising multi-datacenter operations for the Alaska Legislative Affairs Agency—I founded **Crusan & Co.** to build systems the way they ought to be built: from first principles, grounded in real hardware state, with zero bloat.

Our flagship platform is **[AxisOS™](https://axisos.pro)**—a deterministic, RAM-resident operating system and embedded micro-node ecosystem engineered around **Three Inviolable Pillars**:

1. **HONEST**: Systems that know what they don't know. Every diagnostic reads live hardware registers, `/sys`, `/proc`, and physical bus state—never guesswork or synthetic placeholders.
2. **AUDITABLE**: Operations and code you can inspect at every layer—freestanding C99 utilities, direct kernel syscalls (`svc #0` / `syscall`), and deterministic `RAMGAK`-bracketed DDR4 RAM execution (`0.00%` flash wear, 100% power-pull corruption immunity).
3. **OWNED**: Hardware and software you own outright. Designed for 100% local, air-gapped sovereignty across workstations, Raspberry Pi edge appliances, and **RP2350 (Pico 2 W)** / **ESP32-S3** micro-nodes (`Cub`).

---

## 📂 Featured Public Repositories & Ecosystem Layers

| Repository | Layer | Description |
| :--- | :--- | :--- |
| **[`AxisOS_Flasher`](https://github.com/mcrusan/AxisOS_Flasher)** | Bare-Metal Tooling (`C11/POSIX`) | Deterministic pure-C RFC 1055 SLIP & ROM bootloader flasher (`axflash`) for ESP-series micro-nodes with zero Python dependencies |
| **[`AxisOS-Firmware-`](https://github.com/mcrusan/AxisOS-Firmware-)** | Embedded Silicon (`RP2350 / C11`) | Bare-metal `NO_SYS=1` lwIP cooperative scheduler & hardware watchdog firmware for Raspberry Pi Pico 2 W micro-nodes |
| **[`AxisOS-Viewer-Suite`](https://github.com/mcrusan/AxisOS-Viewer-Suite)** | Workbench Inspection (`C / GTK3`) | Dual-pane Hex, Octal, Binary, and ASCII binary inspector with hot-loadable `AxisPluginInfo` shared-object ABI |
| **[`AxisOS-AlexaPlus-Outpost`](https://github.com/mcrusan/AxisOS-AlexaPlus-Outpost)** | Voice & Edge MCP (`Python / C99 Bridge`) | Self-hosted Streamable HTTP Model Context Protocol (MCP) server uniting Alexa+, Fire TV 10-Foot HUD, Ring sensors, and the AxisOS™ Triad |
| **[`AxisOS-Nebula-Engine`](https://github.com/mcrusan/AxisOS-Nebula-Engine)** | Multi-Agent Orchestration | Sovereign multi-agent orchestrator bridging Nebius Token Factory, NVIDIA Nemotron, and the AxisOS™ RAM-resident Triad |
| **[`AxisOS-OmniCare`](https://github.com/mcrusan/AxisOS-OmniCare)** | Omnichannel Edge Control | Unified SMS, RCS, WhatsApp, and Amazon SES conversational control plane bridged to physical AxisOS™ edge nodes |

---

## 📚 *The Pocket Professor's Guide to AxisOS™* Series

Alongside our hardware appliances and software stack, **Crusan & Co.** publishes ***The Pocket Professor's Guide to AxisOS™***—a multi-volume hands-on technical series written from the workbench covering freestanding C99 system programming, bare-metal kernel architecture, RAM-resident operating systems, and sovereign local AI engineering.

---

**Copyright © 2026 Crusan & Co. (Marc F. Crusan). All Rights Reserved.**  
**AxisOS™** is a trademark of Crusan & Co. (*U.S. Trademark Application Serial No. `99878469`*).
