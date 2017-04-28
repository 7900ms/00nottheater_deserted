
Sublime Text 3
```

== 何时用 ==

在 写 exe 的时候用


== 最后一个好的版本 ==

SublimeTextBuild3114
xSublimeText3_3126


== 禁用更新 ==

改 host

> sudo nano /etc/hosts
# 防止软件更新
127.0.0.1 www.sublimetext.com

安装
cmd+shift+p  pci

ctrl+`

import urllib.request,os,hashlib; h = 'df21e130d211cfc94d9b0905775a7c0f' + '1e3d39e33b79698005270310898eea76'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by) 

https://packagecontrol.io/installation

插件
BracketHighlighter
Emmet

阻止更新
ST - Preferences - Browse Packages ...
~/Library/Application Support/Sublime Text 3/Packages/PyV8/osx-p3/config.json


Preferences - setting - user

{
  "color_scheme": "Packages/Color Scheme - Default/Mac Classic.tmTheme",
  "font_size": 16,
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "highlight_line": true,
  "default_line_ending": "unix",
  "ignored_packages":
  [
    "Vintage"
  ],
  "trim_trailing_white_space_on_save": true,
  "update_check": false
}

Licence

```
----- BEGIN LICENSE -----
Affinity Computer Technology
10 User License
EA7E-909026
D64472BD FA040F1B 20F23C0D 114D57E4
AF4DDFDC A3FDDA29 00319FA1 91EE46D2
B3210738 54154723 F12511D6 950F839D
C5A83395 76EAEC5B FC25B644 9802A931
28A62A8C 9483EC49 E28E1A3B 997FA0FA
678ED4D3 2F4C2645 8E88274C 8AC599C2
F2D578D3 DF19037B 544F5304 18F3F196
6F1AC83E 2E1FCE1D BA74F528 1340A09F
------ END LICENSE ------
```



= = = 碎碎念 = = =
= =

插件

BracketHighlighter
EJS
Emmet
Jade
(Boxy theme)(ST3 can't support emoji. for emoji, use EmojiEditor )

= = 

🌽, 🐮, 🐔
emoji (无法实现。不如用别的编辑器)
https://www.tjvantoll.com/2016/06/10/emoji-and-coding/

= = = 碎碎念 = = =

不要 xSublimeText3_3126 和之后的

Licence

https://www.v2ex.com/t/345827

https://wikileaks.org/ciav7p1/cms/page_9535650.html
```
