作业
~~~~~~~~~~~~~~~~~~~~~~~~~

1. 已知一个列表 a 的长度为 n, 给出下面这段代码分别在最好情况和最差情况下的时间复杂度.

::
   
   length = 1
   for i in range(n):
       j = i+1
       while j < n and a[j-1] <= a[j]:
           if length < j-i+1:
               length = j-i+1
            j++

2. 基于牛顿迭代法, 定义一个求任意实数 x 的立方根函数.