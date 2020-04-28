# MSI-B360M-MORTAR-HACKINTOSH
电脑硬件：i5-9600k / msi-b360m-mortar / Macmini8,1 / fenvi-bcm94360cs2

由于机箱、网卡插口位置区别，仓库中的引导文件默认启用全部USB端口；

10.15.+系统需要手动设置：Kernel/Quirks/PowerTimeoutKernelPanic为Ture（修复睡眠唤醒几秒后重启）

关于本机：简单上传一些截图，显卡(双硬解） / 声卡(麦克风+耳机自动切换） / 以太网卡 / WI-FI / 原生电源管理 / 睡眠唤醒 / iServices / 随航+隔空+Handoff / 暂时还没发现不可用功能，接近完美 。。。。。。

![image](https://github.com/Utmostmao/MSI-B360M-MORTAR-HACKINTOSH/blob/master/Screenshots/%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png)

三码配置：图中是随意填写的三码，使用前自行修改

![image](https://github.com/Utmostmao/MSI-B360M-MORTAR-HACKINTOSH/blob/master/Screenshots/%E4%B8%89%E7%A0%81%E9%85%8D%E7%BD%AE.png)

H264 / HEVC 双硬解：

![image](https://github.com/Utmostmao/MSI-B360M-MORTAR-HACKINTOSH/blob/master/Screenshots/H264:HEVC.png)

CPU和GPU共同硬解时的运行情况和OpenCore引导文件目录：

![image](https://github.com/Utmostmao/MSI-B360M-MORTAR-HACKINTOSH/blob/master/Screenshots/misc.png)

[OpenCore-Desktop-Guide](https://dortania.github.io/OpenCore-Desktop-Guide/ "台式机OpenCore指南")；
[Dortania](https://dortania.github.io/ "最佳OpenCore指南维护组织")
