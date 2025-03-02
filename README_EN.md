# Xiaomi 10/Pro KernelSU Next SUSFS automatic build
Use GitHub Action to automatically build a kernel with KernelSU Next and SUSFS, including all the features of n0kernel.

**[中文](README.md) [English](README_EN.md)**

> [!WARNING]
> Before flashing, please make sure that the phone has unlocked the Bootloader, make sure your device is suitable for flashing this kernel, and check that the device code matches the kernel flash package you downloaded, and the original boot has been backed up!

### Kernel information
- Xiaomi 10/Pro for Snapdragon 865
- MIUI/HyperOS for Android 10-15
- The kernel is AnyKernel3 flash package
- The source code is based on [n0kernel](https://github.com/jhchong94/kernel_xiaomi_sm8250_n0kernel)

### Flashing guide
1. Download the kernel flash package for your model from the [release page](https://github.com/clcwpwqi/xiaomi10-kernelsu-susfs-kernel-build/releases), or fork and compile it yourself
2. Back up boot
3. Use third-party rec such as twrp to flash, and the device code and ROM information will be detected before flashing
> If it is prompted that there is no kernel suitable for your device, or the device code check fails, please check the device model, device ROM and flash package information
4. If it is turned on, it can be used normally. If it is not turned on, flash back to the original boot to turn on

### Model comparison
| Model name | Device code | Processor |
| ------------- | ------------- | ------------- |
| Xiaomi 10 | umi | Snapdragon 865 |
| Xiaomi 10Pro | cmi | Snapdragon 865 |

### Name Interpretation
#### Attachment Name
- Device Code + Kernel Features + File Type.zip

umi-KernelSU-Next-SUSFS.zip
> Xiaomi 10 kernel includes KernelSU Next and SUSFS, AnyKernel3 brush pack
#### Kernel Name
- Kernel Version + Author Name + Device code + Kernel Features + Build Time + Random Code

4.19.24-CLC-UMI-K-S-20250227-z9m7c3d3
> Xiaomi 10 kernel includes KernelSU Next and SUSFS compiled on February 27, 2025
>
