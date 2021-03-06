#  链表LinkTable
> 链表是一种物理存储单元上非连续、非顺序的存储结构，数据元素的逻辑顺序是通过链表中的指针链接次序实现的。
> 链表由一系列结点（链表中每一个元素称为结点）组成，结点可以在运行时动态生成。每个结点包括两个部分：一个是存储数据元素的数据域，另一个是存储下一个结点地址的指针域。
> 使用链表结构可以避免在使用数组时需要预先知道数据大小的缺点，链表结构可以充分利用计算机内存空间，实现灵活的内存动态管理。但是链表失去了数组随机读取的优点，同时链表由于增加了结点的指针域，空间开销比较大。
> 链表允许插入和移除表上任意位置上的结点，但是不允许随机存取。链表有三种类型：单向链表、双向链表以及循环链表。

## 单向链表
> 与数组相似链表也一种**线性** 数据结构,链表的每个元素其实是一个单独的对象,所有的对象都通过每个元素中的引用字段链接在一起

## 双向链表 DoubleLinkTable
> 双向链表也是链表的一种,他的每个数据点中都有两个指针,分别指向直接后继和直接前驱
> 所以双向链表从任意一个节点都还可以很方便的访问他的前驱节点和后继节点
