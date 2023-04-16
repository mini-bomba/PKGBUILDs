# mini_bomba's PKGBUILD collection

This repository contains some of my own (or edits of other) PKGBUILDs for Arch Linux.

## Table of contents

| Directory/PKGBUILD name         | Short summary                                                                                                                                                |
|---------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [nvidia-merged](/nvidia-merged) | Package script for merged NVIDIA drivers from [vGPU-Unlock-patcher](https://github.com/VGPU-Community-Drivers/vGPU-Unlock-patcher). Does not patch drivers.  |
| [nvidia-grid](/nvidia-grid)     | Package script for NVIDIA GRID drivers. Does not download drivers.                                                                                           |

## Building packages

To build a chosen package, enter the chosen directory, read that directory's README.md file and apply any build steps listed there, and finally run `makepkg -Cf`.

To install, run `pacman -U <package files>` as root
