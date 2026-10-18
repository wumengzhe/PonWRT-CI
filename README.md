# 高质量<免费>交流群

[IPQ技术讨论群](https://qm.qq.com/q/v7nMhzB4oU)

# 本地编译器

https://github.com/VIKINGYFY/OWRT-Tools.git

# 自用修改版插件

https://github.com/VIKINGYFY/packages.git

# PonWRT-CI

云编译 AN758X（Airoha AN7581 / AN7583）PON 固件，源码为 pbs05/ponwrt（ImmortalWrt 6.18 内核 + PON 驱动 feeds）。

源码：

https://github.com/pbs05/ponwrt.git

# 编译矩阵

| 配置 | 源码 | 分支 | 子目标 | 设备 |
| --- | --- | --- | --- | --- |
| AN7581 | pbs05/ponwrt | master | airoha/an7581 | an7581.mk 全部 19 个设备（EVB×3、Gemtek×2、Nokia Valyrian、Fiberhome HG5382A/HG5585F 系列×4、ZNXT×2、UnionMan、H3C、Nokia XG-040G-MD/MD-USB-SFP/TF、Quantum Q1000K） |
| AN7583 | pbs05/ponwrt | master | airoha/an7583 | an7583.mk 全部 4 个设备（EVB×2、Nokia XG-040G-MF/MF-UBI） |

即 pbs05/ponwrt 全部 AN758X 子目标的全部设备。PON 相关包（kmod-airoha-xpon、kmod-airoha-en7572、airoha-ponctl、airoha-pond 等）随设备 DEVICE_PACKAGES 自动编入，无需额外勾选。

# 注意

固件为平台固件包，内含多个设备，请注意选择自己需要的设备固件。

# 固件简要说明

固件每周五凌晨2点（北京时间）自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

# 目录简要说明

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
