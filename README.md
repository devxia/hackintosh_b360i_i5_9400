* fork自[@hackerxu](https://github.com/taizilongxu)的Repositories，根据自己的情况稍作修改

## 电脑配置：
* 主板：ASUS ROG STRIX B360-I GAMING
* CPU：Intel Core i5-9400
* 内存：科赋 DDR4 2666 8Gx2
* 硬盘：西数 SN750 黑盘 500G
* 显卡：Intel UHD Graphics 630

### 正常功能：
* UHD630 核显 DP, HDMI正常, 双屏正常, DP 4K 正常
* 板载有线网卡
* 声卡
* 睡眠唤醒
* CPU睿频
* 关机
* USB3.0 & USB3.1

### 无线&蓝牙的解决方案：
* 将主板原装的 Intel Wireless-AC 9560拆下，替换为 BCM94352Z
* 系统安装后把`EFI/CLOVER/kexts/Other/Bluetooth/DW1820A/`下面的三个文件复制到`/Library/Extensions/`下（实测DW1560目录下的文件无效）

### 不正常功能：
* HDMI 4K 分辨率只有 2K

### 参考资料
* [黑果小兵：macOS Catalina 10.15.3 19D76 正式版 with Clover 5103原版镜像[双EFI版]](https://blog.daliansky.net/macOS-Catalina-10.15.3-19D76-Release-version-with-Clover-5103-original-image-Double-EFI-Version.html)
* [黑果小兵：macOS Catalina 10.15安装中常见的问题及解决方法](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html)
