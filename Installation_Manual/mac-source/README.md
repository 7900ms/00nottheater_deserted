
mac-source

mac-source 解决的问题是，仿制 linux source 的情况：When an interactive shell that is “not a login shell” is started, Bash reads and executes commands from ~/.bashrc, if that file exists, 结果就是用 linux 时每次写了 ~/.bashrc 之后，直接开一个新终端tab就能生效，它的效果 是等同于自动 `source ~/.bashrc` (所以linux的 大量东西都写在 bashrc 里且几乎从来用不到source命令 -)

mac默认不会source任何东西 [bash source 优先级关系](https://ruby-china.org/topics/37688)

```
改造办法：

1.
建立 ~/.bashrc

echo "#" >> ~/.bashrc

2.
nano ~/.bash_profile 写入
if [ -f ~/.bashrc ]; then . ~/.bashrc; fi
alias mac-source='source ~/.bashrc'

3.
nano ~/.zshrc 写入
if [ -f ~/.bashrc ]; then . ~/.bashrc; fi
alias mac-source='source ~/.bashrc'

4.
测试

nano ~/.bashrc 写入
alias ssss='say bobo'

打开新终端tab(无论shell是bash还是zsh)

> ssss

成功





= = = 碎碎念(脑容量回收站) = = =

1.
建立 ~/.bashrc

echo "#" >> ~/.bashrc

2.
让 ~/.bashrc 每次在新建 tab 的时候被自动索引

思路：
开机自动索引+手动索引激发
开机自动索引：
`echo "if [ -f ~/.bashrc ]; then . ~/.bashrc; fi" >> ~/.bash_profile`
手动索引激发：
`echo "alias mac-source='source ~/.bashrc'" >> ~/.bash_profile`
手动索引激发+zsh (选做)：
额外在 ~/.zshrc 里加入一句 source ~/.bash_profile

3.
像 linux 一样，所有东西写在 ~/.bashrc 里

生效：
Linux : 每次更新了 ~/.bashrc 之后，打开新的终端tab (会索引 ~/.bashrc)
mac : 每次更新了 ~/.bashrc 之后，打开新的终端tab (会索引 ~/.bashrc)
mac : 每次更新了 ~/.bashrc 之后，重启或执行 mac-source (会索引 ~/.bashrc)
```
