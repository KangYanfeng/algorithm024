知识点总结
1.常见时间复杂度

O(1): Constant Complexity 常数复杂度

O(log n): Logarithmic Complexity 对数复杂度

O(n): Linear Complexity 线性时间复杂度

O(n^2): N square Complexity 平⽅

O(n^3): N square Complexity ⽴⽅

O(2^n): Exponential Growth 指数

O(n!): Factorial 阶乘

数组

数组用一块连续的内存空间，来存储相同类型的一组数据。
支持随机访问，时间复杂度 O(1)
插入、删除操作比较低效，为了满足连续空间需要进行数据的搬移，平均情况时间复杂度为O(n)

链表
链表内存空间可以不连续
链表类型有：单链表、双向链表、循环链表、双向循环链表等
更适合插入、删除操作频繁的场景，时间复杂度 O(1)
但是访问时需要遍历链表 ，平均情况时间复杂度为O(n)
某些情况下双向链表的访问比单链表更高效，如指定访问某个节点前面的节点
为了提高访问效率，用空间换时间的设计思路出现跳表

跳表
通过空间换时间，构建多级索引来提高查询的效率，实现了基于链表的“二分查找”
是一种动态数据结构，支持快速的插入、删除、查找操作，时间复杂度为O(nlogn)

栈
栈是一种受限的数据结构，只支持入栈和出栈操作，其入栈、出栈时间复杂度为O(1)。特点是先入后出。

队列
特点是先入先出，常见 有 优先队列，双端队列

