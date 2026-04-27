---
title: Algorithms Viva (Office-Hour Oral Exam)
layout: single
toc: true
---

# Algorithms Viva

See the [general_description](../../viva.md) of what these will entail.

This will be a short, individual, in-person oral where you explain a
core algorithm or data structure from our syllabus, walk through a
small example on the board, and answer follow-up questions. No notes
or slides.

We do this to verify that you have internalized the material at the
level of Cormen and can reconstruct the mechanism, reason about why it
works, and apply it to a fresh instance. Pre-scripted speeches tend
not to pass. Expect me to change the instance or ask you to adapt the
steps.

# Booking and Logistics

Sign-up link and slots will appear at [this
url](https://calendar.app.google/f8mh4KXybNorL5TbA) before the window
opens. Book a slot between **2026-04-28** and **2026-05-01**. If no
posted time works, email alternatives at least 96 hours before the
window closes. Arrive 2 minutes early. Late arrivals may be asked to
reschedule within the same window if capacity allows. Un-communicated
no-shows count as an attempt and receive a score of zero for that
attempt.

---

## Format

See the [viva page](../../viva.md) for a general_description of the format.

In this case, I will choose three topics at the door from the
published pool below; you can choose which of those you want to be
tested on. The topics are as follows:

### Topic Pool (Spring 2026 window)

- **Breadth-first search (BFS)**
- **Depth-first search (DFS) path-finding**
- **Depth-first search (DFS) cycle detection**
- **Iterative deepening depth-first search**
- **Topological sort**
- **Strongly connected components**
- **Bellman-Ford single-source shortest paths (with negative-cycle detection)**
- **Dijkstra's single-source shortest paths**
- **Dictionaries, incl. association lists**
- **Open indexing arrays**
- **Hash tables**
- **Priority queues**, implemented with unsorted lists, sorted lists, or binary heaps
- **Heapsort**, heaps, heap properties
- **Union-find / disjoint sets**, with and without path compression
- **Kruskal's algorithm**
- **Prim's algorithm**
- **Binary search trees**
- **AVL trees**

For data-structure topics, I may ask you to compare two
implementations of the same abstract data type (for example,
association list vs. hash table, hash table vs. BST, or BST vs. AVL).

### Source material, by section (in addition to slides/notes)

1. **Breadth-first search (BFS) and shortest paths in unweighted graphs**
   Required ideas: predecessor tree, layer structure, O(V+E) bound, why tree paths are shortest.
   Cormen: 20.2.

2. **Depth-first search (DFS), topological sort, and strongly connected components**
   Required ideas: discovery/finish times, DFS forests, edge classification, the white-path intuition, why finish-time order yields a topological sort, and the role of reversed edges in SCCs.
   Cormen: 20.3, 20.4, and 20.5.

3. **Single-source shortest paths**
   Required ideas: relaxation, when Bellman-Ford is needed, how negative-cycle detection works, when Dijkstra is valid, and running-time tradeoffs across implementations.
   Cormen: shortest-path sections; slides/notes for any course-specific variants.

4. **Dictionaries, association lists, and hash tables**
   Required ideas: the dictionary ADT; search/insert/delete; tradeoffs between association lists and hashed implementations; collisions, load factor, and the mechanics of open indexing; expected versus worst-case cost.
   Cormen: hash-table chapter/sections; slides/notes for association lists and open indexing terminology.

5. **Priority queues, binary heaps, and heapsort**
   Required ideas: the priority-queue interface; tradeoffs between unsorted lists, sorted lists, and binary heaps; array layout; heap property; BUILD-HEAP; EXTRACT-MIN/MAX; why heapsort is in-place O(n log n).
   Cormen: Chapter 6.

6. **Union-find / disjoint sets and minimum spanning trees**
   Required ideas: representatives, union and find, weighted union, path compression, cut property, why the greedy choice is safe, and running-time analysis based on the underlying data structures.
   Cormen: disjoint-set and MST chapters/sections.

7. **Binary search trees and AVL trees**
   Required ideas: BST invariant, search/insert/delete, rotations, rebalancing after updates, cost in terms of tree height, and why balancing matters for dictionary operations.
   Cormen: Chapter 12 for BSTs; slides/notes for AVL trees.

Note: I may ask you to compare two nearby items (for example, association list vs. hash table, binary heap vs. sorted-list priority queue, or Prim vs. Kruskal with different supporting data structures).

## What to Know Cold

Use this checklist as you prepare. If you cannot do each item from
memory, keep studying.

- **Problem statement or ADT contract:** One or two precise sentences about what the algorithm computes or what operations the structure supports.
- **Core invariant or representation law:** The fact that stays true and makes the method correct.
- **Procedure or operations:** The steps in order, or the behavior of search/insert/delete/update operations.
- **Complexity:** Tight bounds with a short justification and the parameterization that matters (for example V, E, n, h, or expected vs. worst-case).
- **Edge cases:** What happens with empty inputs, ties, disconnected graphs, duplicates, collisions, or degenerate trees.
- **Small instance:** Be ready to run a clean 5-10 node graph or a 6-8 element array/table/tree without hesitation.

## Grading

You will be scored on four dimensions, each 0-3. Total out of 12
points.

- **Statement and Setup (0-3):** States the problem, defines terms, names the key idea.
  3 = precise and complete; 2 = one minor omission; 1 = vague or partial; 0 = incorrect.
- **Mechanism and Trace (0-3):** Reconstructs the steps correctly and executes them in order.
  3 = correct steps with steady control; 2 = one small slip self-corrected; 1 = multiple slips; 0 = cannot proceed.
- **Correctness Argument (0-3):** Gives the invariant, representation law, or cut/exchange argument and ties it to the steps.
  3 = crisp and targeted; 2 = generally right but imprecise; 1 = hand-wavy; 0 = incorrect.
- **Transfer and Edges (0-3):** Handles follow-ups on complexity, variants, or edge cases.
  3 = handles two follow-ups cleanly; 2 = handles one; 1 = struggles; 0 = cannot answer.

**Hard stop:** Fundamentally misstating the algorithm or data
structure, using the wrong invariant, or being unable to run a small
instance leads to an automatic redo recommendation regardless of point
total.

**Score to letter mapping for this assignment:**
10-12 = A range, 8-9 = B range, 7 = C range, 6 or below = D/F range.

**Redo policy:** For this assignment, one redo is allowed within one
week of your original slot (or within the posted redo window). Your
recorded viva grade is the higher of the two attempts. You should not
expect a second try at the same question.

## Academic Integrity

You may study with peers, but the performance is individual and
unscripted. External solution scripts or hidden notes defeat the point
and violate course policy. If you discuss preparation with others,
acknowledge them in a short note when you book.

## Example Prompt Styles

- "Run BFS from s on this graph. Show the predecessor tree and explain why the path you print is shortest."
- "Perform DFS on this graph, identify whether it has a cycle, and explain how finish times support a topological sort."
- "Explain the dictionary ADT, then compare association lists and hash tables with open indexing for search, insert, and delete."
- "Insert these keys into a hash table using open indexing. Show the probe sequence and explain what changes on lookup or deletion."
- "Show two INSERT operations and one EXTRACT-MIN on a binary heap, then compare that representation to a priority queue implemented with an unsorted list."
- "Use Kruskal on this graph. Name the cut property you are relying on and show the union-find effects."
- "Insert these keys into an AVL tree and show any rotation(s) needed."

Prepare to do any one of these, on a fresh instance, from the topic
pool above.
