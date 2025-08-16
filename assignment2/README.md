# Assignment 2: Skip Lists & Hash Tables

This directory contains my solution to the second data structures assignment.

## Overview
- **Skip lists** – probabilistic data structures that support fast search, insertion and deletion. Implemented here via `AbstractSkipList` and `IndexableSkipList`, with helpers in `SkipListUtils`.
- **Hash tables** – a variety of open addressing and separate chaining hash tables:
  - `ChainedHashTable` implements separate chaining with linked lists.
  - `ProbingHashTable` implements open addressing using probing.
  - Modular and multiplicative hashing (`ModularHash`, `MultiplicativeShiftingHash`) plus `HashFactory` and `HashFunctor` to generate hash functions.
  - Utilities (`HashingUtils`, `HashingExperimentUtils`) assist with experiments and analysis.
- Shared support files like `IntegrityStatement` and `Element` are also provided.

The assignment instructions are in [Data_Structure_2025_Assignment3.pdf](./Data_Structure_2025_Assignment3.pdf). See this PDF for a full description of the tasks and submission guidelines.

## How to compile and run
Navigate to this directory and compile all classes:

```bash
javac *.java
```

You can then run experiments or test individual data structures using:

```bash
java ClassName
```
