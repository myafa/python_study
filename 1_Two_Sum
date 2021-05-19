class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        #딕셔너리의 해시 테이블활용
        dd = {nums[i]:i for i in range(len(nums))}
        #dd = {num:i for i,num in enumerate(nums)}
        for i in range(len(nums)):
            if target-nums[i] in dd and dd[target-nums[i]]>i :
                return [i,dd[target-nums[i]]]
