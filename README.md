## 惠普 暗影精灵4 黑苹果 
## Hackintosh OMEN by HP Laptop 15-dc0xxx

本EFI参考了目前最新的OpenCore文档制作，支持目前最新 Ventura Beta6 版本  
  
  
### 配置
型号  |  OMEN by HP Laptop 15-dc0xxx  
CPU   |  Intel Core i5-8300H  
GPU	    Intel UHD Graphics 630 + NVIDIA GeForce GTX1050Ti  
声卡	Realtek ALC295  
网卡    Realtek RTL8111 + Intel Wireless-AC 9560  
硬盘	LITEON SSD + KIOXIA SSD  
主板    HP 84DA  
BIOS	F.17  
系统版本 Windows11 + MacOS Ventura  

  
### 安装准备：  
1. 更新BIOS版本为最新  
2. BIOS设置中关闭安全启动  
3. 主板解锁CFGLOCK.efi：https://blog.daliansky.net/undefined.html  
  
  
### 安装教程：  
国光的黑苹果安装教程：https://apple.sqlsec.com/   
  
  
### 存在的问题：  
1. NVIDIA GeForce GTX1050Ti 已屏蔽   
    有大佬已实现在BigSur和Monterey中驱动 GTX9x0-10x0 系列独显，但目前不完善。  [参考链接](https://heipg.cn/tutorial/drive-nvidia-graphicscard-above-mojave.html)  
2. 键盘灯暂时未修复，FN+F4为睡眠。其他FN功能正常。  
    本人实在太忙，有时间再修复。[参考链接](https://github.com/daliansky/OC-little/tree/master/07-PS2%E9%94%AE%E7%9B%98%E6%98%A0%E5%B0%84%E5%8F%8A%E4%BA%AE%E5%BA%A6%E5%BF%AB%E6%8D%B7%E9%94%AE)  
3. HDMI接口 无相关硬件，无法测试  
4. 隔空投送 暂时无解，可更换Broadcom无线网卡  
5. 有其它问题，欢迎issues  
  
  
### 优化：  
开启HiDPI：https://github.com/xzhih/one-key-hidpi  
RDM：https://github.com/usr-sse2/RDM  
  
  
  
### 参考资料：  
OpenCore Post-Install：https://dortania.github.io/OpenCore-Post-Install/  
Getting Started With ACPI：https://dortania.github.io/Getting-Started-With-ACPI/  
国光的黑苹果安装教程：https://apple.sqlsec.com/  
远景论坛：https://www.pcbeta.com/  
