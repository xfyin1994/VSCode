# Json文件格式化

（1）安装``json tools``插件

（2）```Ctrl + Alt + M```进行格式化


# VSCode

 1、错误描述

在使用Visual Studio Code进行项目开发，使用快捷键Ctrl+C进行复制，鼠标光标总是变为了插入模式（很宽的光标），而且也复制不了代码。
   
 2、错误原因

   Visual Studio Code工具默认是使用Ctrl+C复制，但是安装了Vim插件，会将这个快捷键替代成其他的功能
   
   原文：https://blog.csdn.net/you23hai45/article/details/85065201 

 3、解决办法

（1）将vim插件卸载

（2）修改复制快捷键组合，使用其它快捷键替代
