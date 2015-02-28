# DLSlideView

DLSlideView对常见的顶部Tab页点击、滑动分页做了封装。
它使用基于ViewController的container特性（而不是scrollview）来管理各个子页面，保留原始的系统消息，没有隐患。
同时内存模型更优于使用scrollview的方式，理论上可以支持无限分页。

可自定义标签栏：
![demo-1](./Images/demo1.jpg)

类似网易新闻，支持无限页面：
![demo-2](./Images/demo2.jpg)