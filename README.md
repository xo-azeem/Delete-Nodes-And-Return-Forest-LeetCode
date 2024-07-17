# Delete Nodes And Return Forest

LeetCode Q # 1110.

Given the root of a binary tree, each node in the tree has a distinct value.

After deleting all nodes with a value in to_delete, we are left with a forest (a disjoint union of trees).

Return the roots of the trees in the remaining forest. You may return the result in any order.

Example 1:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/bb9a4247-71c2-4f04-af55-dbd1c2f51ae2)

</div>

> Input: root = [1,2,3,4,5,6,7], to_delete = [3,5]</br>
> Output: [[1,2,null,4],[6],[7]]

Example 2:

> Input: root = [1,2,4,null,3], to_delete = [3]</br>
> Output: [[1,2,4]]

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/f404e765-78d8-46dc-81d2-422ca3423e89)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
