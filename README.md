# FDS-assigment1

Fundamental Data Structures — Assignment 1: Implementation and analysis of core data structures in Python/C++.

## Contents

| File | Description |
|------|-------------|
| `array_list.py` | Dynamic array implementation with amortized analysis |
| `linked_list.py` | Singly/doubly linked list with iterator |
| `stack_queue.py` | Stack (array/linked) and Queue (circular buffer) |
| `binary_tree.py` | Binary tree, BST, traversals (in/pre/post/order) |
| `heap.py` | Min/Max heap, heapify, heapsort |
| `hash_table.py` | Hash table with chaining/open addressing |
| `graphs.py` | Adjacency list/matrix, BFS, DFS, Dijkstra |
| `analysis.md` | Time/space complexity proofs |

## Data Structures Covered

1. **Arrays** — Dynamic resizing, amortized O(1) append
2. **Linked Lists** — Singly, doubly, circular
3. **Stacks** — LIFO, array + linked implementations
4. **Queues** — FIFO, circular buffer, priority queue
5. **Trees** — Binary, BST, AVL (bonus), traversals
6. **Heaps** — Binary heap, heapify O(n), heapsort O(n log n)
7. **Hash Tables** — Separate chaining, linear/quadratic probing
8. **Graphs** — Adjacency list/matrix, BFS/DFS, shortest path

## Run

```bash
# Python
python -m pytest tests/ -v

# C++
g++ -std=c++17 *.cpp -o fds && ./fds
```

## Complexity Summary

| Structure | Access | Search | Insert | Delete |
|-----------|--------|--------|--------|--------|
| Array | O(1) | O(n) | O(n) | O(n) |
| Linked List | O(n) | O(n) | O(1)* | O(1)* |
| Stack | O(n) | O(n) | O(1) | O(1) |
| Queue | O(n) | O(n) | O(1) | O(1) |
| BST | O(log n) | O(log n) | O(log n) | O(log n) |
| Heap | O(n) | O(n) | O(log n) | O(log n) |
| Hash Table | O(1) | O(1) | O(1) | O(1) |
| Graph | O(V+E) | O(V+E) | O(1) | O(1) |

*At head/tail

## Academic Context

Course: Fundamental Data Structures (CS201)
Semester: Spring 2025
Institution: [University]