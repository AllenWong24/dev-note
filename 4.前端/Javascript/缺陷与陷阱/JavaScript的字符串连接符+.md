##### 在JS循环里面，使用 + 连接字符串，导致性能问题
相当于Java的 String 和 StringBuilder，建议使用 Array 和 join 代替 + 运算符

<img src="https://wx1.sinaimg.cn/mw1024/66fd066bly1gohqyi0w7gj21xq1564bz.jpg" alt="代码" style="zoom:80%;" />
<img src="https://wx1.sinaimg.cn/mw1024/66fd066bly1gohqypp772j22161oqnfz.jpg" alt="性能" style="zoom:80%;" />