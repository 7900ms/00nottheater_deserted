
面对病毒：
[360安全卫士 - 病毒](http://www.360.cn/qiaozha/index.html)

#### windows

关闭端口 [教程](http://bbs.360.cn/thread-14973844-1-1.html)
```
1
关闭445、137、138、139端口，关闭网络共享
http://abin103.iteye.com/blog/400691
http://jingyan.baidu.com/article/d621e8da0abd192865913f1f.html

自启动‘IPSEC 服务’

2
策略组编辑器 (Group Policy Editor) gpedit.msc
http://jingyan.baidu.com/article/7e44095337e4112fc1e2ef76.html
win7 的策略组编辑器 gpedit.msc
https://zhidao.baidu.com/question/129968700.html

3
windows自带的防火墙
https://www.sohu.com/a/140337306_606775
http://bbs.360.cn/thread-14973844-1-1.html

```
```
> netstat -ano
控制面板-管理工具-服务，
控制面板-管理工具，打开“本地安全策略”，选中“IP 安全策略，在本地计算机”

```
#### 路由器

UPnp功能必须使用计算机的端口来进行工作，取得控制权的攻击者，还有可能利用这些端口，达到攻击者的目的
G 路由器 端口 关闭 UPnP
http://itbbs.pconline.com.cn/network/12473184.html

#### 官方补丁

(Microsoft Windows SMB 服务器安全更新)

http://www.iplaysoft.com/wannacry.html

http://www.appinn.com/windowsxp-kb4012598-x86-custom/


#### WIN7

win7 的策略组编辑器 gpedit.msc

360安全卫士吧.里面常用→电脑体检项.下面就有组策略是否禁用选项.显示是已禁用你就开启一下就OK

G WannaCry windows patch

https://blogs.technet.microsoft.com/msrc/2017/05/12/customer-guidance-for-wannacrypt-attacks/

https://support.microsoft.com/en-us/help/2696547/how-to-enable-and-disable-smbv1-smbv2-and-smbv3-in-windows-and-windows-server



