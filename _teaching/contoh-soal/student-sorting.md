---
title: "Student Sorting"
collection: teaching
permalink: /teaching/contoh-soal/student-sorting/
---

Howard is a teacher who has many students. One day, Howard combined all his student lists into a document randomly.  
Howard wants to make the document **ordered by student identification number**, and he asks for your help.

---

## Input Format

Read input from file **`testdata.in`**.

- The first line consists of one integer **N**, the number of students.
- The next **N lines** each contain two fields separated by a space:
  - **R** — student identification number
  - **M** — student's name

---

## Output Format

Output should be expressed in the format:

```
R M
```

The output must be **sorted by R in ascending order**.

---

<!-- ## Constraints

- \( 1 \leq N \leq 1000 \)
- \( |R| = 10 \) (length of string **R**)
- \( 1 \leq |M| \leq 20 \)
- **R** only consists of digits `0–9`
- **M** only consists of letters `a–z` and `A–Z`

--- -->

## Sample Input

```
10
2020123464 Oliver
2020123461 Benjamin
2020123458 William
2020123460 Logan
2020123457 Noah
2020123462 Mason
2020123456 Liam
2020123459 James
2020123463 Elijah
2020123465 Jacob
```

---

## Sample Output

```
2020123456 Liam
2020123457 Noah
2020123458 William
2020123459 James
2020123460 Logan
2020123461 Benjamin
2020123462 Mason
2020123463 Elijah
2020123464 Oliver
2020123465 Jacob
```
