
BL刷机系统：

BootLoader是在操作系统内核运行之前运行的一段小程序。其实Bootloader就相当于手机的bios，通过这段小程序，进行硬件初始化，获取内存大小信息等，调整手机到适配状态。所以Bootloader是很重要的，如果bootloader不能正常加载，手机就是砖头一个，无法正常启动和使用。然后以用户的按键组合进入到某种启动模式，如所熟知的电源键和音量键的组合，可以进入到Recovery、Fastboot 或者正常开机。

值得注意的是，Bootloader被锁的手机必须要破解才能刷第三方rom。如果不破解bootloader，就无法初始化手机硬件，手机也就无法使用。
而在我们接触刷机时，Bootloader、Fastboot已经混合为一个概念;我们只需了解的是，对部分机型，有Bootloader解锁以及对应驱动。

https://www.qiuqiuweb.cn/archives/53

```
实验记录

0.
miui开发版6.1.7以上和稳定版7.1以上的版本中加入了BL锁
旧ROM自带旧Rec https://read01.com/2K7Q3L.html
(红米手机3 上市时间：2016年01月， MIUI6)

1.
电脑准备
进入windows的测试模式
参考
http://bbs.xiaomi.cn/t-12700804
http://www.miui.com/thread-4210326-1-1.html
bcdedit /set testsigning on

2.
软件准备
- 小米助手(官方版,启动一次顺利安装本手机的驱动)
- 高通9008驱动
- MiFlash (ADB工具)
参考
http://bbs.xiaomi.cn/t-12700804
http://www.miui.com/thread-3845129-1-1.html
http://www.xiazaizhijia.com/soft/97205.html#高通9008驱动
http://bigota.d.miui.com/tools/MiPhone20151028.exe#实际上感觉没带高通驱动


3.
手机旧版ROM(线刷包,不带锁的)准备
参考
稳定版 线刷包 V7.1.1.0 (x)
开发版 线刷包 V6.3.17
http://www.miui.com/thread-6289533-1-1.html

4.
刷入旧版ROM
(解锁原理：直接刷入旧ROM,它内置Rec)

参考
http://tieba.baidu.com/p/4423852926
fastboot oem edl (开机到fastboot模式之后 输入这个 ✓)


4.1
http://www.miui.com/thread-3845129-1-1.html#端口COM
not work

4.2
http://www.miui.com/thread-5928262-1-1.html
http://tieba.baidu.com/p/4423852926
fastboot oem edl
not work

4.3【成功】
http://bbs.xiaomi.cn/t-12700804#解BL锁-高通模式9008刷机
adb devices (允许开发者选项-USB调试模式)
adb reboot edl


ref
总结 http://www.miui.com/thread-4210326-1-1.html

5.
重启手机
测试 Rec(不再有BL锁) (电源键+上音量键)
测试 Fastboot (电源键+下音量键)


6.
检查旧的ROM


7.
卡刷任何国际版开发版ROM





```

关键词：高通模式9008刷机

关键材料：
无锁的线刷包

参考
http://bbs.xiaomi.cn/t-12700804

WARNING---
- 不带BL锁的ROM
-> www.miui.com/thread-7253103-1-1.html
->> http://www.miui.com/thread-6289533-1-1.html
->>> http://www.miui.com/thread-3845129-1-1.html # 没提到解锁
->>>> http://bbs.xiaomi.cn/t-12700804#解BL锁

= = =

解锁：

设置>>更多设置>>开发者选项>>设备解锁状态>>点击“绑定账号和设备”

http://www.miui.com/unlock/

info:
- 不解锁时，只能刷入 大陆版小米最新稳定版 or 开发版
- 不解锁时，无法刷入国际版rom，无法取得root权限
- 不解锁时，会自动更新到最新ROM
- 不解锁时，无法刷入rec

暴力解锁原理：刷老系统，然后 没锁，然后自由，然后刷新系统 [-](http://tieba.baidu.com/p/4423852926#G-解锁-秒解-小米)

解锁之后：刷入Rec, 刷入SuperSU(放弃解锁后自带的root), 刷入新ROM [-](http://www.miui.com/thread-3926387-1-1.html)



-
