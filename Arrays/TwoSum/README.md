# Two Sum

## Problem
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

---

## Approach 1: HashMap
- Store number with index
- Check if complement exists

Time Complexity: O(n)  
Space Complexity: O(n)

---

## Approach 2: Two Pointer
- Works only for sorted array
- Use left and right pointers

Time Complexity: O(n log n)

---

## Example
Input: nums = [2,7,11,15], target = 9  
Output: [0,1]