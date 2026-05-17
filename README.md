# Brinicle Linux

Minimal Debian-based Linux distribution for servers, containers, and development environments.

## Features

- Based on Debian 12 (Bookworm)
- Command-line only, no GUI
- Lightweight (~450 MB ISO)
- Pre-installed: openssh-server, curl, wget, git, vim, nano, htop, neofetch
- Multi-architecture support

## Architectures

| Architecture | File | Use Case |
|--------------|------|----------|
| amd64 | brinicle-amd64.iso | Most PCs and servers |
| arm64 | brinicle-arm64.iso | Raspberry Pi 4/5, ARM servers |
| armhf | brinicle-armhf.iso | Raspberry Pi 2/3, older ARM devices |
| i386 | brinicle-i386.iso | Legacy 32-bit systems |

## Download

Get ISO files from [Releases](https://github.com/holcc1145-byte/brinicle-linux/releases)

## Quick Start

### Write to USB (Linux/macOS)
```bash
dd if=brinicle-amd64.iso of=/dev/sdX bs=4M status=progress
