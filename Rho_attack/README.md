代码解析
=

__RhoAttack函数__
___________________

首先创建一个数组来存储Hash值

进行一个循环，在每次循环中选取一个随机数进行SM3加密，之后观察其Hash值是否在结果数组中，若在，的攻击成功。
若不在，则将其存入数组，在进行下次循环，直到攻击成功为止。

运行截图
=

![image](https://github.com/CLiangH/Picture/blob/main/rho.png)
