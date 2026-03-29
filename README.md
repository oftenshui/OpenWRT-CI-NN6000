# OpenWRT-CI 
云编译OpenWRT固件，开启内核eBPF，支持DAED 内核级透明代理

官方版：
https://github.com/immortalwrt/immortalwrt.git

高通版：
https://github.com/VIKINGYFY/immortalwrt.git

LiBWrt：
https://github.com/LiBwrt/openwrt-6.x

单个连我NN6000 DAED 需要更换分区表和uboot,具体使用方法详见恩山帖子:
https://www.right.com.cn/forum/thread-8402269-1-1.html

# 固件简要说明：

固件每天早上4点自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

QUALCOMMAX系列NN6000设备，其他设备请去原项目。

# 目录简要说明：

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
