# JAVA数据结构

- 数组
- 链表
- 堆
- 栈
- 队列
- 树
- 图
- 
- 枚举（Enumeration）
- 位集合（BitSet）
- 向量（Vector）
- 栈（Stack）
- 字典（Dictionary）
- 哈希表（Hashtable）
- 属性（Properties）

## 栈（Stack）

栈是Vector的一个子类，它实现了一个标准的后进先出的栈。

堆栈只定义了默认构造函数，用来创建一个空栈。 堆栈除了包括由Vector定义的所有方法，也定义了自己的一些方法。

| 序号 | 方法名                      | 作用                                             |
| ---- | --------------------------- | ------------------------------------------------ |
| 1    | boolean empty()             | 测试堆栈是否为空。                               |
| 2    | Object peek( )              | 查看堆栈顶部的对象，但不从堆栈中移除它。         |
| 3    | Object pop( )               | 移除堆栈顶部的对象，并作为此函数的值返回该对象。 |
| 4    | Object push(Object element) | 把项压入堆栈顶部。                               |
| 5    | int search(Object element)  | 返回对象在堆栈中的位置，以 1 为基数。            |

## 哈希表（Hashtable）