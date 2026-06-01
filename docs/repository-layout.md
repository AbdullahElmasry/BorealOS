# Repository Layout

This document defines the intended BorealOS repository structure.

BorealOS is a Debian-based Linux distribution planned to ship as a bootable ISO
image with `aurorad` included out of the box.

## Top-level directories

```text
BorealOS/
├── docs/              Project documentation, architecture notes, build plans, and roadmaps
├── build/             ISO/image build configuration
├── packages/          BorealOS-owned Debian package sources
├── configs/           Default system, desktop, and aurorad configuration files
├── .assets/           Logos, wallpapers, banners, themes, and branding assets
├── tools/             Helper scripts for development, testing, and release work
├── external/          Vendored third-party source code only when necessary
└── src/               Source code maintained by BorealOS