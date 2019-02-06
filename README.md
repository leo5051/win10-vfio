# leo5051's virtual gaming machine

## Hardware:
* `CPU`: Intel Core i7-7700K
* `Motherboard`: MSI Z270 SLI PLUS (MS-7A59)
* `Host GPU`: Intel HD Graphics 630
* `Guest GPU`: Nvidia GeForce GTX 970
* `Guest USB`: Renesas Technology Corp. uPD720202 USB 3.0 (for keyboard/mouse/gamepad)
* `RAM`: 32GB (2x16 Samsung DDR4 M378A2K43BB1-CPB)

## Configuration:
* `Host Kernel`: Kernel version Linux 4.xx (No ACS override patch).
* Using `libvirt QEMU/KVM with OVMF`.
* `Host OS`: Gentoo Linux
* `Guest OS`: Windows 10 Pro
* VM gets dedicated 16GB RAM.
* CPU pinning increased performance considerably.
