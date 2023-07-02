# nvidia-merged

A PKGBUILD for NVIDIA merged drivers made with [vGPU-Unlock-patcher](https://github.com/VGPU-Community-Drivers/vGPU-Unlock-patcher).
Includes [vgpu_unlock-rs](https://github.com/mbilker/vgpu_unlock-rs).

Made for version 525.125.06. You may need to edit the PKGBUILD if you're using a different version - package version at least.

## Building

Build your merged driver of choice using [vGPU-Unlock-patcher](https://github.com/VGPU-Community-Drivers/vGPU-Unlock-patcher). Use `--repack general-merge`, or `--repack --lk6-patches general-merge` if using kernel >= 6.1.

Put your `NVIDIA-Linux-x86_64-<version>-merged-vgpu-kvm-patched.run` file in this directory, then follow common build steps listed in the root directory of this repository.

## Credits

This is a modified & merged version of [nvidia-utils](https://github.com/archlinux/svntogit-packages/tree/packages/nvidia-utils/trunk) and [lib32-nvidia-utils](https://github.com/archlinux/svntogit-community/tree/packages/lib32-nvidia-utils/trunk) Arch Linux packages + [nvidia-merged](https://aur.archlinux.org/pkgbase/nvidia-merged) AUR package.

This package includes [vgpu_unlock-rs](https://github.com/mbilker/vgpu_unlock-rs).
