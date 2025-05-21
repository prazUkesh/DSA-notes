# Deterministic & Non-deterministic Algorithm

| Deterministic | Non-deterministic|
|----|----|
| different input will result in different output | same output will result in different output |


## Reduction
Consider we have wo decsion problems P1 & P2

```
P1 -> Input (I1)
P1 -> Algorithm(A1)


P2 -> Input (I2)
P2 -> Algorithm(A2)

```
if P1 can be solved with the help of A2, then we convert input Z1 into Z2 and field solution 
This process notifies that P1 is related to P2  

---
P-> polynomial Time
NP -> Non deterministic Polynomila Time

P-> Problem which can be solved in Polynomial Time
NP -> Problem which cannot be solved in Polynomial Time

Polynomial time
- which takes less time
- eg. linear search: n
- eg. binary search:

Exponential time
- takes more time even if its a small problem
- Eg. KnapSack Problem, Traveling Sales Man Problem
