## 暗影精灵4 黑苹果 
## Hackintosh OMEN by HP Laptop 15-dc0xxx

本EFI参考了目前最新的OpenCore文档制作，支持目前最新 Ventura Beta6 版本  
  
### 配置
型号 | OMEN by HP Laptop 15-dc0xxx（暗影精灵4） 
---- | -----  
CPU | Intel Core i5-8300H  
GPU | Intel UHD Graphics 630 + NVIDIA GeForce GTX1050Ti  
声卡 | Realtek ALC295  
网卡 | Realtek RTL8111 + Intel Wireless-AC 9560  
硬盘 | LITEON SSD + KIOXIA SSD  
主板 | HP 84DA  
BIOS | F.17  
系统版本 | Windows11 + MacOS Ventura  

  
### 安装准备：  
1. 更新BIOS版本为最新  
2. BIOS设置中关闭安全启动  
3. 主板解锁CFGLOCK.efi：https://blog.daliansky.net/undefined.html  
  
  
### 安装教程：  
国光的黑苹果安装教程：https://apple.sqlsec.com/   

  
### 存在的问题：  
1. NVIDIA GeForce GTX1050Ti：   *已屏蔽*   
        [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)项目中，已实现对 Nvidia 驱动程序的支持，目前处于Alpha版本。  [[参考链接]](https://github.com/dortania/OpenCore-Legacy-Patcher/pull/993)  
2. 键盘灯：  *暂时未修复，FN+F4为睡眠。其他FN功能正常*  
        本人较忙，有空再修复。[[参考链接]](https://github.com/daliansky/OC-little/tree/master/07-PS2%E9%94%AE%E7%9B%98%E6%98%A0%E5%B0%84%E5%8F%8A%E4%BA%AE%E5%BA%A6%E5%BF%AB%E6%8D%B7%E9%94%AE)  
3. HDMI接口：    *无相关硬件，无法测试*  
4. 隔空投送：    *暂时无解，可更换Broadcom无线网卡*  
5. 有其它问题，欢迎[issues](https://github.com/StarryNightThor/Hackintosh_OMEN_by_HP_Laptop_15-dc0xxx/issues)    
  
  
### 优化：  
开启HiDPI：https://github.com/xzhih/one-key-hidpi  
RDM：https://github.com/usr-sse2/RDM  
  
  
### 参考资料：  
OpenCore Post-Install：https://dortania.github.io/OpenCore-Post-Install/  
Getting Started With ACPI：https://dortania.github.io/Getting-Started-With-ACPI/  
国光的黑苹果安装教程：https://apple.sqlsec.com/  
远景论坛：https://www.pcbeta.com/  
特别感谢Harris Moore大佬的EFI配置参考，少走了很多弯路。https://github.com/sunmousn/OMEN-by-HP-Laptop-15-dc0xxx   

### 截图： 
<img width="1440" alt="截屏2022-08-29 23 21 40" src="https://user-images.githubusercontent.com/41841456/187238430-7333eda7-24f8-47b6-ba8c-c5af390a2e20.png">


<img width="1440" alt="截屏2022-08-29 23 24 35" src="https://user-images.githubusercontent.com/41841456/187252984-09b298b3-8204-47dd-b7d2-b2c8831c848a.png">





