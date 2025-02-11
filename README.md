# 在Windwos环境中用VS Code编译和调试ioquake3

##编译环境安装
https://ioquake3.org/help/building-ioquake3/building-ioquake3-on-windows-cygwin-mingw/

##注意
将编译器安装在E:/cygwin64
将源码下载下来放在D:/prj/ioq3-main,保证Makefile文件在D:/prj/ioq3-main/Makefile

##编译
VS Code中使用软件界面右上角三角形按钮进行编译

##调试
VS Code中使用F5调试程序客户端ioquake3.x86_64.exe
程序main函数位置在code/sys/sys_main.c中

##游戏资源下载地址
https://github.com/nrempel/q3-server/tree/master

将下载下来的游戏资源baseq3中的文件拷贝到
D:\prj\ioq3-main\build\debug-mingw32-x86_64\baseq3

运行ioquake3.x86_64.exe开始游戏
