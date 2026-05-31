# Maximum Width of Binary Tree

## Problem Statement

Find the maximum width among all levels of a binary tree.

🔗 Problem Link:
https://takeuforward.org/data-structure/maximum-width-of-a-binary-tree

---

## Approach

Use Breadth First Search (Level Order Traversal).

Each node is assigned an index similar to heap indexing:

- Left Child = 2*i + 1
- Right Child = 2*i + 2

The width of a level is:

Last Index - First Index + 1

---

## Design Pattern

### BFS with Positional Indexing

Combines:

- Queue based traversal
- Virtual indexing

Useful whenever tree structure matters more than node values.

---

## Time Complexity

O(N)

---

## Space Complexity

O(N)

Queue stores nodes level by level.

---

## Key Learning

BFS is not limited to traversal.

Additional metadata can be carried along with nodes to solve structural tree problems.
