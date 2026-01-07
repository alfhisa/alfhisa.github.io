---
title: "Jojo's Hardest Problem"
collection: teaching
permalink: /teaching/contoh-soal/jojoshardestproblem/
---

# Jojo's Hardest Problem (?)

Jojo is enjoying his vacation with his family when suddenly an instant message came in. Apparently, there is a message from Lili:

> *“Jojo, don’t forget to check the forum. Who knows if there is an assignment before the exam?”*

Jojo finally took the time to check the discussion forum and sure enough, there were some assignments given to his class. He immediately told his classmates.

Jojo then finds one difficult problem for himself as follows.

You are given an array containing **N elements** and also given an integer **M**. You need to find the maximum possible value of a function **f(x, k)** such that the value is **less than or equal to M**.

The value of **k** is arbitrary but must satisfy **k ≤ N**.

The function **f(x, k)** is defined as:

```
f(x, k) = A[x] × k + A[x + 1] × (k − 1) + ... + A[x + k − 1] × 1
```

Help Jojo to get the correct final answer.

---

## Input Format

- The first line contains an integer **T**, indicating the number of test cases.
- For each test case, the following **3 lines** are given:
  1. An integer **N**, the number of elements in the array.
  2. A line containing **N integers**, describing the elements **A[i]**.
  3. An integer **M**.

---

## Output Format

For each test case, output a single integer **Y**, the maximum value of function **f(x, k)** such that the value is **≤ M**.

---

## Constraints

- \( 1 \leq N \leq 4 \times 10^5 \)
- \( 1 \leq A[i] \leq 10^6 \)
- \( 1 \leq M \leq 10^{12} \)

---

## Sample Input 1

```
5
6 1 3 4 6
10
```

---

## Sample Output 1

```
10
```

---

## Sample Input 2

```
5
1 2 3 4 5
14
```

---

## Sample Output 2

```
13
```

---

## Explanation

For **test case 1**, the maximum result is:

```
f(3, 2) = 3 × 2 + 4 × 1 = 10
```
