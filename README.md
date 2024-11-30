### Custom Recovery Tree for the CMF Phone 1 (Tetris)

```
# SPDX-License-Identifier: Apache-2.0
```

#### The Linux Kernel binary and it's accompanying modules are provided by [Nothing Technology Limited](https://github.com/NothingOSS) under the GNU Public License


=========================================

The CMF Phone 1 (codenamed _"Tetris"_) is a mid-range smartphone from Nothing released in early 2024.
![CMF Phone 1](https://in.cmf.tech/cdn/shop/files/Engineering_aesthetics_1600x.png?v=1720164742)

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 4x ARM Cortex-A78 @ 2.50 GHz  |  4x ARM Cortex-A55 @ 2.00 GHz
Chipset | Mediatek Dimensity 7300 5G
GPU     | Mali-G615 MC2
Memory  | 6/8 GB RAM
Shipped Android Version | 14
Storage | 128 GB
Battery | Li-Po 5000 mAh, non-removable
Display | 1080 x 2400 pixels, 6.7 inches, 60/120 hz

## After you've built a custom recovery using this tree, you can enter the following command in fastboot to flash it (yes, the recovery is stored in `vendor_boot`)

## Thanks to (Siddharth)[https://github.com/sidharthify] For Base trees. ❤️


```
fastboot flash vendor_boot vendor_boot.img
```
