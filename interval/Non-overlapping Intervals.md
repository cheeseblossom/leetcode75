https://leetcode.com/problems/non-overlapping-intervals/description/

Given an array of intervals `intervals` where `intervals[i] = [starti, endi]`, return _the minimum number of intervals you need to remove to make the rest of the intervals non-overlapping._

---

Example 1:

Input: intervals = [[1,2],[2,3],[3,4],[1,3]]

Output: 1

Explanation: [1,3] can be removed and the rest of the intervals are non-overlapping.

---

Example 2:

Input: intervals = [[1,2],[1,2],[1,2]]

Output: 2

Explanation: You need to remove two [1,2] to make the rest of the intervals non-overlapping.

---

Example 3:

Input: intervals = [[1,2],[2,3]]

Output: 0

Explanation: You don't need to remove any of the intervals since they're already non-overlapping.

---

Constraints:

- 1 <= intervals.length <= 10<sup>5</sup>
- intervals[i].length == 2
- -5 _ 10<sup>4</sup> <= starti < endi <= 5 _ 10<sup>4</sup>

---

```java
class Solution {
    public int eraseOverlapIntervals(int[][] intervals) {

    }
}
```
