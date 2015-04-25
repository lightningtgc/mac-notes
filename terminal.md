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
