# 这里主要讨论的是shell中的跳转问题

## [目录](https://github.com/shgopher/GOFamily/tree/master/%E5%85%A5%E9%97%A8%E7%AF%87/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/shell)

## 这三件事你要先搞明白

- 第一件事知道如何获取你目前所在的路径位置：`pwd`

- 如果跳转到另一个文件：cd

    - `cd~`转到home目录

    - `cd -`转到刚才的那个目录 

- 如果列举出本页面的所有的内容：ls

    - `ls -a`可以列出隐藏的文件

    > 隐藏文件意思是开头是.的文件

## 接下来要解释一下类unix系统树状目录

- 类unix最常用的有Linux各种发行版和macOS(又叫osX)

- 类unix和windows的目录是截然不同的。

- 类unix和windows的命令行也是截然不同的不能乱用。

- 大小写是敏感的

- 不要使用空格要使用-或者是.或者是_

- 一般而言-表示连字符_表示空格

## [目录](https://github.com/shgopher/GOFamily/tree/master/%E5%85%A5%E9%97%A8%E7%AF%87/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/shell)
