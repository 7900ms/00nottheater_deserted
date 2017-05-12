
#### Chrome 版本

不支持拖入插件
googlechrome_51.0.2704.79.dmg，51 57

#### Chrome 的卸载

额外删除
```
rm -rf ~/Library/Application\ Support/Google/Chrome
rm -rf ~/Library/Google
```
#### Chrome 关闭自动更新
(在 Proxifier Default覆盖 的情况下 会自动更新)

小小办法(不灵)

mv ~/Library/Google/GoogleSoftwareUpdate ~/Library/Google/GoogleSoftwareUpdate-1

小小办法(不灵)
> defaults write com.google.Keystone.Agent checkInterval 0

#### 第三方插件安装

[安装第三方 chrome 插件](https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/baiduWangpan)

```
proxy

  SwitchyOmega
  curl -O https://github.com/7900ms/00nottheater_deserted/raw/master/Usage_Manual/Chrome/chrome-SwitchyOmega.bak

flash

  StopFlash Flash Blocker 由Juloo[提供](https://chrome.google.com/webstore/detail/stopflash-flash-blocker/oiiohfpnbijbgdidjfcpcljcfbmkaooi)
  
  chrome://settings/content

音乐

  声海盗(Sound Pirate) (缓存抓取)
  
  听个虾米 (对于虾米下架的歌曲，本扩展通过在QQ音乐上搜索对应歌曲进行播放)

  https://github.com/7900ms/00nottheater_deserted/blob/master/Usage_Manual/GoogleMusicOnChrome.md

广告过滤

  ublock

```

=== 碎碎念 ===

FlashControl - 不支持旧版 chrome 

https://chrome.google.com/webstore/detail/flashcontrol/mfidmkgnfgnkihnjeklbekckimkipmoe
https://github.com/n0wa11/gfw_whitelist

= = = == = = = 

```
fq
fq软件的PAC模式

插件
Proxy SwitchyOmega
uBlock origin
StopFlash Flash Blocker(Flashcontrol)

音乐
声海盗
听个虾米

百度网盘
见 aria2 (
最新版 https://github.com/acgotaku/BaiduExporter
)

办公
Office Editing for Docs, Sheets & Slides

视频去广告
QQ浏览器
视频AD叉

game
[Hamster](http://abowman.com/google-modules/hamster/)

```

```
关闭自动更新
http://www.chromium.org/administrators/turning-off-auto-updates
G google chrome disable update mac
http://wikieswan.github.io/2015/10/20/mac-shout-down-chrome-update
```


= = = 脑容量回收站 = = =

网页快照收藏 - Google Save
https://www.v2ex.com/t/359547

鼠标手势 摇杆手势 - crxMouse Chrome Gestures
