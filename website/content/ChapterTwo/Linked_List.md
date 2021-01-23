---
title: Linked List
type: docs
---

# Linked List

![](https://img.halfrost.com/Leetcode/Linked_List.png)


- 巧妙的构造虚拟头结点。可以使遍历处理逻辑更加统一。
- 灵活使用递归。构造递归条件，使用递归可以巧妙的解题。不过需要注意有些题目不能使用递归，因为递归深度太深会导致超时和栈溢出。
- 链表区间逆序。第 92 题。
- 链表寻找中间节点。第 876 题。链表寻找倒数第 n 个节点。第 19 题。只需要一次遍历就可以得到答案。
- 合并 K 个有序链表。第 21 题，第 23 题。
- 链表归类。第 86 题，第 328 题。
- 链表排序，时间复杂度要求 O(n * log n)，空间复杂度 O(1)。只有一种做法，归并排序，至顶向下归并。第 148 题。
- 判断链表是否存在环，如果有环，输出环的交叉点的下标；判断 2 个链表是否有交叉点，如果有交叉点，输出交叉点。第 141 题，第 142 题，第 160 题。




| No.      | Title | Solution | Difficulty | TimeComplexity | SpaceComplexity |Favorite| Acceptance |
|:--------:|:------- | :--------: | :----------: | :----: | :-----: | :-----: |:-----: |
|0002|Add Two Numbers|[Go]({{< relref "/ChapterFour/0002.Add-Two-Numbers.md" >}})|Medium| O(n)| O(1)||35.2%|
|0019|Remove Nth Node From End of List|[Go]({{< relref "/ChapterFour/0019.Remove-Nth-Node-From-End-of-List.md" >}})|Medium| O(n)| O(1)||35.6%|
|0021|Merge Two Sorted Lists|[Go]({{< relref "/ChapterFour/0021.Merge-Two-Sorted-Lists.md" >}})|Easy| O(log n)| O(1)||55.7%|
|0023|Merge k Sorted Lists|[Go]({{< relref "/ChapterFour/0023.Merge-k-Sorted-Lists.md" >}})|Hard| O(log n)| O(1)|❤️|42.0%|
|0024|Swap Nodes in Pairs|[Go]({{< relref "/ChapterFour/0024.Swap-Nodes-in-Pairs.md" >}})|Medium| O(n)| O(1)||52.7%|
|0025|Reverse Nodes in k-Group|[Go]({{< relref "/ChapterFour/0025.Reverse-Nodes-in-k-Group.md" >}})|Hard| O(log n)| O(1)|❤️|44.4%|
|0061|Rotate List|[Go]({{< relref "/ChapterFour/0061.Rotate-List.md" >}})|Medium| O(n)| O(1)||31.6%|
|0082|Remove Duplicates from Sorted List II|[Go]({{< relref "/ChapterFour/0082.Remove-Duplicates-from-Sorted-List-II.md" >}})|Medium| O(n)| O(1)||39.0%|
|0083|Remove Duplicates from Sorted List|[Go]({{< relref "/ChapterFour/0083.Remove-Duplicates-from-Sorted-List.md" >}})|Easy| O(n)| O(1)||46.3%|
|0086|Partition List|[Go]({{< relref "/ChapterFour/0086.Partition-List.md" >}})|Medium| O(n)| O(1)|❤️|43.1%|
|0092|Reverse Linked List II|[Go]({{< relref "/ChapterFour/0092.Reverse-Linked-List-II.md" >}})|Medium| O(n)| O(1)|❤️|40.3%|
|0109|Convert Sorted List to Binary Search Tree|[Go]({{< relref "/ChapterFour/0109.Convert-Sorted-List-to-Binary-Search-Tree.md" >}})|Medium| O(log n)| O(n)||49.8%|
|0138|Copy List with Random Pointer|[Go]({{< relref "/ChapterFour/0138.Copy-List-with-Random-Pointer.md" >}})|Medium||||39.6%|
|0141|Linked List Cycle|[Go]({{< relref "/ChapterFour/0141.Linked-List-Cycle.md" >}})|Easy| O(n)| O(1)|❤️|42.3%|
|0142|Linked List Cycle II|[Go]({{< relref "/ChapterFour/0142.Linked-List-Cycle-II.md" >}})|Medium| O(n)| O(1)|❤️|39.4%|
|0143|Reorder List|[Go]({{< relref "/ChapterFour/0143.Reorder-List.md" >}})|Medium| O(n)| O(1)|❤️|40.3%|
|0147|Insertion Sort List|[Go]({{< relref "/ChapterFour/0147.Insertion-Sort-List.md" >}})|Medium| O(n)| O(1)|❤️|44.2%|
|0148|Sort List|[Go]({{< relref "/ChapterFour/0148.Sort-List.md" >}})|Medium| O(n log n)| O(n)|❤️|45.9%|
|0160|Intersection of Two Linked Lists|[Go]({{< relref "/ChapterFour/0160.Intersection-of-Two-Linked-Lists.md" >}})|Easy| O(n)| O(1)|❤️|42.7%|
|0203|Remove Linked List Elements|[Go]({{< relref "/ChapterFour/0203.Remove-Linked-List-Elements.md" >}})|Easy| O(n)| O(1)||39.1%|
|0206|Reverse Linked List|[Go]({{< relref "/ChapterFour/0206.Reverse-Linked-List.md" >}})|Easy| O(n)| O(1)||64.9%|
|0234|Palindrome Linked List|[Go]({{< relref "/ChapterFour/0234.Palindrome-Linked-List.md" >}})|Easy| O(n)| O(1)||40.3%|
|0237|Delete Node in a Linked List|[Go]({{< relref "/ChapterFour/0237.Delete-Node-in-a-Linked-List.md" >}})|Easy| O(n)| O(1)||66.4%|
|0328|Odd Even Linked List|[Go]({{< relref "/ChapterFour/0328.Odd-Even-Linked-List.md" >}})|Medium| O(n)| O(1)||56.9%|
|0445|Add Two Numbers II|[Go]({{< relref "/ChapterFour/0445.Add-Two-Numbers-II.md" >}})|Medium| O(n)| O(n)||56.1%|
|0707|Design Linked List|[Go]({{< relref "/ChapterFour/0707.Design-Linked-List.md" >}})|Medium| O(n)| O(1)||25.8%|
|0725|Split Linked List in Parts|[Go]({{< relref "/ChapterFour/0725.Split-Linked-List-in-Parts.md" >}})|Medium| O(n)| O(1)||52.8%|
|0817|Linked List Components|[Go]({{< relref "/ChapterFour/0817.Linked-List-Components.md" >}})|Medium| O(n)| O(1)||57.6%|
|0876|Middle of the Linked List|[Go]({{< relref "/ChapterFour/0876.Middle-of-the-Linked-List.md" >}})|Easy| O(n)| O(1)|❤️|68.9%|
|1019|Next Greater Node In Linked List|[Go]({{< relref "/ChapterFour/1019.Next-Greater-Node-In-Linked-List.md" >}})|Medium| O(n)| O(1)||58.2%|
|1171|Remove Zero Sum Consecutive Nodes from Linked List|[Go]({{< relref "/ChapterFour/1171.Remove-Zero-Sum-Consecutive-Nodes-from-Linked-List.md" >}})|Medium||||41.5%|
|1290|Convert Binary Number in a Linked List to Integer|[Go]({{< relref "/ChapterFour/1290.Convert-Binary-Number-in-a-Linked-List-to-Integer.md" >}})|Easy||||81.7%|
|1669|Merge In Between Linked Lists|[Go]({{< relref "/ChapterFour/1669.Merge-In-Between-Linked-Lists.md" >}})|Medium||||78.0%|
|1670|Design Front Middle Back Queue|[Go]({{< relref "/ChapterFour/1670.Design-Front-Middle-Back-Queue.md" >}})|Medium||||54.6%|
|------------|-------------------------------------------------------|-------| ----------------| ---------------|-------------|-------------|-------------|


----------------------------------------------
<div style="display: flex;justify-content: space-between;align-items: center;">
<p><a href="https://books.halfrost.com/leetcode/ChapterTwo/Two_Pointers/">⬅️上一页</a></p>
<p><a href="https://books.halfrost.com/leetcode/ChapterTwo/Stack/">下一页➡️</a></p>
</div>
