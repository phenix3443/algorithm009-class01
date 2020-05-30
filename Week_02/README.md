
学习笔记
* 第五课 哈希表、映射、集合

** [[https://leetcode-cn.com/problems/valid-anagram][242 有效的字母异位词]]
   + 考察点：hash 使用
   + 异位词的共同点：所有异位词字母排序后得到的单词一样，所以可以作为 key。

** [[https://leetcode-cn.com/problems/group-anagrams/][49 字母异位词分组]]
   + 同上

* 第六课 树、二叉树、二叉搜索树

** [[https://leetcode-cn.com/problems/binary-tree-inorder-traversal/][94 二叉树的中序遍历]]
   + 考察点：递归
** [[https://leetcode-cn.com/problems/binary-tree-preorder-traversal/][144 二叉树的前序遍历]]
   + 考察点：递归
** [[https://leetcode-cn.com/problems/n-ary-tree-preorder-traversal/description/][589 N叉树的前序遍历]]
   + 考察点：递归
** [[https://leetcode-cn.com/problems/n-ary-tree-postorder-traversal/][590 N叉树的后序遍历]]
   + 考察点：递归

** 树总结
   + 树是链表的二维化，所以链表的一些操作技巧可以用在树上。

* 第七课 堆、二叉堆、图
  堆的实现：二叉堆，斐波那契堆，参看 https://en.wikipedia.org/wiki/Heap_(data_structure)

  二叉堆：
  + 完全二叉树。
  + 数组存储：左（2i+1） 右儿子（2i+2）

** [[https://leetcode-cn.com/problems/zui-xiao-de-kge-shu-lcof/][40-最小的k个数]]
   + 考察点：堆的性质。
   + 最好自己实现以下大根堆的调整过程。

** [[https://leetcode-cn.com/problems/kth-largest-element-in-an-array/][215 数组中的第k个最大元素]]
   + 考察点：堆的性质。
   + 同上一题，就是使用大根堆排序后的最后一个元素。

** [[https://leetcode-cn.com/problems/top-k-frequent-elements/][347 前k个高频元素]]
   + 考察点：堆的性质，要举一反三
   + (k,c)按照 c 简历大根堆。

** [[https://leetcode-cn.com/problems/sliding-window-maximum/][239 滑动窗口的最大值]]
   + 考察思路：单调栈思路的变形
   + 如果要是使用堆，k个元素建堆的复杂度是 O(k),该操作要执行 n-k 此，总体时间复杂度是 O(k)*O(n-k)

** [[https://leetcode-cn.com/problems/chou-shu-lcof/][49 丑数]]
   + 考察点：
