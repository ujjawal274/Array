Array Questions...

So, basically i am working on an array question that is called "Two Sum" ,

"" 1. Two Sum
Easy
Topics
premium lock icon
Companies
Hint
You are given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.

 

Example 1:

Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].
Example 2:

Input: nums = [3,2,4], target = 6
Output: [1,2]
Example 3:

Input: nums = [3,3], target = 6
Output: [0,1]
 

Constraints:

2 <= nums.length <= 104
-109 <= nums[i] <= 109
-109 <= target <= 109
Only one valid answer exists. ""

Solution For That ---

SOURCE CODE:
class Solution:
    def twoSum(self, nums, target):
        i=0
        j=i+1

        for i in range(0,len(nums)):
            for i in range(i+1,len(nums)):
               if nums[i] + nums[j] == target:
                  return [i,j]   

 I solved an Array Question called TwoSum.
 And next question i solved that called Rotate Array

 ---
 I practiced two questions of array:
 First- Best time to Buy and sell stocks
  Second- TwoSum utooguglougipl
 ---  
 I practiced one question of array:
 Known as- Single No. uoyfosuegfo8usrt

 ---
 I practiced an Array Question:
 Known as- sortedSquares

fgbzgdhvhggxgxhh

---
---
---
