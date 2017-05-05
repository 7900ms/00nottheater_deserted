
#### 民用系统和其他系统

民用系统 的稳定性，在于 不要和其他系统弄混

不要让其他系统入侵民用系统，有明确的分界线

#### 融合模式 - 不用

融合模式：放弃 (在 10.11.5 用官方版本软件 无法开启融合模式)

```
虚拟机设置
(既然不要融合模式)完全隔绝民用系统和虚拟机系统，仅有文件共享

Options - Sharing
Home folder only
其他都不选

Options - Applications
都不选

```

#### 设置融合模式(如果可用)

Applications - Share - share windows app with mac 取消，share mac app with windows 取消

然后 通过启动 融合模式 (10.11.5 not work coherence, even with official software)，自动开启所需要的东西


-
