# 在gdb中执行shell命令和make

## 技巧

你可以不离开gdb，直接执行shell命令，比如：

	(gdb) shell ls

或

	(gdb) !ls

这里，"!"和命令之间不能有空格。

特别是当你在构建环境(build目录)下调试程序的时候，可以直接运行make：

	(gdb) make CFLAGS="-g -O0"

## 贡献者

xmj
