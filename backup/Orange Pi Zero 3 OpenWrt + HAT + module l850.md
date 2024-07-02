![IMG_4738](https://github.com/yazipu/yazipu.github.io/assets/6688947/e1d3c496-9e32-4782-b154-ae52528b24a2)

香橙派是一款开源的单板卡片电脑，新一代的arm64开发板，它可以运行Android TV 12、Ubuntu和Debian 等操作系统。 香橙派开发板（Orange Pi Zero 3）使用全志H618系统级芯片，同时拥有1GB 或1.5GB 或2GB 或4GB LPDDR4 内存。 

便宜的开发版，将操作系统烧录在TF卡中。
可刷入OpenWrt系统，作为智能路由器使用。
配合 GL-MT3000 及 USB 4g/5g 网络实现无线宽带。

Orange Pi Zero3 中文下载：
http://www.orangepi.cn/html/hardWare/computerAndMicrocontrollers/service-and-support/Orange-Pi-Zero-3.html

Orange Pi Zero3 English Download:
http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/service-and-support/Orange-Pi-Zero-3.html

OpenWrt Firmware Download 固件下载：
https://drive.google.com/file/d/1gchXIV_PwduCa-xWBxJZude_Msba3i_E
https://disk.yandex.ru/d/vYI64bq_J77CBA

Windows TF卡 OpenWrt 烧录方法：
先下载固件镜像： opiz3 23.05.2.img.img
打开【SD Card Formatter】 软件，点击format，然后关闭
完成之后打开 【Win32DiskImager】
选择映像文件：opiz3 23.05.2.img.img
点击写入，等待写入，写入成功
将写好的TF卡插入Orange PI Zero 3开机启动
连接WIFI：OPIZ 3 密码：kuotamahal
然后访问管理界面：http://192.168.1.1
管理账号：root 密码: kendal

Introduce Video:
https://youtu.be/CK220iBGlAM

wifi name: OPIZ 3
wifi pass: kuotamahal

manage url: http://192.168.1.1
username: root
password: kendal

OpenWrt 管理界面安装中文语言包

1、打开 OpenWrt 的管理界面，选择「System」>「Software」。
2、选择「Update lists」更新软件列表，等更新成功。
3、在筛选框中输入 luci-i18n-base-zh-cn 进行查找，接着选择「Install」安装语言包。
4、选择「Install」执行安装。
5、语言包安装成功，刷新页面后界面语言会替换成中文。
