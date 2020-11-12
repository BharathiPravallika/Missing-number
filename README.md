# 8) Missing-number
<b>Find the missing number in the given array
Given an array nums containing n distinct numbers in the range [0, n], return the only number in the range that is missing from the array.

Follow up: Could you implement a solution using only O(1) extra space complexity and O(n) runtime complexity?</b>

 

Example 1:

Input: nums = [3,0,1]<br>
Output: 2<br>
Explanation: n = 3 since there are 3 numbers, so all numbers are in the range [0,3]. 2 is the missing number in the range since it does not appear in nums.<br>

Example 2:

Input: nums = [0,1]<br>
Output: 2<br>
Explanation: n = 2 since there are 2 numbers, so all numbers are in the range [0,2]. 2 is the missing number in the range since it does not appear in nums.<br>

Example 3:

Input: nums = [9,6,4,2,3,5,7,0,1]<br>
Output: 8<br>
Explanation: n = 9 since there are 9 numbers, so all numbers are in the range [0,9]. 8 is the missing number in the range since it does not appear in nums.<br>

Example 4:

Input: nums = [0]<br>
Output: 1<br>
Explanation: n = 1 since there is 1 number, so all numbers are in the range [0,1]. 1 is the missing number in the range since it does not appear in nums.<br>

 

Constraints:

    n == nums.length
    1 <= n <= 104
    0 <= nums[i] <= n
    All the numbers of nums are unique.

