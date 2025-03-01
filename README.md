# 小米10/Pro KernelSU Next SUSFS 自动构建
利用GitHub Action自动构建带KernelSU Next与SUSFS的内核，包含n0kernel的所有特性。


> [!WARNING]
>刷入前请确认手机已经解锁Bootloader，请确保您的设备适合刷入此内核，并检查设备代号符合您所下载的内核卡刷包，并且已经备份原boot！

### 内核信息
- 适用于骁龙865的小米10/Pro
- 适用于安卓10-15的MIUI/HyperOS
- 内核为AnyKernel3卡刷包
- 源码基于[n0kernel](https://github.com/jhchong94/kernel_xiaomi_sm8250_n0kernel)

### 刷入指南
1. 下载适用于您机型的内核卡刷包
2. 备份boot
3. 使用twrp等第三方rec刷入，刷入前会检测设备代号及ROM信息
> 如果提示没有适合您设备的内核，或设备代号检查不通过，请检查设备型号，设备ROM及卡刷包信息
4. 若开机则正常使用，不开机刷回原boot即可开机

### 机型对照
| 机型名称  | 设备代号 | 处理器 |
| ------------- | ------------- | ------------- |
| 小米10  | umi  | 骁龙865 |
| 小米10Pro  | cmi  | 骁龙865 |

### 名称解读
#### 附件名称
- 设备代号+内核特性.zip\

如：umi-KernelSU-Next-SUSFS.zip
> 小米10 内核包含KernelSU Next与SUSFS
#### 内核名称
- 内核版本+作者名称+内核特性+构建时间+随机编码\

如：4.19.24-CLC-K-S-20250227-z9m7c3d3
> 小米10 内核包含KernelSU Next与SUSFS 2025年2月27日编译
> 
