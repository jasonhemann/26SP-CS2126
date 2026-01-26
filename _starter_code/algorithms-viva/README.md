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
url](https://calendar.app.google/Une5wVth6iP6dcMd6) before the window
opens. If no posted time works, email alternatives at least 96 hours
before the window closes. Arrive 2 minutes early. Late arrivals may be
asked to reschedule within the same window if capacity allows.
Un-communicated no-shows count as an attempt and receive a score of
zero for that attempt.

---

## Format

See the [viva page](../../viva.md) for a general_description of the format.

In this case, I will choose the exact topic at the door from the published pool below.

### Topic Pool (Spring 2026 window)

1. **Breadth-First Search (BFS) and shortest paths in unweighted graphs**
   Required ideas: predecessor tree, layer structure, O(V+E) bound, why tree paths are shortest.
   Cormen: 20.2.

2. **Depth-First Search (DFS) and Topological Sort**
   Required ideas: discovery/finish times, edge types, white-path idea, why topological sort based on finish times is correct.
   Cormen: 20.3 and 20.4.

3. **Binary Heaps and Heapsort**
   Required ideas: array layout, heap property, BUILD-HEAP, EXTRACT-MAX/MIN, why heapsort is in-place O(n log n).
   Cormen: Chapter 6.

4. **Minimum Spanning Trees**
   (I will specify either **Kruskal** with union-find or **Prim** with a binary heap.)
   Required ideas: cut property, why the greedy choice is safe, running-time analysis based on data structures.
   Cormen: Chapter 21.

5. **Binary Search Trees (BST): search, insert, delete**
   Required ideas: BST invariant, how delete handles the three cases, cost in terms of tree height, why correctness holds.
   Cormen: Chapter 12.

Note: I may ask you to compare two items (for example, why Prim vs. Kruskal has a different cost profile with different data structures).

---

## What to Know Cold

Use this checklist as you prepare. If you cannot do each item from memory, keep studying.

- **Problem statement:** One or two precise sentences about what the algorithm computes or what the structure supports.
- **Core invariant or safety argument:** The one fact that stays true and makes the method correct.
- **Procedure outline:** The steps in order, including any key subroutines and what each returns or maintains.
- **Complexity:** Tight bound with a short justification and the parameterization that matters (e.g., V, E, n, h).
- **Edge cases:** What happens with empty inputs, ties, disconnected graphs, duplicates, or degenerate trees.
- **Small instance:** Be ready to run a clean 5-10 node graph or a 6-8 element array/tree without hesitation.

---


## Grading

You will be scored on four dimensions, each 0-3. Total out of 12 points.

- **Statement and Setup (0-3):** States the problem, defines terms, names the key idea.
  3 = precise and complete; 2 = one minor omission; 1 = vague or partial; 0 = incorrect.
- **Mechanism and Trace (0-3):** Reconstructs the steps correctly and executes them in order.
  3 = correct steps with steady control; 2 = one small slip self-corrected; 1 = multiple slips; 0 = cannot proceed.
- **Correctness Argument (0-3):** Gives the invariant or cut/exchange argument and ties it to steps.
  3 = crisp and targeted; 2 = generally right but imprecise; 1 = hand-wavy; 0 = incorrect.
- **Transfer and Edges (0-3):** Handles follow-ups on complexity, variants, or edge cases.
  3 = handles two follow-ups cleanly; 2 = handles one; 1 = struggles; 0 = cannot answer.

**Hard stop:** Misstating the algorithm fundamentally (e.g., using the wrong data structure) or failing to run a small instance leads to
an automatic redo recommendation regardless of point total.

**Score to letter mapping for this assignment:**
10-12 = A range, 8-9 = B range, 7 = C range, 6 or below = D/F range.

**Redo policy:** For this assignment, one redo is allowed within one
week of your original slot (or within the posted redo window). Your
recorded viva grade is the higher of the two attempts. You should not
expect a second try at the same question.

---

## Academic Integrity

You may study with peers, but the performance is individual and
unscripted. External solution scripts or hidden notes defeat the point
and violate course policy. If you discuss preparation with others,
acknowledge them in a short note when you book.

---

## Example Prompt Styles

- "Run BFS from s on this graph. Show the predecessor tree and explain why the path you print is shortest."
- "Perform a topological sort and explain why the finish-time rule works."
- "Build a max-heap from this array and show two EXTRACT-MAX operations. Explain the running time."
- "Use Kruskal on this graph. Name the cut property you are relying on and show union-find effects."
- "Delete this key from the BST. Name the invariant and argue correctness in one minute."

Prepare to do any one of these from the topic pool, on a fresh instance.
