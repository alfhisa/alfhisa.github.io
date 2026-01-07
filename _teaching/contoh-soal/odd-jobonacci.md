---
title: "Odd Jobonacci"
collection: teaching
permalink: /teaching/contoh-soal/odd-jobonacci/
---

Jojo is a genius in mathematics, especially in numerical sequences. He also created his own series called **Jobonacci**.

Jobonacci is a sequence defined as follows:

- \( jobonacci[n] = jobonacci[n-1] + jobonacci[n-2] \)
- If **n is an odd number**, then **jobonacci[n] = 1**

You are a friend of Jojo who is making guesses about the Jobonacci series. To avoid losing to him, you need to create a program that can answer Jojo’s questions quickly.

You are **encouraged to use recursive techniques** to solve this problem.

---

## Input Format

Input consists of **1 integer N**, representing Jojo’s question about the Jobonacci series.

---

## Output Format

Output a single line containing the **N-th Jobonacci number**.

---

<!-- ## Constraints

- \( 1 \leq N \leq 25 \)

--- -->

## Sample Input

```
6
```

---

## Sample Output

```
3
```

---

## Notes

Assume the following base cases:

- `jobonacci[0] = 0`
- `jobonacci[1] = 1`
- `jobonacci[2] = 1`
- `jobonacci[3] = 1`
