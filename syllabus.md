---
title: Syllabus
layout: single
toc: true
toc_label: "Syllabus Contents"
---

## Purpose and Objectives

This course teaches the design, implementation, analysis, and proper
application of abstract data types, data structures, and their
associated algorithms. We will explore a wide variety of data
structures both conceptually and concretely via implementation. The
class involves a significant hands-on programming component; you will
both implement and use several data structures yourself. To summarize,
in this course you will:

After this course you will know how to:

  1. Understand the basic data structures commonly used in computer
     science, such as arrays, linked lists, stacks, queues, trees, and
     graphs.
  1. Analyze the time and space complexity of different algorithms,
     and understand the trade-offs between different data structures
     and algorithms.
  1. Implement basic algorithms, such as sorting and searching.
  1. Understand the principles of algorithm design, including
     divide-and-conquer, dynamic programming, and greedy algorithms.
  1. Use data structures and algorithms to solve real-world problems
     in an efficient and effective manner.

This syllabus contains policies and expectations I have established
for {{ site.title }}. Please read the entire syllabus before
continuing in this course. Policies and expectations may be modified
at any time by the course instructor. Notice of such changes will be
made by announcement in class, by written or email notice, or by
changes to this syllabus posted on the course website.

## Contact

The best way to get in contact for personal, private (FERPA, etc.)
messages is via my email address [{{ site.author.emailaddr }}]({{ site.author.email }}).
You should expect a response within 48 hours. If I deem it potentially
useful to others, I may anonymize your letter, answer it in an FAQ post
to the class, and forward you the link.

A regular way to reach out for help is via my [office hours]({{ site.baseurl }}/office-hours/).
Outside of my office hours, you should not expect to reach me by MS Teams chat.

## Additional Support

In addition to lecture, I provide the following additional resources.

### Scheduled Office Hours

My [office hours]({{ site.baseurl}}/office-hours/) are scheduled weekly, and I can also be available by appointment.

### Textbooks

 - Cormen et al. "Introduction to Algorithms, Fourth Edition". MIT Press (2022)
 - Aditya Bhargava. "Grokking Algorithms: An Illustrated Guide for Programmers and Other Curious People". Manning Publications (2016).

For the most part, lectures are intended to be standalone, with the
textbook as a supplement. Some topics will not be covered directly in
lecture; you will need to read the relevant textbook chapter before
class. The Cormen text is comprehensive but theoretical; the Grokking
text is an easier on-ramp.

### Supplementary Videos

I will link to supplementary videos about various {{ site.title }} topics.
Watch them early; they can help when you study and prepare for quizzes.


## Assessment

### Categories and weights

This is likely quite different from what you have seen in your other
classes, and will take some getting used to on your part. This system,
however, has a number of benefits for students---see [Why
Spec](why-specs**.

- Mid-term Exam (pen and paper, in class): 20%
- Final Exam, cumulative (pen and paper): 25%
- Algorithm Explanation Check (in person, individual): 15%
- In-class reading quizzes (best 15; about 18–22 offered): 25%
- Programming homeworks (6 autograded assignments, individual): 15%

Total: 100%.

Letter grades are computed from the weighted average using Seton Hall's recommended fixed grade cutoffs:

```
| Letter Grade | Range        |
|--------------+--------------|
| A            | 100% to 94%  |
| A-           | < 94% to 90% |
| B+           | < 90% to 87% |
| B            | < 87% to 84% |
| B-           | < 84% to 80% |
| C+           | < 80% to 77% |
| C            | < 77% to 74% |
| C-           | < 74% to 70% |
| D+           | < 70% to 67% |
| D            | < 67% to 64% |
| D-           | < 64% to 61% |
| F            | < 61% to 0%  |
```

### Exams

One in-class midterm and one cumulative final, both closed-book and
closed-notes. No electronics. Show work for partial credit. Dates for
Exam 1 will be announced in class; the Final Exam follows the
Registrar schedule.

### In-class reading quizzes

At the start of many class meetings we will have a 10-12 minute
paper quiz on assigned readings and on recent material. Slides are not
distributed before class; the reading primes the topic that follows in
the lecture deck. Quizzes are closed-notes. We drop all but your best
15 quiz scores to cover routine conflicts. No make-ups.

### Programming Assignments (autograded, pair-programming)

This class features six programming homeworks. Programming assignments are to be done in pairs, chosen at your discretion, and submitted on Gradescope.

When evaluating your programming submissions, I will give you feedback regarding where they fell short as well as assign one of the following outcomes:

- Got it: your submission implements the specification correctly and in full.
- Almost there: your submission implements the specification with minor mistakes or omissions.
- On the way: your submission has elements of a correct solution, but requires non-trivial further work to be correct and/or complete.
- Not yet: your submission requires significant further work.
- Cannot assess: I could not evaluate your submission as is; repairs are required before I can do so.

For grading with points, each outcome maps to a percentage of the assignment’s points:

- Got it = 100%
- Almost there = 85%
- On the way = 65%
- Not yet = 35%
- Cannot assess = 0% (until repaired and resubmitted as your redo)

Each homework is worth the same share of the “Programming homeworks” category in the grading breakdown. Your score on a homework is the percentage above multiplied by that homework’s points.

### Resubmissions

Making mistakes and correcting them is a natural part of the learning process. An outcome of On the way or Not yet is not a failure; it means you still have things to learn.

You may resubmit that homework assigment one week after the initial deadline. To determine your recorded homework score, I use the best of the two outcomes (initial or redo) converted by the outcome map above. If your initial outcome was Cannot assess, you must repair it before the redo; otherwise the recorded score remains 0.

### Autograder and materials protection

- Hidden tests and randomized instances are used. Only minimal sample tests are published; full suites and outputs are not released.
- We may require an in-person spot check where you explain your code. If you cannot explain your own work, the homework score may be set to zero under the academic integrity policy.
- Do not post prompts, tests, or solutions during or after the term.

### Algorithm explanation check (in person, choose one option)

Every student must complete one brief, individual, no-notes
explanation in my office. These will be ~10-minute slots signed up for
in my office; you'll get one attempt plus one re-try in the following
week if needed.

<!-- Option A: Pick-from-list algorithm explanation -->
<!-- - You choose one algorithm from the published list (for example: -->
<!-- Dijkstra, Kruskal with DSU, open addressing with linear probing, -->
<!-- red-black tree insert/fixup, dynamic array amortized analysis). -->
<!-- - In the meeting you will: state the core idea, trace the algorithm on -->
<!-- a fresh instance I provide, state the key invariant or lemma, give the -->
<!-- running time, and answer one targeted "what if" variant. -->

<!-- Option B: CLRS pseudocode deep dive -->
<!-- - You are assigned a specific CLRS pseudocode (for example: CLRS 6 -->
<!-- Build-Heap, CLRS 11 Chained Hash-Insert, CLRS 13 RB-Insert-Fixup). -->
<!-- - In the meeting you will: explain preconditions, state the loop -->
<!-- invariants, justify correctness at the level of the book, trace a -->
<!-- fresh instance, and answer one targeted "what if" variant. -->

#### Scoring and weight

This is scored as pass/fail using a simple rubric: idea, trace,
invariant, what-if. This is a pass requirement. Failing to pass after
one re-try caps the course grade at D+.

### Preparation and reading

Assigned reading will be listed on the Schedule page each week.
Read before class. Quizzes target that preparation and the previous
class's content. Slides are not posted before class.

## Late Policy

Unless otherwise indicated, assignments are due by 09:59 p.m. on their
due date. Dropboxes close automatically, and late is late.

Each student starts with three late tokens. Each token can be exchanged
for a two-day no questions asked extension on a non-exam assignment,
including a homework redo. Only one token can be used per submission.
Late tokens are applied automatically when you submit late. The two-day
window begins at the time of your late submission. If you run out of
tokens, I will reach out. Quizzes and exams are in-class and are not
eligible for late tokens.

Barring extreme circumstances, no additional ad-hoc extensions will be
granted. If you require further flexibility, contact your dean of
students and have them contact me.

## Academic Integrity

It's OK to meet with colleagues, form study groups, discuss
assignments, compare high-level approaches, and go over examples from
texts. It is never OK to share code or solutions or to see someone
else's code or solutions. What you turn in must be your own work.
Copying code, solution sets, test cases, or materials from prior terms
or the web is strictly prohibited. Tools that automatically generate
code or solutions are prohibited unless I explicitly authorize them.
Acknowledge any help you received by listing names and sources in your
submission.

There will be no tolerance for cheating and plagiarism. Any material
that is not entirely your own work must be indicated and cited. You
must not share, post, or publicize course materials (homeworks, exams,
solutions, test cases, or your submissions), including after the term.

I may require you to explain any non-exam work in person as a
condition of receiving credit.

## Academic Accommodations

It is the policy and practice of Seton Hall University to promote
inclusive learning environments. If you have a documented disability
you may be eligible for reasonable accommodations in compliance with
University policy, the Americans with Disabilities Act, Section 504 of
the Rehabilitation Act, and/or the New Jersey Law against
Discrimination. Please note, students are not permitted to negotiate
accommodations directly with professors. To request accommodations or
assistance, please self-identify with the Office for Disability
Support Services (DSS), Duffy Hall, Room 67 at the beginning of the
semester. For more information or to register for services, contact
DSS at (973) 313-6003 or by [e-mail](mailto:DSS@shu.edu), or visit
their [webpage](https://www.shu.edu/disability-support-services/index.cfm).

## Equity and Compliance

Consult the university's [relevant information and policies](https://www.shu.edu/title-ix/index.cfm). Federal
regulations and University policy require me to promptly convey certain
reports to the Title IX Coordinator.

## Technology and Platforms

We will use a variety of tools and platforms to facilitate teaching
and learning. See the technology page at {{ site.baseurl }}/tech/ for
details.

## Acknowledgments

Thanks over the years for inspiration and content from at least the
following: Dan Friedman, Shriram Krishnamurthi, Lindsey Kuper, Vincent
St-Amour, Jessie Tov, and Marco Morazán.

![In the syllabus]({{ site.baseurl }}/assets/images/syllabus.gif "Might just be worth checking.")
