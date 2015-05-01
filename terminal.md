## 快捷键：


## 小技巧：

### 自动补全忽略大小写

打开终端 或者 `cd ~`

输入：
```
vi .inputrc
```

在这个文件中添加:
```
set completion-ignore-case on
set show-all-if-ambiguous on
TAB:menu-complete
```

接着按`:wq`退出并保存文件，重启终端即可

注：按Tab时会忽略大小写，如果匹配到多个路径，可按Tab进行切换

[.inputrc 相关资源介绍](http://ss64.com/bash/syntax-inputrc.html)

### 文件文件夹等类型颜色高亮显示

打开终端 或者 `cd ~`

输入：
```
vi .bash_profile
```

添加:
```
export CLICOLOR=1
export LSCOLORS=gxfxaxdxcxegedabagacad
```
`:wq` 退出并保存，重启terminal即可显示类型的颜色

还可以通过点击`preferences`在里面import一些主题或者DIY自己喜欢的颜色大小

推荐一款主题：

https://github.com/Ihavee/Monokai


## 命令相关：

### 查看日历

```
// 当前日期
cal
// 具体某一年某一月
cal 8 2015
```
