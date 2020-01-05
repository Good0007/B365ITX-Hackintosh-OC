## B365ITX-Hackintosh-OC 华擎B365ITX 黑苹果OC 配置

### 主机配置
- 机箱：某宝（魔神科技)xs1机箱
- 电源：台达 400w 1u 改猫扇 
- 主板：华擎 B365I 
- CPU：9900t es
- 显卡：R9 nano
- 网卡：BCM94360CS2
- 内存：DDR4 16g x 2
- 硬盘：东芝RC500 
- CPU风扇：AR11 银欣 

### 正常功能
机型使用 iMAC 19,1 开启了核显加速，目前已99%完美
- 无线网卡：ok
- 蓝牙：ok
- R9显卡：ok
- 核显：ok (核显加速)
- 声卡：ok
- 睡眠/唤醒：ok
- CPU变频：ok

### 安装和问题参考

- 如果使用该EFI进行安装 机型必须设置为iMac 19,1，不能随意更改机型否则usb会失效！

- 可以用小兵最新的10.15.1 镜像进行安装，OC的配置文件编辑目前还没有clover智能，设置开机选中mac需要使用LogoutHook模拟nvram，然后在 偏好设置->启动磁盘 设置默认启动盘，具体操作参考xjn的博客。
 
- 镜像下载：[黑果小兵博客镜像地址](https://blog.daliansky.net/macOS-Catalina-10.15.1-19B88-Release-version-with-Clover-5098-original-image-Double-EFI-Version.html "黑果小兵10.15.1镜像")

- 常见问题：[安装常见问题](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html "安装常见问题")

- Etcher烧录工具：[Etcher烧录工具](https://www.balena.io/etcher/ "Etcher烧录工具")

### 特别鸣谢@Xjn
OpenCore相关知识和设置开机选择启动盘：[Xjn的博客](https://blog.xjn819.com/?p=543 "Xjn的博客")

### 关联CLOVER配置
[华擎B365ITX 黑苹果CLOVER](https://github.com/Good0007/B365ITX-Hackintosh-CLOVER "华擎B365ITX - CLOVER")

