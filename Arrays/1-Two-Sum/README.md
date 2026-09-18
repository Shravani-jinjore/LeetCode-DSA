# 1. Two Sum

## Problem
Given an array of integers `nums` and an integer `target`, return the
indices of two numbers whose sum is equal to `target`.

## Approach
Use a Hash Map.

For every number, calculate its complement:

complement = target - nums[i]

Check whether the complement already exists in the hash map.

If it exists, we have found the two required indices.

Otherwise, store the current number and its index in the hash map.

## Complexity
Time: O(n)

Space: O(n)
