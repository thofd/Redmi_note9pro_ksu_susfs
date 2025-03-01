# Xiaomi 10/Pro KernelSU Next SUSFS Auto-Build  
Automatically build kernels with KernelSU Next and SUSFS via GitHub Action, containing all features of n0kernel.  

> !WARNING  
> Ensure your device's Bootloader is unlocked before flashing. Verify that your device is compatible with this kernel, confirm the device codename matches the downloaded flashable ZIP, and back up the original boot partition!  

### Kernel Information  
- For Xiaomi 10/Pro with Snapdragon 865  
- Compatible with MIUI/HyperOS based on Android 10-15  
- Kernel packaged as AnyKernel3 flashable ZIP  
- Source code based on n0kernel  

 ### Flashing Guide  
1. Download the flashable ZIP matching your device model.  
2. Backup the original boot partition.  
3. Flash via TWRP or other custom recovery. Device codename and ROM compatibility will be checked before flashing.  
> If prompted "No compatible kernel for your device" or codename verification fails, double-check your device model, ROM version, and ZIP compatibility.  
4. If the device boots normally, proceed to use. If not, reflash the original boot backup to recover.  

 Device Reference Table  
 Device Name  Codename  Processor   
  
 Xiaomi 10  umi  Snapdragon 865   
 Xiaomi 10 Pro  cmi  Snapdragon 865   

### Naming Convention  
 #### Filename Format  
- `Codename-Features.zip`  
- Example: `umi-KernelSU-Next-SUSFS.zip`  
> Xiaomi 10 kernel with KernelSU Next and SUSFS  

#### Kernel Version Format  
- `Kernel Version-Author-Features-Build Date-Random Code`  
- Example: `4.19.24-CLC-K-S-20250227-z9m7c3d3`  
> Xiaomi 10 kernel with KernelSU Next and SUSFS, compiled on February 27, 2025.  
