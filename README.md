<img width="1400" height="300" alt="logo" src="https://github.com/user-attachments/assets/c5b02c95-2ab8-416d-886f-b0db1ffe58fb" />
# 🚀 My Personal Arch Linux Installation Guide & Script

A streamlined, custom Arch Linux installation setup tailored for performance, minimalism, and a modern tiling window manager experience.

---

## 📌 Overview

This repository contains my personal installation guide and automated scripts for setting up a fully functional, highly optimized **Arch Linux** environment from scratch.

* **OS:** Arch Linux
* **WM/Compositor:** [Hyprland](https://hyprland.org/) (Wayland)
* **Shell:** Zsh / Bash
* **Target Audience:** Intermediate to advanced Linux users who want a clean, minimalist system setup.

---

## 🛠️ System Prerequisites

Before starting the installation process, make sure you have:

- [x] A bootable USB drive with the latest Arch Linux ISO.
- [x] An active internet connection (Wi-Fi via `iwctl` or Ethernet).
- [x] UEFI mode enabled in your BIOS/UEFI settings.
- [x] Secure Boot disabled.

---

## 📥 Quick Start & Usage

1. **Boot into the Arch ISO** and establish an internet connection:
   ```bash
   iwctl
   # Station wlan0 connect YOUR_SSID
