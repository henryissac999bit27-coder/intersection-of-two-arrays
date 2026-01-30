# LeetCode #349: Intersection of Two Arrays (Easy)

## 📝 Problem Description
Given two integer arrays `nums1` and `nums2`, return an array of their intersection. Each element in the result must be **unique**, and the result can be returned in any order.

## 🚀 My Solution
The approach leverages the properties of **HashSets** to handle uniqueness and intersection:
1. **Uniqueness:** Load both arrays into separate `HashSet` objects to automatically remove duplicates within each array.
2. **Intersection:** Utilize the built-in `set1.retainAll(set2)` method, which performs a mathematical intersection, leaving only common elements in `set1`.
3. **Conversion:** Iterate through the resulting set to populate the final integer array.

## 📊 Complexity Analysis
- **Time Complexity:** $O(n + m)$ where $n$ and $m$ are the lengths of the two arrays.
- **Space Complexity:** $O(n + m)$ to store the elements in the sets.

## 🔗 Problem Link
[Intersection of Two Arrays - LeetCode](https://leetcode.com)
