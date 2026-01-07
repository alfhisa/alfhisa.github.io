---
title: "Jojo and Median"
collection: teaching
venue: ""
location: ""
date: ""
permalink: /teaching/contoh-soal/jojo-and-median/
---

# Jojo and Median

Jojo and Lili have just learned statistics in their school. However, Jojo fell asleep when the teacher was explaining about the concept of **median**. As Jojo doesn’t want to get bad grades, he asked Lili to explain it to him.

Lili explained that the **median** is the *middle value of a sorted list*. She then gave Jojo a list of items, each with its own **ID**, **name**, and **price**, and asked him to list all the IDs and names of all items which have prices **equal to or above the median price**.

Fortunately, the list Lili gave is already **sorted by price**. As Jojo is still confused, he has asked you to help him finish this task.

---

## Input Format

- A single line with an integer **N**, denoting the number of items.
- This is followed by **3 × N lines**, where each group of 3 lines contains:
  1. **ID** of the item  
  2. **S** — the name of the item  
  3. **P** — the price of the item  

---

## Output Format

Print the **IDs and names** of all items that are priced **equal to or above the median price**, in the **order of input**.

---

## Constraints

- \( 1 \leq N \leq 3 \times 10^4 \)
- The ID of an item is a string containing **exactly 8 numerical digits**
- \( 1 \leq |S| \leq 15 \)
- \( 1 \leq P \leq 10^{12} \)

---

## Sample Input 1

```
3
12345678
Apel
2500
12345679
Jeruk
2750
12345786
Mangga
3000
```

---

## Sample Output 1

```
12345679 Jeruk
12345786 Mangga
```

---

## Sample Input 2

```
4
12345678
Ayam Geprek
15000
11111111
Bakmie Ayam
20000
12121212
Nasi Padang
20000
12341234
Steak Ayam
30000
```

---

## Sample Output 2

```
11111111 Bakmie Ayam
12121212 Nasi Padang
12341234 Steak Ayam
```

---

## Notes

- The list of items is already **sorted by price**.
- If **N** is even, the median is defined as the **upper middle value**.
