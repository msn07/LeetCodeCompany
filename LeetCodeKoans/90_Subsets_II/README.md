# [90. Subsets II](https://leetcode.com/problems/subsets-ii/#/description)

## Description

Given a collection of integers that might contain duplicates, **nums**, return all possible subsets.

**Note:** The solution set must not contain duplicate subsets.

For example,     
If **nums** = `[1,2,2]`, a solution is:

```
[
  [2],
  [1],
  [1,2,2],
  [2,2],
  [1,2],
  []
]
```

## Solution

* HashSet

* backtrack    
  Sort -> list add -> for loop -> skip duplicate -> temp add -> bt -> temp remote top.
