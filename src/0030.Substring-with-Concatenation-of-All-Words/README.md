# [30. Substring with Concatenation of All Words][title]

## Description

Given two binary strings, return their sum (also a binary string).

The input strings are both **non-empty** and contains only characters `1` or `0`.

**Example 1:**

```
Input: a = "11", b = "1"
Output: "100"
```

**Example 2:**

```
Input: a = "1010", b = "1011"
Output: "10101"
```

**Tags:** Math, String

## 题意
>给定一个目标字符串s，一个单词集合words。
 要求使得words集合中所有元素连续出现在s中的首位置组成的集合（元素顺序不考虑）。

## 题解

### 思路1
> 按照小学算数那么来做，用 `carry` 表示进位，从后往前算，依次往前，每算出一位就插入到最前面即可，直到把两个二进制串都遍历完即可。

```go

```

### 思路2
> 思路2
```go

```

## 结语

如果你同我一样热爱数据结构、算法、LeetCode，可以关注我 GitHub 上的 LeetCode 题解：[awesome-golang-leetcode][me]

[title]: https://leetcode.com/problems/substring-with-concatenation-of-all-words/description/
[me]: https://github.com/kylesliu/awesome-golang-leetcode
