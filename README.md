# 小米10/Pro KernelSU Next SUSFS 自动构建
利用GitHub Action自动构建带KernelSU Next与SUSFS的内核，包含n0kernel的所有特性。

### 内核信息：
- 适用于骁龙865的小米10/Pro
- 适用于安卓10-15的MIUI/HyperOS
- 源码基于[n0kernel](https://github.com/jhchong94/kernel_xiaomi_sm8250_n0kernel)

### 刷入指南
1. 下载适用于您机型的刷机包
2. 备份boot
3. 使用twrp等第三方rec刷入
4. 若开机则正常使用，不开机刷回原boot即可开机

### 机型对照
| 机型名称  | 手机代号 | 处理器 |
| ------------- | ------------- | ------------- |
| 小米10  | umi  | 骁龙865 |
| 小米10 Pro  | cmi  | 骁龙865 |

> [!WARNING]
>刷入前请确认手机已经解锁Bootloader并且适用于本内核，并且已经备份原boot！
