# The Portable Course

A lightweight, curated, updatable cybersecurity curriculum that lives on a USB drive.
**High-tech build. Low-tech delivery.**

Each module is a single self-contained HTML file — it opens in any browser with **no install,
no runtime, and no dependencies**, online or offline. The files are small, hand-tuned, and built
to be edited: a shared design system at the top, plain semantic content in the middle, and a small
vanilla-JavaScript block at the bottom.

Two classes share the drive:

- **IST 4910 — Enterprise Networking.** Build and defend a fictional business on Proxmox.
- **IST 4620 — Ethical Hacking.** Pen-test lifecycle, hands-on CVE practice, portable toolkit.

Open [index.html](index.html) to land on the class picker.

## Modules

### IST 4910 — Enterprise Networking

| # | Module | What it covers |
|---|--------|----------------|
| 01 | [Dog Park Project Guide](Dog-Park-Project-Guide.html) | A Socratic field guide for the eight-VM build. Zones, DHCP & routing, firewall rule logic, AD/DNS join (Windows + RHEL via realmd/sssd), the storefront, and surviving pen-test week. Phased self-check tracker saves in the browser. |

### IST 4620 — Ethical Hacking

| # | Module | What it covers |
|---|--------|----------------|
| 01 | [Phases of Penetration Testing](Phases-of-Pen-Testing.html) | The pen-test lifecycle (EC-Council 5 phases, cross-mapped to PTES & NIST SP 800-115), tools & techniques per phase, ethics, and an interactive quiz. |
| 02 | [Vulhub Guide](Vulhub-Guide.html) | What Vulhub is, how to navigate it, an interactive workflow, real-world breach cards, and a saved lab-assignment tracker. |
| 03 | [Ultimate Thumb Drive Guide](Ultimate-Thumb-Drive-Guide.html) | Build a bootable IT/security toolkit (Medicat, YUMI + Kali, PortableApps, netboot.xyz, Clonezilla) with a verified, screen-by-screen Medicat walkthrough. |

## Design

The landing page uses the **CSUSB Coyote-Blue + sunrise-gold** palette with an inline-SVG San
Bernardino Mountains hero. The 4620 modules share a **terminal / red-team** dark theme by default;
the 4910 Dog Park guide shares the same base system tuned to a blue/gold infrastructure feel.
Everything is implemented in CSS — no fonts, no images, no external assets. Re-tint by editing the
palette variables at the top of any file.

## Use

Open any `.html` file in a browser. Progress in the interactive trackers and the light/dark theme
are saved locally in the browser. This repository is the source of truth; the USB is a snapshot.

---
*Educational material for authorized, lab-only use. Built for IST 4910 and IST 4620.*
