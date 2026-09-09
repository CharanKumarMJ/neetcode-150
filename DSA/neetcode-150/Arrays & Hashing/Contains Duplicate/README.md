# Contains Duplicate

## Problem

Given an integer array `nums`, return `true` if any value appears at least twice in the array, and return `false` if every element is distinct.

## Pattern

**Arrays & Hashing**

## Approach

Use a `HashSet` to keep track of the elements that have already been encountered.

For each element in the array:

1. Check whether the element is already present in the `HashSet`.
2. If it is present, a duplicate exists, so return `true`.
3. Otherwise, add the element to the `HashSet`.
4. If the entire array is processed without finding a duplicate, return `false`.

## Complexity

- **Time Complexity:** O(n)
- **Space Complexity:** O(n)

## Key Learning

A `HashSet` provides an efficient way to determine whether an element has already appeared in an array.
