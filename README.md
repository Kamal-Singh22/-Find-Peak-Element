# -Find-Peak-Element
A peak element is an element that is strictly greater than its neighbors. Given a 0-indexed integer array nums, find a peak element and return its index. If the array contains multiple peaks, return the index of any of them.




Explanation:
Binary Search Approach:

Use two pointers left and right to perform binary search.
Compare the middle element nums[mid] with its next element nums[mid + 1].
If nums[mid] > nums[mid + 1], the peak lies in the left half (or is the middle element).
Otherwise, the peak lies in the right half.
Time Complexity:

The solution runs in 
𝑂(logn)
O(logn), where 
𝑛
n is the length of the input array.
Space Complexity:

The space complexity is 
𝑂(1)
O(1) as we use constant extra space.
