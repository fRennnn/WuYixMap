# Data Structure
2023/1/11
-------------
写个日志，今天把总体框架完善了。
更新：添加了ESC退出的功能
修改：用户在用隐藏密码输入时，主菜单的UID号显示错误。

2023/1/12
--------------
修改：用户在注册账号时使用隐藏密码模式，第二次输入时无论输什么都错误。

2023/2/10
--------------------------
头文件加了stack和quece的库，写栈和队列就直接用就是了，省的那么麻烦。时间不多了该开工了- -
总体上决定不用gotoxy()的函数了，打印地图的时候会出错，改起来非常麻烦。
今天把地图打印和地图节点信息查询功能做了，唯一美中不足的是返回菜单时会多打印一次菜单(已修改)

2023/2/12
-----------------------------
邻接矩阵的初始化由XP完成，虽然我看不懂是怎么做的就是了
今天做的是增加修改地图节点信息的功能，因txt文件的数据错乱造成打不开的bug已修改

2023/2/15
-----------------------------
凌晨1:24 
总体功能都基本完成了，但有一个比较致命的问题就是int inputString(char *filename,string str[])不能正常的返回文件的行数，导致新写入的数据没办法更新，解决这个的话这个大作业就正式完成了。
解决了掉了这个问题了，不过又有新的问题，就是文件写入的时候会乱起一行导致数据异常，不知道该怎么做

2023/2/16
------------------------
现在是凌晨4:14
妈的终于解决掉问题了，也写完全部功能了

16:09
芜湖完工辣!
tmp.txt是中转文件，用来传输文件数据的

2023/3/3
-----------------------------
发现最短路径算法有错误
13到1能正常显示 1到13不能正常显示
用了很粗糙的方法解决了

2023/3/5
-------------------------------
原来是少循环了一次，那没事了

2023/3/8
--------------------------------
加了个注销账号的功能，妈的为什么要写5000字报告？
完善了注册账号和注销账号的UID显示问题

2023/3/14
---------------------------------
优化了UID更新问题，为什么会有人早上八点考数学捏？