命令窗口是EE内部集成的一个小部件，主要目的是对外部工具的输入进行操作。有时候一些外部工具会提示用户输入，这时候可以调出命令窗口，输入即可（输出窗口不可进行输入操作）。

除此之外，命令窗口还有一些其它的功能。

* 查找替换
* 执行程序

## 查找替换
* !exe 是直接执行这个程序
* :exe 是把输入的命令当成一个命令程序执行并捕获其输出
* cls 清除输出窗口的文本
* help打开在线帮助
* /反斜线之后的输入，会按照查找来进行， 按住`Enter`是查找下一个，`Ctrl+Enter`是查找上一个， 比如:/name
* /find/replace/ 进行查找替换

未来还会集成`awk`命令。
