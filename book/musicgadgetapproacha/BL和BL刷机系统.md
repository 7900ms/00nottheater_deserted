
BL刷机系统：

```
实验记录


1.
电脑准备
进入windows的测试模式
参考
http://bbs.xiaomi.cn/t-12700804
http://www.miui.com/thread-4210326-1-1.html
bcdedit /set testsigning on

2.
软件准备
- x小米助手(官方版,启动一次顺利安装本手机的驱动)
- 高通9008驱动
- MiFlash
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
adb devices
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





-
