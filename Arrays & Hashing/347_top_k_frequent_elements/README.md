# 347. Top K Frequent Elements

$\textsf{\color{Goldenrod} Medium}$

Given an integer array `nums` and an integer `k`, return <em>the</em> `k` <em>most frequent elements.</em> You may return the answer in <strong>any order</strong>.

### Example 1:

    Input: nums = [1,1,1,2,2,3], k = 2
    Output: [1,2]

### Example 2:

    Input: nums = [1], k = 1
    Output: [1]

### Constraints:

    1 <= nums.length <= 105
    -104 <= nums[i] <= 104
    k is in the range [1, the number of unique elements in the array].
    It is guaranteed that the answer is unique.

### Follow up:

Your algorithm's time complexity must be better than O(n log n), where n is the array's size.
