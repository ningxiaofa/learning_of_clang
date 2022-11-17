### [Make 命令教程(https://www.ruanyifeng.com/blog/2015/02/make.html)

### make命令/软件
并不仅仅只能用于软件编译安装

Make是最常用的构建工具，可以用于除了编译之外的构建任务,

在make/other中，执行make命令总是报错：
```
mac Makefile:2: *** missing separator.  Stop.
```

最后找到原因:
还是tab缩进的问题，vscode上也是tab输入的，而且看着是没问题的， 结果使用vim打开，发现不对
直接使用vim进行编辑，解决。

之后重新使用vscode进行编辑，也正常了 {有可能这是vscode的bug} TBD

