
# blog

osx 是一个 “[民用系统](https://github.com/7900ms/00nottheater_deserted/blob/master/small/系统分划and防系统污染.md)” ，它能通过接口和 “其他系统” 通信，在热插拔的连接之后。

它是一个电脑系统，其他都不重要。软件的作用是重要的，特性是不重要的。这个民用系统的（琐碎特性），其实是不重要的。一个软件的特性是不值得称道的，它的作用能干活儿就可以。(抬杠、广告、自说自话，前两者都没必要 而且说多了招人烦，最后一个还不那么讨厌)

#### 鼠标滚轮
系统偏好设置 - 自然方向 取消
time machine 关，安全和隐私 - FileVault 关，防火墙 关，键盘灯 关，f1当作功能键 ✓ ，去掉Spotlight的快捷键，音量在菜单栏

#### 输入法
输入法 [rime](https://github.com/7900ms/00nottheater_deserted/tree/master/Installation_Manual/Rime)

(输入法切换 系统设置-keyboard->shortcuts->inputSources 快捷键 ctrl+空格)

#### 触摸板
触摸板 单击打开、三指拖动选文字
Trackpad - tap to click (one finger) 打开, MissionControl三指取消
Accessibility - Mouse&Trackpad - Trackpad Options - Enable Dragging 3 finger drag

#### 开机登入
系统偏好设置 - Users & Group - login option - 自动登入

#### dock窗口最小化方式
系统偏好设置 - dock - 缩放效果(默认是神奇效果)

#### 后缀名
Finder 高级 - show all file extension
Finder 排序 Date Added, icon 视图，不用 columns 视图

#### 菜单栏 **
系统偏好设置 - 通用 - 自动隐藏菜单栏

#### 文件管理器
Finder - 边栏 - 硬盘 外置磁盘 外置设备 CD-DVD-iPod,
Finder - 边栏 - 外置磁盘

#### 触发角
[触发角](https://github.com/7900ms/00nottheater_deserted/blob/master/chufajiao/触发角.txt)

#### 防误触cmdQ
[防误触cmdQ](https://github.com/7900ms/00nottheater_deserted/blob/master/Installation_Manual/防误触cmdQ.txt)

#### 最近使用程序
[最近使用程序](https://github.com/7900ms/00nottheater_deserted/blob/master/chufajiao/recent-applications.txt)

#### 分辨率
一般上网 1152 x 720,
游戏最大 1440 x 900

-

#### App Store
AppStore - 不要自动更新(系统设置-不检查更新),允许安装任意安装包(系统设置-安全与隐私-允许任意安装包) (关闭防火墙和FileVault-默认关闭)

#### Xcode Command Line Tools
[Xcode Command Line Tools](https://github.com/7900ms/00nottheater_deserted/tree/master/Installation_Manual/Xcode-Command-Line-Tools)

#### SIP
[关闭SIP](https://github.com/7900ms/nottheater_deserted/blob/master/supplementary/360安全卫士-系统修复-SIP.txt)

#### DS_Store清理和防生成
[DS清理器 Asepsis](https://github.com/7900ms/00nottheater_deserted/blob/master/chufajiao/去掉-去掉DS_Store.txt)

#### 防止休眠
```
[caffeine, Amphetamine_MAS](https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/Amphetamine)
+XMenu
+[StartNinja 开机声音关闭](https://github.com/7900ms/00nottheater_deserted/blob/master/Installation_Manual/StartNinja关闭开机声音.txt)
+Day-O日历菜单栏
+MenubarCountdown
+鼠标右键 New File Menu
+[PresButan](https://github.com/7900ms/00nottheater_deserted/blob/master/Installation_Manual/PresButan.txt)
+[XtraFinder](https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/XtraFinder)
+[TextEdit](https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/TextEdit)
+zip (keka,TheUnarchiver)[link](https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/Keka)
+[Bartender](https://github.com/7900ms/00nottheater_deserted/tree/master/Installation_Manual/Bartender)
~~[TextWrangler](https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/TextWrangler)~~
```

mkdir -p ~/Library/Application\ Support/XMenu/Custom/Tools 把十一个东西都连进去(必须知道电脑上都安了什么软件。写一个放一个)

(下载命令 "curl -O http://xxxxx.plist" )

#### Safari
去掉 安全的文件下载后打开

[flash](https://github.com/7900ms/00nottheater_deserted/blob/master/Installation_Manual/flash.txt)

#### links文件夹
[links文件夹](https://github.com/7900ms/00nottheater_deserted/blob/master/links.txt)
把 rime 文件夹放进去 (~/Library/Rime)(必须知道电脑上都安了什么软件)
```
> mkdir -p ~/E02/links
> cd ~/E02/links
> ln -s ~/Library/Rime .
```

#### 任务栏
[uBar](https://github.com/7900ms/00nottheater_deserted/tree/master/Installation_Manual/uBar)

#### 防火墙 驱动 卸载
handsOff![防火墙](https://github.com/7900ms/00nottheater_deserted/tree/master/Installation_Manual/HandsOff)

NTFS驱动 Paragon_NTFS

AppCleaner

CleanMyMac

#### 文件管理器

[XnViewMP](https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/XnViewMP)

#### 桌面排布

[iCollections](https://github.com/7900ms/00nottheater_deserted/tree/master/Installation_Manual/iCollections)

并放到 links文件夹

(安完大约14.3G)

= = = 碎碎念 = = =

小调整：
鼠标滚动方向
dock位置
dock窗口最小化方式
Finder - Sidebar
后缀名 - Finder - show all file extension

小调整：
输入法切换方式(系统设置-keyboard->shortcuts->inputSources 快捷键 ctrl+空格)
AppStore - 不要自动更新(系统设置-不检查更新),允许安装任意安装包(系统设置-安全与隐私-允许任意安装包)

小调整：
分辨率 一般上网分辨率1152x720，游戏分辨率1140x900

小调整：
自动登入电脑 不用输入密码(系统偏好设置 － 用户和群组 － 登陆选项 自动登录)

#
