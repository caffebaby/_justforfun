# _justforfun
# 前言

​		“程序=数据结构+算法”，本项目旨在总结常用又经典的数据结构和算法实现，以及其在工程上的应用进行系统设计，可以作为生活工作学习的参考:)

# **数据结构**

- ## **线性结构**

  - 数组

    - 动态数组

  - 链表

    > 单向链表的翻转、排序、树形转化

    - 跳表

    > 跳表是一个随机化的数据结构，一种可以进行二分查找的有序链表。

    - 双向链表

  - 栈 

    > 栈是先进后出的数据结构

    - 单调栈

    - 数组实现栈

    - 链表实现栈

    - 队列实现栈

    - 栈实现计算器功能

  - 队列

    > 队列是先进先出的数据结构

    - 数组实现队列

    - 链表实现队列

    - 栈实现队列

    - 循环队列
    - 优先队列

- ## **树型结构**

  - 二叉树

    - AVL（自平衡二叉查找树）

    - BST（二叉搜索树）

    - 红黑树

    - huffman树

    - 堆（完全二叉树）

    - 二叉树的遍历（前序、中序、后序、层序、morris）

    - 二叉树的序列化和反序化

  - 多叉树

    - 线段树

    - B+树

    - Trie（字典树）

    - UF（并查集）

    - 多叉树的遍历

- ## **图结构**

  - 邻接表
  - 邻接矩阵

# **算法**

- ## 基本思想

  - 贪心

    > 贪心算法（又称贪婪算法）是指，在对问题求解时，总是做出在当前看来是最好的选择。也就是说，不从整体最优上加以考虑，他所做出的是在某种意义上的局部最优解。
    >
    > 贪心算法不是对所有问题都能得到整体最优解，关键是贪心策略的选择，选择的贪心策略必须具备**无后效性**，即某个状态以前的过程不会影响以后的状态，只与当前状态有关。

  - 回溯

    > 回溯算法实际上一个类似枚举的搜索尝试过程，主要是在搜索尝试过程中寻找问题的解，当发现已不满足求解条件时，就 “回溯” 返回，尝试别的路径。回溯法是一种选优搜索法，按选优条件向前搜索，以达到目标。但当探索到某一步时，发现原先选择并不优或达不到目标，就退回一步重新选择，这种走不通就退回再走的技术为回溯法，而满足回溯条件的某个状态的点称为 “**回溯点**”。许多复杂的，规模较大的问题都可以使用回溯法，有“通用解题方法”的美称

  - 分治

    > 在计算机科学中，分治法是构建基于多项分支递归的一种很重要的算法范式。字面上的解释是「**分而治之**」，就是把一个复杂的问题分成两个或更多的相同或相似的子问题，直到最后子问题可以简单的直接求解，原问题的解即子问题的解的合并。

  - 枚举

    > 枚举算法就是我们通常使用的**暴力解法**，它的核心思想就是:枚举所有的可能。
    >
    > 枚举法的本质就是从所有候选答案中去搜索正确的解,使用该算法需要满足两个条件：(1)可预先确定候选答案的数量；(2)候选答案的范围在求解之前必须有一个确定的集合。

- ## **排序**

  - 冒泡排序

  - 选择排序

  - 插入排序

  - 希尔排序

  - 归并排序（自底向上、自顶向下）

  - 快速排序（随机快排、双路快排、三路快排）

  - 桶排序

  - 基数排序

  - 计数排序

  - 堆排序

    > 排序算法的总结如下

    ![1231](https://mmbiz.qpic.cn/mmbiz_png/QCu849YTaIOOdfiakqsTRHKk9icjqQZJYuUQSibiaZIayLeW08icZul2EH9VqMgbeMN3nhfic7Wxfb8Ctk4Oicwj6DQ0Q/640?tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

- ## **查找**

  - 二分查找
  - 斐波那契查找
  - 插值查找

- ## 数学原理

  - 数论

    > 快速幂算法

  - 排列组合

  - 线性规划

- ## 计算机原理

  - 位运算

    > 汉明重量

- ## **字符串算法**

  - KMP算法

    > 字符串匹配算法

  - Manacher算法

    > 查找一个字符串的最长回文子串的线性算法

- ## **哈希算法**

  - 布隆过滤器
  - 一致性哈希

- ## **图算法**

  - 图的表示

  - 深度优先遍历

    > 单源路径、连通分量、无向图环检测、二分图检测、桥和割点

  - 广度优先遍历

    > 无权图最短路径、BFS和DFS联系、floodfill算法

  - 哈密尔顿路径和欧拉路径

    > Hierholzer 算法

  - 最小生成树

    > 切分定理、Kruskal 算法、Prim算法

  - 最短路径算法

    > Dijkstra 算法、 Bellman-Ford 算法、Floyd 算法

  - 有向图

    > 拓扑排序、Kosaraju 算法

  - 网络流

    > Ford-Fulkerson 思想、Edmonds-Karp 算法

  - 匹配问题

    > 二分图匹配算法、匈牙利算法

- ## **动态规划**

  - 背包问题
  - 线性DP
  - 区间DP
  - 树形DP
  - 状态压缩DP
  - 数位DP
  - 计数型DP

- ## 多线程算法

# **系统设计**

​		工程应用中的**系统设计**，往往就是一些算法的应用，算是对工作的一个总结吧。

- ## 缓存

  - LFU

    > Least recently used， 淘汰最不经常使用页的算法

  - LRU

    > Least frequently used， 淘汰最近最少使用页的算法

- ## 高并发

  - 分布式ID生成

    > UUID、雪花算法

- ## 社交系统

  - 设计Twitter

    > 设计一个简化版的推特(Twitter)，可以让用户实现发送推文，关注/取消关注其他用户，能够看见关注人（包括自己）的最近十条推文。你的设计需要支持以下的几个功能：
    >
    > 1.postTweet(userId, tweetId): 创建一条新的推文
    > 2.getNewsFeed(userId): 检索最近的十条推文。每个推文都必须是由此用户关注的人或者是用户自己发出的。推文必须按照时间顺序由最近的开始排序。
    > 3.follow(followerId, followeeId): 关注一个用户
    > 4.unfollow(followerId, followeeId): 取消关注一个用户
    >
    > 链接：https://leetcode-cn.com/problems/design-twitter

  
  
