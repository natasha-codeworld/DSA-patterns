# Nodes at Distance K from Target Node

## Problem Statement

Print all nodes at distance K from a target node.

🔗 Problem Link:
https://takeuforward.org/data-structure/print-all-the-nodes-at-a-distance-of-k-in-a-binary-tree

---

## Approach

Convert the tree into an undirected graph.

Why?

Trees only allow movement downward.

This problem requires movement:

- Left
- Right
- Parent

After building parent references, perform BFS starting from the target node.

---

## Design Pattern

### Tree to Graph Transformation

A powerful pattern where:

Tree → Graph

Then solve using standard graph algorithms.

---

## Time Complexity

O(N)

---

## Space Complexity

O(N)

---

## Key Learning

Sometimes the easiest solution comes from changing the way we model the problem.

Tree problems can often be transformed into graph problems.
