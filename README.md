# Two-Sum-Algorithm-and-My-Solution
My code which solves a Two sum algorithm



The algorithm: Given an array of integers, return indices of the two numbers such that they add up to a specific target.

You may assume that each input will have at most one solution, and you may not use the same index twice.

In case no solution exists, return [-1, -1]

Example:

Input: nums = [2, 7, 11, 15], target = 9
Output: [0, 1]
Explanation: nums[0] + nums[1] = 2 + 7 = 9




Steps:
 Step # 1 / 5
Using an index i, iterated over the indices of nums.
 
 Step # 2 / 5
Using an index j, next, iterated over the indices of nums starting from index i + 1.
 
 Step # 3 / 5
Wrote out  an if statement that checked to see  if nums[i] + nums[j] is going to be  equal to target
 
 Step # 4 / 5
Returned the pair (i, j)
 
 Step # 5 / 5
Finally, returned the pair (-1, -1) in case the search terminates with no valid solution.
