# Lowest Common Ancestor in Binary Tree

## Problem Statement

Find the lowest common ancestor (LCA) of two given nodes in a binary tree.

🔗 Problem Link:
https://takeuforward.org/data-structure/lowest-common-ancestor-for-two-given-nodes

---

## Approach

This problem can be solved efficiently using Recursive DFS.

### Key Idea

- If current node is null, return null.
- If current node matches either target node, return current node.
- Search left subtree.
- Search right subtree.
- If both sides return non-null values, current node becomes the LCA.

---

## Design Pattern

### Recursive Divide & Conquer

Break the problem into:

- Search left subtree
- Search right subtree

Combine the results while returning back up the recursion stack.

---

## Time Complexity

O(N)

Every node is visited at most once.

---

## Space Complexity

O(H)

Where H is tree height.

Worst case:

O(N)

---

## Key Learning

Information can flow upward through recursive calls.

Many tree problems rely on returning meaningful information from child nodes to parent nodes.
