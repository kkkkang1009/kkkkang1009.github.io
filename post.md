# Algorithm
## Leetcode 문제풀기
* [1. Two Sum](https://leetcode.com/problems/two-sum/)
'
class Solution:
   def twoSum(self, nums, target):
       for i in range(0, len(nums)):
           for j in range(i+1, len(nums)):
               if nums[i] + nums[j] == target:
                   return [i, j]
'
  
* [7. Reverse Integer](https://leetcode.com/problems/reverse-integer/)
'
class Solution:
   def reverse(self, x):
       if x > 0:
           xtoString = x.__str__()
           revX = xtoString[::-1]
           answer = int(revX)
       else:
           x = -x
           xtoString = x.__str__()
           revX = xtoString[::-1]
           answer = -int(revX)
       if answer > 2147483647 or answer < -2147483648:
           return 0
       return answer
'
* [test](https://www.supremenewyork.com/shop)
