https://leetcode.com/problems/validate-binary-search-tree/description/

Given the `root` of a binary tree, _determine if it is a valid binary search tree (BST)._

A **valid BST** is defined as follows:

- The left subtree of a node contains only nodes with keys less than the node's key.
- The right subtree of a node contains only nodes with keys greater than the node's key.
- Both the left and right subtrees must also be binary search trees.

---

Example 1:

![image](/img/tree2.jpg)

Input: root = [2,1,3]

Output: true

---

Example 2:

![image](/img/tree3.jpg)

Input: root = [5,1,4,null,null,3,6]

Output: false

Explanation: The root node's value is 5 but its right child's value is 4.

---

Constraints:

- The number of nodes in the tree is in the range [1, 10<sup>4</sup>].
- -2<sup>31</sup> <= Node.val <= 2<sup>31</sup> - 1

---

```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode() {}
 *     TreeNode(int val) { this.val = val; }
 *     TreeNode(int val, TreeNode left, TreeNode right) {
 *         this.val = val;
 *         this.left = left;
 *         this.right = right;
 *     }
 * }
 */
class Solution {
    public boolean isValidBST(TreeNode root) {

    }
}
```
