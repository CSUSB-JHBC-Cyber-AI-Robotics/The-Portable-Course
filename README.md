# The Portable Course

A lightweight, curated, updatable cybersecurity curriculum that lives on a USB drive.
**High-tech build. Low-tech delivery.**

Each module is a single self-contained HTML file — it opens in any browser with **no install,
no runtime, and no dependencies**, online or offline. The files are small, hand-tuned, and built
to be edited: a shared design system at the top, plain semantic content in the middle, and a small
vanilla-JavaScript block at the bottom.

## Modules

| # | Module | What it covers |
|---|--------|----------------|
| 01 | [Phases of Penetration Testing](Phases-of-Pen-Testing.html) | The pen-test lifecycle (EC-Council 5 phases, cross-mapped to PTES & NIST SP 800-115), tools & techniques per phase, ethics, and an interactive quiz. |
| 02 | [Vulhub Guide](Vulhub-Guide.html) | What Vulhub is, how to navigate it, an interactive workflow, real-world breach cards, and a saved lab-assignment tracker. |
| 04 | [Ultimate Thumb Drive Guide](Ultimate-Thumb-Drive-Guide.html) | Build a bootable IT/security toolkit (Medicat, YUMI + Kali, PortableApps, netboot.xyz, Clonezilla) with a verified, screen-by-screen Medicat walkthrough. |

## Design

All modules share one **terminal / red-team** visual theme — dark by default, monospace headers,
console accents — implemented entirely in CSS (no fonts, no images, no external assets). Re-tint the
whole course by editing the `--red` / `--green` variables in any file's palette.

## Use

Open any `.html` file in a browser. Progress in the interactive trackers and the light/dark theme
are saved locally in the browser. This repository is the source of truth; the USB is a snapshot.

---
*Educational material for authorized, lab-only use. Built for IST 4620.*
