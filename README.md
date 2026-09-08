# leetcode-notes

个人 LeetCode 刷题笔记，记录解题思路与代码实现。

---

## 进度总览

| # | 题目 | 难度 | 状态 | 分类 | 题解 |
|---|------|------|------|------|------|
| 1 | Two Sum | Easy | AC且最优 | 数组、哈希表 | [链接](./solutions/1.md) |
| 2 | Add Two Numbers | Medium | 思路正确但不能AC | 链表、模拟 | [链接](./solutions/2.md) |
| 3 | Longest Substring Without Repeating Characters | Medium | 思路正确但不能AC | 哈希表、字符串、滑动窗口 | [链接](./solutions/3.md) |
| 11 | Container With Most Water | Medium | AC且最优 | 双指针、贪心 | [链接](./solutions/11.md) |
| 15 | 3Sum | Medium | 思路正确但不能AC | 数组、双指针、排序 | [链接](./solutions/15.md) |
| 41 | First Missing Positive | Hard | AC非最优 | 数组、哈希表 | [链接](./solutions/41.md) |
| 42 | Trapping Rain Water | Hard | 思路正确但不能AC | 数组、双指针、动态规划 | [链接](./solutions/42.md) |
| 48 | Rotate Image | Medium | 无思路 | 数组、矩阵 | [链接](./solutions/48.md) |
| 49 | Group Anagrams | Medium | AC且最优 | 哈希表、字符串、排序 | [链接](./solutions/49.md) |
| 53 | Maximum Subarray | Medium | 思路正确但不能AC | 数组、动态规划 | [链接](./solutions/53.md) |
| 54 | Spiral Matrix | Medium | 思路正确但不能AC | 数组、矩阵、模拟 | [链接](./solutions/54.md) |
| 56 | Merge Intervals | Medium | AC且最优 | 数组、排序 | [链接](./solutions/56.md) |
| 73 | Set Matrix Zeroes | Medium | 思路正确但不能AC | 数组、矩阵、原地算法 | [链接](./solutions/73.md) |
| 76 | Minimum Window Substring | Hard | 思路错误 | 哈希表、字符串、滑动窗口 | [链接](./solutions/76.md) |
| 94 | Binary Tree Inorder Traversal | Easy | AC非最优 | 树、栈、递归 | [链接](./solutions/94.md) |
| 101 | Symmetric Tree | Easy | AC且最优（纠错后通过） | 树、递归 | [链接](./solutions/101.md) |
| 102 | Binary Tree Level Order Traversal | Medium | AC且最优（纠错后通过） | 树、广度优先搜索、队列 | [链接](./solutions/102.md) |
| 104 | Maximum Depth of Binary Tree | Easy | AC且最优 | 树、递归 | [链接](./solutions/104.md) |
| 21 | Merge Two Sorted Lists | Easy | AC且最优 | 链表 | [链接](./solutions/21.md) |
| 24 | Swap Nodes in Pairs | Medium | AC且最优 | 链表 | [链接](./solutions/24.md) |
| 25 | Reverse Nodes in k-Group | Hard | 无思路 | 链表 | [链接](./solutions/25.md) |
| 19 | Remove Nth Node From End of List | Medium | AC且最优 | 链表、双指针 | [链接](./solutions/19.md) |
| 128 | Longest Consecutive Sequence | Medium | AC且最优 | 哈希表、数组 | [链接](./solutions/128.md) |
| 141 | Linked List Cycle | Easy | AC非最优 | 链表、双指针 | [链接](./solutions/141.md) |
| 138 | Copy List with Random Pointer | Medium | AC非最优 | 链表、哈希表 | [链接](./solutions/138.md) |
| 142 | Linked List Cycle II | Medium | AC非最优 | 链表、双指针、哈希表 | [链接](./solutions/142.md) |
| 148 | Sort List | Medium | 无思路 | 链表、归并排序 | [链接](./solutions/148.md) |
| 160 | Intersection of Two Linked Lists | Easy | AC非最优 | 链表、双指针 | [链接](./solutions/160.md) |
| 189 | Rotate Array | Medium | AC非最优 | 数组、数学 | [链接](./solutions/189.md) |
| 226 | Invert Binary Tree | Easy | AC且最优 | 树、递归 | [链接](./solutions/226.md) |
| 238 | Product of Array Except Self | Medium | AC非最优 | 数组、前缀积 | [链接](./solutions/238.md) |
| 239 | Sliding Window Maximum | Hard | 思路正确但不能AC | 队列、数组、滑动窗口 | [链接](./solutions/239.md) |
| 240 | Search a 2D Matrix II | Medium | AC非最优 | 数组、矩阵、二分查找 | [链接](./solutions/240.md) |
| 234 | Palindrome Linked List | Easy | AC非最优 | 链表、双指针 | [链接](./solutions/234.md) |
| 283 | Move Zeroes | Easy | AC且最优 | 双指针、数组 | [链接](./solutions/283.md) |
| 438 | Find All Anagrams in a String | Medium | 思路正确但不能AC | 哈希表、字符串、滑动窗口 | [链接](./solutions/438.md) |
| 543 | Diameter of Binary Tree | Easy | AC且最优（纠错后通过） | 树、递归 | [链接](./solutions/543.md) |
| 560 | Subarray Sum Equals K | Medium | 思路正确但不能AC | 数组、哈希表、前缀和 | [链接](./solutions/560.md) |

---

## 按专题分类

### 哈希表

| # | 题目 | 难度 |
|---|------|------|
| 1 | Two Sum | Easy |
| 3 | Longest Substring Without Repeating Characters | Medium |
| 41 | First Missing Positive | Hard |
| 49 | Group Anagrams | Medium |
| 76 | Minimum Window Substring | Hard |
| 128 | Longest Consecutive Sequence | Medium |
| 438 | Find All Anagrams in a String | Medium |
| 560 | Subarray Sum Equals K | Medium |

### 双指针

| # | 题目 | 难度 |
|---|------|------|
| 11 | Container With Most Water | Medium |
| 15 | 3Sum | Medium |
| 42 | Trapping Rain Water | Hard |
| 283 | Move Zeroes | Easy |

### 树

| # | 题目 | 难度 |
|---|------|------|
| 94 | Binary Tree Inorder Traversal | Easy |
| 101 | Symmetric Tree | Easy |
| 102 | Binary Tree Level Order Traversal | Medium |
| 104 | Maximum Depth of Binary Tree | Easy |
| 226 | Invert Binary Tree | Easy |
| 543 | Diameter of Binary Tree | Easy |

### 广度优先搜索

| # | 题目 | 难度 |
|---|------|------|
| 102 | Binary Tree Level Order Traversal | Medium |

### 数组

| # | 题目 | 难度 |
|---|------|------|
| 1 | Two Sum | Easy |
| 15 | 3Sum | Medium |
| 41 | First Missing Positive | Hard |
| 42 | Trapping Rain Water | Hard |
| 48 | Rotate Image | Medium |
| 53 | Maximum Subarray | Medium |
| 54 | Spiral Matrix | Medium |
| 56 | Merge Intervals | Medium |
| 73 | Set Matrix Zeroes | Medium |
| 128 | Longest Consecutive Sequence | Medium |
| 283 | Move Zeroes | Easy |
| 239 | Sliding Window Maximum | Hard |
| 189 | Rotate Array | Medium |
| 238 | Product of Array Except Self | Medium |
| 240 | Search a 2D Matrix II | Medium |
| 560 | Subarray Sum Equals K | Medium |

### 链表

| # | 题目 | 难度 |
|---|------|------|
| 2 | Add Two Numbers | Medium |
| 19 | Remove Nth Node From End of List | Medium |
| 21 | Merge Two Sorted Lists | Easy |
| 24 | Swap Nodes in Pairs | Medium |
| 25 | Reverse Nodes in k-Group | Hard |
| 160 | Intersection of Two Linked Lists | Easy |
| 141 | Linked List Cycle | Easy |
| 142 | Linked List Cycle II | Medium |
| 138 | Copy List with Random Pointer | Medium |
| 148 | Sort List | Medium |
| 234 | Palindrome Linked List | Easy |

### 贪心

| # | 题目 | 难度 |
|---|------|------|
| 11 | Container With Most Water | Medium |

### 排序

| # | 题目 | 难度 |
|---|------|------|
| 15 | 3Sum | Medium |
| 49 | Group Anagrams | Medium |
| 56 | Merge Intervals | Medium |

### 字符串

| # | 题目 | 难度 |
|---|------|------|
| 3 | Longest Substring Without Repeating Characters | Medium |
| 49 | Group Anagrams | Medium |
| 438 | Find All Anagrams in a String | Medium |
| 76 | Minimum Window Substring | Hard |

### 滑动窗口

| # | 题目 | 难度 |
|---|------|------|
| 3 | Longest Substring Without Repeating Characters | Medium |
| 239 | Sliding Window Maximum | Hard |
| 438 | Find All Anagrams in a String | Medium |
| 76 | Minimum Window Substring | Hard |

### 动态规划

| # | 题目 | 难度 |
|---|------|------|
| 42 | Trapping Rain Water | Hard |
| 53 | Maximum Subarray | Medium |

### 前缀和 / 前缀积

| # | 题目 | 难度 |
|---|------|------|
| 238 | Product of Array Except Self | Medium |
| 560 | Subarray Sum Equals K | Medium |

### 队列

| # | 题目 | 难度 |
|---|------|------|
| 102 | Binary Tree Level Order Traversal | Medium |
| 239 | Sliding Window Maximum | Hard |

---

## 专题笔记

| 专题 | 来源题目 | 链接 |
|------|---------|------|
| 递归 | #148 | [链接](./notes/递归.md) |
| 链表常用算法 | #2、#19、#21、#24、#25、#141、#142、#160、#234 | [链接](./notes/链表常用算法.md) |
| 链表边界处理 | #2、#21、#142、#160、#234 | [链接](./notes/链表边界处理.md) |

> 📌 工作流与协作约定见 [WORKFLOW.md](./WORKFLOW.md)（在其他对话/项目中快速恢复用）

---

## 使用说明

```bash
# 克隆仓库
git clone https://github.com/zawsze9/leetcode-notes.git

# 本地查看
cd leetcode-notes
```
