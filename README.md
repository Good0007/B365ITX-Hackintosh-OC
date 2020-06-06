## B365ITX-Hackintosh-OC 华擎B365ITX 黑苹果OC 配置

[我的博客同步更新](https://www.chenweikang.top/?p=846 "左手代码右手诗")

### 主机配置
- 机箱：某宝（魔神科技)xs1机箱
- 电源：台达 400w 1u 改猫扇 
- 主板：华擎 b365m-itx
- CPU：9900t es
- 显卡：R9 nano
- 网卡：DW1820A
- 内存：玖合 DDR4 16g x 2
- 硬盘：东芝RC500 
- CPU风扇：AR11 银欣 

### 已知问题
- b365itx 无法加载AppleGUC 所以核显不能拉满1.1ghz，只能到0.35的样子(影响hevc解码能力，日常使用可忽略)

### 安装和问题参考

- 配置里提供【单核显配置】、【核显+独显配置】等，请根据个人情况更名后食用，否则可能无法正常启动；

- 5600xt 5700xt 如果黑屏 ，请自行加入参数 agdpmod=pikera 

- 单核显的配置不再提供hdmi输出的支持，mac上intel核显hdmi兼容很差，而且weg官方也不再对hdmi做兼容优化了，所以请使用dp输出或者转接线（转接头/线需要主动式芯片）

- cpu有核显的务必在BOIS里设置多监视器(IGPU Multi-Monitor)为启用状态；

- 默认配置加入了1820A驱动，cs2网卡的用户请自行删除1820A驱动！

- 设置开机默认启动Mac： 偏好设置->启动磁盘 设置默认启动盘。

- 镜像下载：[黑果小兵博客镜像地址](https://blog.daliansky.net/macOS-Catalina-10.15.1-19B88-Release-version-with-Clover-5098-original-image-Double-EFI-Version.html "黑果小兵10.15.1镜像")

- 常见问题：[安装常见问题](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html "安装常见问题")

- Etcher烧录工具：[Etcher烧录工具](https://www.balena.io/etcher/ "Etcher烧录工具")

- OCC：[OC配置可视化编辑工具](https://mackie100projects.altervista.org/download-opencore-configurator/ "OCC")

### 特别鸣谢@Xjn
OpenCore相关知识和设置开机选择启动盘：[Xjn的博客](https://blog.xjn819.com/?p=543 "Xjn的博客")

### 关联CLOVER配置
[华擎B365ITX 黑苹果CLOVER](https://github.com/Good0007/B365ITX-Hackintosh-CLOVER "华擎B365ITX - CLOVER")

