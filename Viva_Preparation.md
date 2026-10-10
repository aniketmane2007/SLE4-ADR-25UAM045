# SLE-4 Viva Preparation

**Course:** 02AML204 – Introduction to Artificial Intelligence  
**Project:** 8-Puzzle Search Performance Comparison  
**Student:** Aniket Anandrao Mane  
**PRN:** 25UAM045

## 1. What is an Architecture Decision Record (ADR)?
An ADR records an important design decision, its context, alternatives, justification, and consequences.

## 2. Why compare BFS and DFS?
To compare how two search strategies behave on the same documented puzzle state using node expansions and execution time.

## 3. What were the recorded SLE-2 results?
For the documented test case, BFS expanded 33 nodes and averaged 0.0541 ms. DFS expanded 2,927 nodes and averaged 3.2204 ms. Both reported finding the goal.

## 4. What is the difference between BFS and DFS?
BFS explores states level by level using a queue. DFS explores deeper states first using a stack, and in this implementation it uses a depth limit.

## 5. Does this prove BFS is always better?
No. These results are for one documented test case. Performance can change with the initial state, exploration order, implementation, and search limits.

## 6. What is one limitation of BFS?
BFS can use substantial memory because it stores states waiting to be explored.

## 7. What does the C4 model describe?
It describes a system at four levels: Context, Container, Component, and Code.

## 8. How does SLE-3 relate to this decision?
The C4 design describes the search system and its responsibilities, including the search engine and the functions that support state exploration.

## 9. What should you say about AI assistance?
Explain truthfully which AI assistance you used and identify the code, tests, results, diagrams, and writing you personally completed or verified.

## Before the viva
- Review your actual code and diagrams.
- Make sure you can explain the queue, stack, visited-state tracking, and depth limit.
- Verify the performance values against your submitted report.
- Do not claim the program reconstructs a complete solution path unless that feature is implemented and tested.
