# DSA Interview Master List

> **240 Unique LeetCode Problems • Pattern-Oriented • Interview-Focused**

A focused DSA interview-preparation repository containing **exactly 240 unique LeetCode problems** and their solutions.

The goal of this repository is not to collect hundreds of repetitive questions. It is to build a compact interview-oriented problem set that covers the major DSA patterns while keeping a strict **240-problem ceiling**.

---

## 🎯 Purpose

This repository is designed to provide one canonical place for:

- The complete 240-problem DSA interview list.
- LeetCode links for every problem.
- Solutions for every selected problem.
- Pattern and topic classification.
- Difficulty and priority information.
- A progression from fundamentals to advanced interview patterns.
- A reusable revision resource after the initial problem-solving phase.

The emphasis is **pattern recognition**, not raw problem count.

> **Learn the pattern → solve representative problems → recognize variations → revise failed problems.**

---

## 📚 Reference

The list uses **Striver's SDE Sheet** as its primary backbone.

Striver's SDE Sheet contains 191 problems, while this repository extends the coverage to 240 by adding important interview patterns that are useful for a broader preparation set.

- [Striver's SDE Sheet](https://takeuforward.org/dsa/strivers-sde-sheet-top-coding-interview-problems)

---

## 🔒 The 240-Problem Rule

This repository intentionally has a hard limit:

> **There must never be more than 240 problems in the master list.**

The current master list contains:

- **240 unique problems**
- **48 Easy**
- **158 Medium**
- **34 Hard**
- **0 duplicate LeetCode IDs**

New problems should **replace** an existing problem when necessary rather than increasing the total beyond 240.

This keeps the repository focused and prevents it from becoming another endless DSA problem dump.

---

## 🧩 Topics Covered

The master list covers:

- Arrays & Hashing
- Two Pointers
- Sliding Window
- Binary Search
- Linked Lists
- Stack & Queue
- Heap / Priority Queue
- Greedy
- Recursion & Backtracking
- Strings
- Binary Trees
- Binary Search Trees
- Trie
- Graph Fundamentals
- Union-Find / MST
- Shortest Paths
- Dynamic Programming - Fundamentals
- Dynamic Programming - Advanced
- Bit Manipulation
- Data Structure Design

---

## 🧠 Major Patterns

The selected problems collectively cover the following major interview patterns:

- Hashing and frequency maps
- Prefix and suffix techniques
- Kadane's Algorithm
- Boyer-Moore Voting
- Two Pointers
- Fast/Slow Pointers
- Sliding Window
- Monotonic Stack
- Monotonic Deque
- Binary Search
- Binary Search on Answer
- Intervals
- Heap / Priority Queue
- Top-K
- Two Heaps
- Greedy
- Recursion
- Backtracking
- Linked-list pointer manipulation
- Tree DFS / BFS
- Tree DP
- Lowest Common Ancestor
- BST invariants
- Trie
- Graph DFS / BFS
- Bipartite Graphs
- Topological Sort
- Union-Find / DSU
- Minimum Spanning Tree
- Dijkstra
- Bellman-Ford-style relaxation
- 0-1 BFS
- 1D / 2D Dynamic Programming
- Knapsack
- LIS
- LCS
- String DP
- Stock DP
- Interval DP
- Bit Manipulation
- Data-structure design
- LRU / LFU Cache

---

## ⭐ Priority System

Every problem has a priority level.

| Priority             | Meaning                                                                        |
| -------------------- | ------------------------------------------------------------------------------ |
| **Must Master**      | Pattern anchor. Should eventually be solvable from scratch without assistance. |
| **Interview Strong** | Important variation or deeper application of a known pattern.                  |
| **Core**             | Fundamental problem used to establish the underlying technique.                |
| **Specialist**       | Advanced problem intended for deeper exposure and difficult interviews.        |

Priority is about **learning value**, not simply difficulty.

---

## 📈 Recommended Progression

The repository is organized around conceptual dependencies rather than random LeetCode ordering.

```text
Arrays & Hashing
        ↓
Two Pointers
        ↓
Sliding Window
        ↓
Binary Search
        ↓
Linked Lists
        ↓
Stack / Queue
        ↓
Heap
        ↓
Greedy
        ↓
Recursion / Backtracking
        ↓
Strings
        ↓
Binary Trees
        ↓
BST
        ↓
Trie
        ↓
Graph Fundamentals
        ↓
Topological Sort
        ↓
Union-Find / MST
        ↓
Shortest Paths
        ↓
DP Fundamentals
        ↓
Advanced DP
        ↓
Bit Manipulation
        ↓
Data Structure Design
```

You do not have to solve every problem in a topic before moving forward. The progression is intended to make prerequisite relationships easier to understand.

---

## 🗂 Repository Structure

A recommended structure for the solutions is:

```text
.
├── README.md
├── DSA_Interview_Master_List_240.md
│
├── arrays-hashing/
│   ├── 0001-two-sum/
│   │   └── solution.cpp
│   ├── 0049-group-anagrams/
│   │   └── solution.cpp
│   └── ...
│
├── two-pointers/
│   ├── 0015-3sum/
│   │   └── solution.cpp
│   └── ...
│
├── sliding-window/
│   └── ...
│
├── binary-search/
│   └── ...
│
├── linked-lists/
│   └── ...
│
├── stack-queue/
│   └── ...
│
├── heap/
│   └── ...
│
├── greedy/
│   └── ...
│
├── recursion-backtracking/
│   └── ...
│
├── strings/
│   └── ...
│
├── binary-trees/
│   └── ...
│
├── bst/
│   └── ...
│
├── trie/
│   └── ...
│
├── graphs/
│   └── ...
│
├── union-find-mst/
│   └── ...
│
├── shortest-paths/
│   └── ...
│
├── dp-fundamentals/
│   └── ...
│
├── dp-advanced/
│   └── ...
│
├── bit-manipulation/
│   └── ...
│
└── data-structure-design/
    └── ...
```

The exact directory organization can evolve, but each solution should remain easy to locate from its **LeetCode ID and problem name**.

---

## 💻 Solution Format

Each problem solution should preferably contain:

1. Problem link.
2. Problem statement or a short restatement.
3. Pattern identification.
4. Approach.
5. Step-by-step reasoning.
6. Algorithm.
7. Complexity analysis.
8. Implementation.
9. Important edge cases.
10. Common mistakes, when useful.

A recommended solution template:

````markdown
# Two Sum

**LeetCode:** https://leetcode.com/problems/two-sum/

## Pattern

Hash Map

## Idea

Explain the key observation and why the selected pattern works.

## Approach

1. ...
2. ...
3. ...

## Complexity

- Time: O(...)
- Space: O(...)

## Solution

```cpp
// implementation
```
````

## Edge Cases

- ...
- ...

````

The implementation language can be changed according to the repository's needs.

---

## 📝 Master List

The complete canonical list is maintained separately:

**[DSA Interview Master List — 240 Problems](./DSA_Interview_Master_List_240.md)**

That file contains:

- Problem number
- LeetCode ID
- Problem name
- Topic
- Pattern
- Difficulty
- Priority
- Prerequisite
- Clickable LeetCode links

The Markdown master list should remain the **single source of truth** for the selected 240 problems.

---

## 🔄 Solving Workflow

A useful workflow for each problem:

```text
Read Problem
     ↓
Identify Constraints
     ↓
Try Brute Force
     ↓
Find the Bottleneck
     ↓
Identify Pattern
     ↓
Derive Optimized Approach
     ↓
Implement
     ↓
Test Edge Cases
     ↓
Analyze Complexity
     ↓
Record Mistakes
     ↓
Re-solve Later
````

The important part is not merely obtaining Accepted.

The objective is to understand **why a particular pattern is appropriate** and recognize that pattern when it appears in a different problem.

---

## 🧪 What "Solved" Should Mean

A problem should not be considered mastered simply because the submission was accepted.

A stronger progression is:

```text
Not Started
    ↓
Attempted
    ↓
Solved With Help
    ↓
Solved Independently
    ↓
Re-solved
    ↓
Mastered
```

### Mastered

A problem can be considered **Mastered** when you can:

- Identify the pattern quickly.
- Explain the approach without memorizing code.
- Implement it independently.
- State the time and space complexity.
- Handle common edge cases.
- Recognize at least one meaningful variation.

---

## 📊 Progress Tracking

A simple tracker can use:

| Status             | Meaning                                            |
| ------------------ | -------------------------------------------------- |
| `Not Started`      | Problem has not been attempted.                    |
| `Attempted`        | An independent attempt was made.                   |
| `Solved With Help` | Required hints, editorial, or solution assistance. |
| `Solved`           | Successfully solved independently.                 |
| `Re-solved`        | Successfully solved again after a delay.           |
| `Mastered`         | Pattern and implementation are reliable.           |

The goal is not to maximize the number of `Solved` entries.

The goal is to maximize the number of **patterns you can reliably recognize and implement under interview pressure**.

---

## 🚫 What This Repository Is Not

This repository is intentionally **not**:

- A collection of every popular LeetCode problem.
- A 500+ problem grind.
- A replacement for understanding DSA fundamentals.
- A collection of copied editorials.
- A race to maximize solved-problem counts.

The 240-problem limit exists to force selection.

---

## 🎯 Final Objective

By completing this repository properly, the target is to build a compact but broad interview toolkit covering:

```text
Data Structures
        +
Algorithmic Patterns
        +
Problem Recognition
        +
Implementation
        +
Complexity Analysis
        +
Interview Communication
```

The number **240** is the boundary.

The real objective is **pattern mastery**.

---

## 📌 Repository Principle

> **Do fewer problems deeply rather than hundreds superficially.**

If a new problem adds an important pattern that is missing, it may justify replacing an existing problem.

Otherwise, keep the list stable and focus on solving, revising, and mastering the existing set.
