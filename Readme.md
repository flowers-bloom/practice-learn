# jdk-learn
该仓库用于记录个人对`jdk`中一些实现的学习，比如自己动手实现一个优先队列。

## 实践记录
1、优先队列
- 泛型，支持任意元素
- 可自定义比较器，支持自定义元素的优先顺序
- 对象数组存储元素，需实现扩容方式
- 通过堆维护顺序
- 先进先出，非双端队列

```java
/**
 * <? extends E> 表示集合中的元素必须是 E 的子类
 * <? super E> 表示集合中的元素必须是 E 的父类
 * <E extends Comparable<? super E>> 表示 E 或者 E 的父类其中之一，必须实现 comparable 接口
 */
```