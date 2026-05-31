# Minimum Time Taken to Burn a Binary Tree

## Problem Statement

A fire starts at a target node.

Each second, fire spreads to:

- Parent
- Left Child
- Right Child

Find the minimum time required to burn the entire tree.

🔗 Problem Link:
https://takeuforward.org/data-structure/minimum-time-taken-to-burn-the-binary-tree-from-a-node

---

## Approach

This problem is very similar to Nodes at Distance K.

Step 1:

Create parent references.

Step 2:

Treat the tree as an undirected graph.

Step 3:

Run BFS from the target node.

Each BFS level represents one second of fire spread.

---

## Design Pattern

### Multi-Directional BFS

The fire expands simultaneously in all directions.

This is a classic BFS expansion problem.

---

## Time Complexity

O(N)

---

## Space Complexity

O(N)

---

## Key Learning

Many spreading problems can be modeled as BFS.

Examples:

- Fire spread
- Infection spread
- Network propagation
- Shortest path exploration
