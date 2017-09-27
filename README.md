# HTML5扫雷游戏

搬砖业余学习编程，使用原生的 HTML + CSS + JavaScript 做了一个扫雷游戏，功能和windows自带的扫雷游戏一致。

在这个网页上玩，初级最好成绩10秒，中级73秒，高级375秒。

雷的布局采用随机的方式，不知道电脑上的是不是用到什么牛逼的算法，没关系，反正不会懂。

整个雷区就是通过一个table实现的，每个td采用类似于Ps软件的那种图层的方法，来进行显示控制。

大概是这么个样子，真特么丑！后续看能不能抢救过了……
![pic001](https://github.com/zhangxiaoleipy/Minesweeper/blob/master/Screenshots/pic001.PNG)

* 支持双键操作
* 如果一片是空白，将自动打开一片
* 第一步不是雷
* 有一个游戏统计功能，可以保存游戏信息。
* 有三个难度可以选择
* 有三种颜色可以选择
* 所有图标均有CSS绘制

另外本人不会英语，所以变量起名比较随意，正在学习中……
目前只是运行正常，细节上还有不少问题，后续有时间慢慢完善

仅在内核为Chromium53.0.2785.104的浏览器上运行正常，其它浏览器没有测试。
