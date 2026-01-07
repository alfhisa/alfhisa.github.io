---
title: "Temperature"
collection: teaching
permalink: /teaching/contoh-soal/temperature/
---

WorldTemperature.com is a website that lists various temperatures of cities all over the world.  
On their website, some cities use different temperature metrics: **Celsius (C)** and **Fahrenheit (F)**.

They want to add a feature to **sort the list of cities based on their temperature**, from the **coldest to the hottest**, while still keeping the **original temperature metric** for each city.

---

## Input Format

- All temperature data are stored in a file named **`testdata.in`** with a maximum of **N lines**.
- Each line contains **three data**, separated by `#`:
  - City Name
  - Temperature
  - Metric (`C` or `F`)

---

## Output Format

Output **N lines** of temperature data sorted from the **coldest to the hottest** city.

If two or more cities have the **same temperature**, sort them by **city name in ascending order (A–Z)**.

The output format must be:

```
[city name] is [temperature][metric]
```

- Use **two decimal places** for the temperature value.

---

<!-- ## Constraints

- \( 1 \leq N \leq 100 \)
- \( 1 \leq \text{Length of City Name} \leq 1000 \)
- \( -60 \leq \text{temperature} \leq 224 \)

--- -->

## Sample Input

```
Jakarta#28#C
New York#37.4#F
Tokyo#9#C
London#9#C
Singapore#27#C
Vancouver#-1#C
Taipei#64.4#F
Denver#-4#C
Santiago#69.8#F
New Delhi#11#C
```

---

## Sample Output

```
Denver is -4.00C
Vancouver is -1.00C
New York is 37.40F
London is 9.00C
Tokyo is 9.00C
New Delhi is 11.00C
Taipei is 64.40F
Santiago is 69.80F
Singapore is 27.00C
Jakarta is 28.00C
```

---

## Notes

To compare temperatures, convert all values to **Celsius** using the formula:

```
Celsius = (Fahrenheit - 32) × 5 / 9
```

The output must still use the **original temperature metric**.
