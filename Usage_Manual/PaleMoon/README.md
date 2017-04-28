
PaleMoon
```
图集
http://imgur.com/a/sgrpQ

下载
curl -O http://xxxx.plist

FoxyProxy Standard

  https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt
  AutoProxy Base64

Google

  https://www.google.com/ncr

Tab Utilities

  (x 老旧)https://github.com/7900ms/noname/blob/master/TUprefs.txt
  见本页的最新

鼠标摇杆手势

  Mouse Gestures Suite
  
中文网址

  https://github.com/7900ms/noname/blob/master/firefox-cn-url.md
  about:config ====> network.standard-url.escape-utf8 改为 f

内存
  about:config
  media.mediasource.webm.enabled ===> 改为 t
  启用硬件加速

SSD写入保护
  about:config
  browser.sessionstore.interval ====》 默认 15000 || 60000(六万，即60秒 1分钟)(注：15000，是15秒)
  改为 1800000 即 30分钟

  https://www.v2ex.com/t/308601

ad

  https://github.com/7900ms/noname/blob/master/ublock.txt

homepage

  https://github.com/7900ms/noname/blob/master/homepage.txt

flash
  http://www.adobe.com/software/flash/about/
  FlashDisable 插件

首选项
  主页 about:blank
  检查更新 no
  记住网站密码 no

webrtc漏洞测试
  https://haoip.cn/
  防止：
  ublock:防止 WebRTC 泄露本地IP地址

dns
  114.114.114.110
  114.114.115.110
  DNS 清理
  sudo dscacheutil -flushcache && sudo killall -HUP mDNSResponder

=

Google search link fix

Just Disable Stuff

Redirector

Firefox-网页保存MHT UnMHT

= = = 碎碎念 = = =

tab

  Tab Mix Plus (使用内建的页面恢复机制)
  https://github.com/7900ms/noname/blob/master/TMPpref.txt
  (不用 Tab Mix Plus 因为没有按钮，用于“所有新标签在后台打开”)
  (仅当 Tab Utilities 用不了时，比如在Firefox上，才可能会用到 Tab Mix Plus)


小仓鼠
  http://abowman.com/google-modules/hamster/
  http://www.protopage.com/gbrowser#老马不亏待
  自己玩自己的 http://s.codepen.io/changsj/debug/vyZaXV
  http://dwz.cn/changsjtv http://s.codepen.io/changsj/debug/NRdQRb
  
  
```


== fq 插件： FoxyProxy Standard ==

代理服务器-Direct：
 #0055E5

代理服务器-Koffee：
 127.0.0.1:1080 SOCKS5
 URL模式：(导入)

 #6BE600

 测试能在Koffee模式打开y2b

订阅模式：
 gfwlist
 https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt
 Format: AutoProxy
 Obfuscation：Base64
 代理服务器：Koffee

快速添加：
 启用
 已添加式样的代理：Koffee




https://raw.githubusercontent.com/7900ms/gfwlist/master/gfwlist.txt
https://raw.githubusercontent.com/calfzhou/autoproxy-gfwlist/trunk/gfwlist.txt
https://raw.githubusercontent.com/Long-live-gfwlist/gfwlist/master/gfwlist.txt



