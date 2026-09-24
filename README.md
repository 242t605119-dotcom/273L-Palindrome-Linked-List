# Palindrome Linked List

LeetCode 234

## Problem Statement

Given the head of a singly linked list, determine whether the linked list is a palindrome.

A palindrome is a sequence that reads the same from left to right and from right to left.

## Solution

This solution stores all the values of the linked list in a list.

After collecting the values, the list is compared with its reversed version. If both are the same, the linked list is a palindrome.

## Example

### Input

```text
head = [1,2,2,1]
```

### Output

```text
true
```

### Explanation

The linked list values are:

```text
[1,2,2,1]
```

The reversed values are also:

```text
[1,2,2,1]
```

Since both are the same, the linked list is a palindrome.

## Approach

1. Traverse the linked list.
2. Store each node value in a list.
3. Reverse the stored list.
4. Compare the original list with the reversed list.
5. Return `true` if they are equal; otherwise, return `false`.

## Algorithm

1. Create an empty list called `values`.
2. Traverse the linked list until the end.
3. Add each node's value to `values`.
4. Compare `values` with `values[::-1]`.
5. Return the comparison result.

## Complexity

* Time Complexity: O(n)
* Space Complexity: O(n)

## Author

T. Nandhini
