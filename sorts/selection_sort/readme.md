# 选择排序

## 概念
这是一种简单直观的排序算法。它的工作原理如下：
首先在未排序序列中找到最小（大）元素，存放到排序序列的**起始位置**，然后，再从**剩余未排序**元素中继续寻找最小（大）元素，然后放到**已排序**序列的**末尾**。以此类推，直到所有元素均排序完毕。

**注意**：在排序算法中，我们默认序列内部元素是可比较的，否则无意义。

## 图示

![选择排序算法](./img/Selection_sort_animation.gif)

![选择排序动画示例](./img/Selection-Sort-Animation.gif)

红色表示当前未排序序列中的最小值，黄色表示已排序序列，蓝色表示搜寻操作。

## 复杂度

O(n^2)

```bash
n*(n-1)*……*1 = (n^2)/2 >> O(n^2)
```

