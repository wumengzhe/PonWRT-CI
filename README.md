# 高质量<免费>交流群

[IPQ技术讨论群](https://qm.qq.com/q/v7nMhzB4oU)

# 本地编译器

https://github.com/VIKINGYFY/OWRT-Tools.git

# 自用修改版插件

https://github.com/VIKINGYFY/packages.git

# PonWRT-CI

云编译 AN758X（Airoha AN7581 / AN7583）OpenWrt 固件。

源码：

https://github.com/Yuzhii0718/immortalwrt-mt798x-6.6-padavanonly.git

https://github.com/chasey-dev/immortalwrt-mt798x-rebase.git

# 编译矩阵

| 配置 | 源码 | 分支 | 子目标 | 设备 |
| --- | --- | --- | --- | --- |
| AN7581 | Yuzhii0718/immortalwrt-mt798x-6.6-padavanonly | openwrt-24.10-6.6 | airoha/an7581 | airoha_an7581-evb、airoha_an7581-evb-emmc |
| AN7581 | chasey-dev/immortalwrt-mt798x-rebase | 25.12 | airoha/an7581 | airoha_an7581-evb、airoha_an7581-evb-emmc |
| AN7583 | chasey-dev/immortalwrt-mt798x-rebase | 25.12 | airoha/an7583 | airoha_an7583-evb、airoha_an7583-evb-emmc |

即 CloseWRT-CI 两个源码仓中全部 AN758X 子目标的全部设备。

# 注意

固件为平台固件包，内含多个设备，请注意选择自己需要的设备固件。

# 固件简要说明

固件每周五凌晨2点（北京时间）自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

# 目录简要说明

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
