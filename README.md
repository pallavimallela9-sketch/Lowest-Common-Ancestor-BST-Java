# Lowest Common Ancestor of a Binary Search Tree - Java

## Problem Statement

Given a Binary Search Tree (BST) and two nodes, find their
Lowest Common Ancestor (LCA).

The Lowest Common Ancestor is the lowest node in the tree that
has both given nodes as descendants.

## Example

### Input

        6
       / \
      2   8
     / \
    0   4

p = 2
q = 4

### Output

2

## Explanation

Node 2 is an ancestor of both 2 and 4.

Therefore, the Lowest Common Ancestor is 2.

## Approach

We use the Binary Search Tree property.

- If both nodes are smaller than the current node, move left.
- If both nodes are greater than the current node, move right.
- Otherwise, the current node is the Lowest Common Ancestor.

## Complexity

- Time Complexity: O(h)
- Space Complexity: O(1)

Where `h` is the height of the tree.

## Language

Java

## Algorithm

Binary Search Tree

## Data Structure

Binary Tree

## Author

M. Pallavi
