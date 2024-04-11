https://leetcode.com/problems/reorder-list/description/

You are given the head of a singly linked-list. The list can be represented as:

L0 → L1 → … → Ln - 1 → Ln

_Reorder the list to be on the following form:_

L0 → Ln → L1 → Ln - 1 → L2 → Ln - 2 → …

You may not modify the values in the list's nodes. Only nodes themselves may be changed.

---

Example 1:

![image](/img/reorder1linked-list.jpg)

Input: head = [1,2,3,4]

Output: [1,4,2,3]

---

Example 2:

![image](/img/reorder2-linked-list.jpg)

Input: head = [1,2,3,4,5]

Output: [1,5,2,4,3]

---

Constraints:

- The number of nodes in the list is in the range [1, 5 * 10<sup>4</sup>].
- 1 <= Node.val <= 1000

---

```java
/**
 * Definition for singly-linked list.
 * public class ListNode {
 *     int val;
 *     ListNode next;
 *     ListNode() {}
 *     ListNode(int val) { this.val = val; }
 *     ListNode(int val, ListNode next) { this.val = val; this.next = next; }
 * }
 */
class Solution {
    public void reorderList(ListNode head) {

    }
}
```