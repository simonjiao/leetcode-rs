# Solution
1. 二分删除法, 第k小的数
2. 数组总数为奇数选择(k-1), 偶数选择(k-1, k)
3. 循环结束条件
   1. 其中一个数组为空
   2. 数组均不为空，但是k==1
      1. 如果为奇数，选择数组头两个元素中的较小者
      2. 如果为偶数，选择数组前四个中较小的两个