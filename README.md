明日方舟自动刷图脚本 2.0 - [主页](https://github.con/bakashigure/mrfz)
=========================

**基于Python 3.8.5 64-bit**

Description
=========================
请在windows上运行模拟器，强烈建议设置模拟器窗口大小为`1440x810`
！请以管理员权限运行，因为需要模拟鼠标点击，无论在编译器中还是exe，都需要管理员权限。！

    欢迎使用明日方舟刷图脚本 Version2.0
    这里是一些程序说明，请仔细阅读后使用。

    0.本程序会先试图遍历进程寻找包含模拟器三字的进程，如果结果为0，则会让您自行指定进程，
       如果结果为1，则会向您确认是否为游戏进程，如果结果大于1，则会让您手动指定进程.
       随后需要您指定主线/剿灭,将游戏打开到右下角为开始行动的蓝色字样，
       勾选代理作战,随后在本程序内输入您希望循环刷图的次数.
       随后在软件内确认开始后，会自动进行识别刷图.
       游戏可以放在后台，但请不要最小化.

    1.本程序需要管理员权限，这是因为模拟鼠标点击所需，您也可以通过Github上的开源代码自己在IDE中运行.
    2.本程序支持多开，请自行指定正确的进程句柄.
    3.本软件工作原理是通过对处于后台/前台的游戏窗口进行截图并识别当前处于哪一步，不会对游戏进程进行任何的操作.
    4.建议分辨率1440*810，可以缩放窗口，但过大或过小的窗口可能造成识别失败.
    6.几乎没有错误处理，所以请不要在输入数字的地方输入其他字符.
    7.目前仅支持[简体中文]的游戏内容，其他语言支持请联系我哈



    附0: 开源项目地址 https://github.com/bakashigure/mrfz  (请不要用于商业化)
    附1: 我的官服id 孭纸#416  (孭读mie)
    附2: contact::bakashigure@hotmail.com

ChangeLog
=========================

**V2.0** 2020-8-25
  - 使用图片识别来刷图

**V0.04** 2019-9
  - 使用绝对定位来刷图，失败率较高

Discussing
=========================
- [telegram](https://t.me/bakashigure)