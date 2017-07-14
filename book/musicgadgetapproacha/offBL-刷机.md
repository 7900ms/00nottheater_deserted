
刷Rec，刷SuperSURoot，卡刷ROM(国际版波兰版,MIUI7)

注意：
- 每次刷新ROM 【得到新ROM机】 都会把SuperSURoot覆盖掉
- 每次在本ROM之内三清【得到全心机】，不会把SuperSURoot抹掉

```
实验记录

0.
移动叔叔 找红米的rec
http://bbs.ydss.cn/forum-redmi3-1.html
http://bbs.ydss.cn/thread-627967-1-1.html

1.
软件准备
参考
- MiFlash (ADB工具)
- 第三方Recovery
http://bbs.ydss.cn/thread-627967-1-1.html

2.
手机关机，开机到fastboot界面(电源键+下音量键)

3.
连电脑
用管理员身份 进入到 文件夹里，运行 一键刷入recovery(需要先解bl锁).bat
参考
http://android.tgbus.com/Android/yizhi/201412/511888.shtml

4.
Recovery设置

Recovery设置
在Rec界面内
1.进入设置(System分区可读写)
2.(尝试重启到正常系统 - “Rec界面-重启-系统”-初次会自动进入设置，再次即可自动重启到系统)
3.初次设置：会有提示 ”是否覆盖掉(立即禁止恢复)原版Recovery(是)，是否安装SuperSU(是)“

5.
进入手机系统
正常使用
(SuperSU已安装)
(刷Rec ✓ ，刷SuperSURoot ✓)

6.
成功进入Rec (电源键+上音量键，选择进入 Rec - 进入了第三方Recovery

7.
国际版ROM 卡刷包 (地区选择香港)
https://yeziting.com/441.html#G-波兰版miui
http://www.miui.com/thread-2870129-1-1.html
http://www.miui.com/thread-3926387-1-1.html

参考
找rom
http://en.miui.com/download-298.html#Redmi3
+开发版
7.6.8 dev
7.4.27 dev
MIUI8
MIUI7
6.5.26 dev(?)
+稳定版
8.1.3.0 stable
8.0.2.0 stable
MIUI8
MIUI7
7.5.2.0 stable ✓

语言 English 国家 HK

8.
重置

8.1
刷完新ROM 重刷SuperSUROOT
再次

Recovery设置
在Rec界面内
1.进入设置(System分区可读写)
2.(尝试重启到正常系统 - “Rec界面-重启-系统”-初次(刷完新ROM后的初次)会自动进入设置，再次即可自动重启到系统)
3.初次设置：会有提示 ”是否覆盖掉(立即禁止恢复)原版Recovery(是)，是否安装SuperSU(是)“

8.2
用了一段时间之后，想三清
直接进入Rec做三清(DDC+内置储存)<SuperSURoot会自动保留>

* DDC: 进入Rec界面(电源键+上音量键)会看到 “Rec界面-清除-高级清除-Dalvik+Data+Cache”


```


http://www.miui.com/thread-3926387-1-1.html
http://bbs.ydss.cn/forum-redmi3-1.html
G 如何刷入Recovery

-


