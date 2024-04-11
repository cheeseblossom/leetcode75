https://leetcode.com/problems/kth-smallest-element-in-a-bst/description/

Given the `root` of a binary search tree, and an integer `k`, return the `kth` _smallest value (**1-indexed**) of all the values of the nodes in the tree._

---

Example 1:

![image](/img/kthtree1.jpg)

Input: root = [3,1,4,null,2], k = 1

Output: 1

---

Example 2:

![image](/img/kthtree2.jpg)

Input: root = [5,3,6,2,4,null,null,1], k = 3

Output: 3

---

Constraints:

- The number of nodes in the tree is n.
- 1 <= k <= n <= 10<sup>4</sup>
- 0 <= Node.val <= 10<sup>4</sup>

Follow up: If the BST is modified often (i.e., we can do insert and delete operations) and you need to find the kth smallest frequently, how would you optimize?

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
    public int kthSmallest(TreeNode root, int k) {

    }
}
```
