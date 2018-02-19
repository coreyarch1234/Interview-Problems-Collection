## What is this:
This will contain all of the problems Make Schoolers have encountered in:
- Company interviews
- Mock interviews
- Independent practice

## How to submit:
- Choose the language folder (i.e. - python, javascript)
- Create a new file with a descriptive name for the problem (i.e. - kth_largest_element.py, combination_sum.js)
- Include the problem description as a comment. Within the problem description, include:
    - What the problem is asking
    - The source of the problem (i.e. - leetcode, interviewcake, Alan's Core Data Structures Class)
- Write your solution with a solution number in the format:
    - Solution 1, 2, 3, ...

* Note: Try your best to make sure the proposed solution works (try as many test cases as possible). If you are unsure, leave a note that you have not fully tested the proposed solution. Feel free to leave test cases in the solution!

## Example of a Good Submission:
- File Name: binary_tree_max_depth.py
- Problem Description and Solution:
```
# https://leetcode.com/problems/maximum-depth-of-binary-tree/description/
#
#
# Given a binary tree, find its maximum depth.
#
# The maximum depth is the number of nodes along the longest path from the root node down to the farthest leaf node.

# Solution 1:
def maxDepth(root):
    """
    :type root: TreeNode
    :rtype: int
    """
     if not root:
        return 0

    return 1 + max(maxDepth(root.left), maxDepth(root.right))

```
