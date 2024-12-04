<a href="https://github.com/MetaCubeX/ClashMetaForAndroid"><div align=center><img src="/android-phone-share-magic/images/Clash Meta.png" width="200" height="200"></div></a>

<div align="center"><h1>局域网内使用Windows通过Mihomo party共享魔法</h1></div>

<h2>本教程的前提是两台设备需要在同一局域网下，其中Windows已安装好Mihomo party，并且已有机场订阅</h2>

# 一、请再次确认所需设备在同一局域网下，电脑已安装好Mihomo party，并且已有机场订阅

# 二、打开系统代理，打开虚拟网卡，并将左边的Tun模式堆栈改为gVisor
![](/windows-share-magic/images/1.png)

# 三、打开控制面板，网络和Internet-网络和共享中心-更改适配器设置
## ！！将除了Realtk***、Microsoft***、WAN***、Bluetooth***其他的网卡禁用，比如uu加速器，Radmin，Zerotier！！
![](/windows-share-magic/images/2.png)

# 四、打开热点，发现会多了个本地链接* 10（Microsoft Wi-Fi Direct Virtual Adapter），选择Mihomo，右键属性-共享，按照下图设置，至此，其他连接该pc的热点能够科学上网
![](/windows-share-magic/images/3.png)

# 可能已知问题