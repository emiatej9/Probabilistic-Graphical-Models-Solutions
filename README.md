# Probabilistic Graphical Models Solutions
This repository is for discussion and organization of solution of exercise in PGM book.

## Chapter 2
### Exercise 2.1
Prove the following properties using basic properties of definition 2.1:

a. P(∅) = 0

![a](https://latex.codecogs.com/svg.latex?\begin{align*}P(\Omega)%20=%20P(\Omega%20\cup%20\varnothing)%20&=%20P(\Omega)%20+%20P(\varnothing)%20=%201%20\quad\text{(definition%202.1)}%20\\\\\Leftrightarrow%20P(\varnothing)%20=%201%20-%20P(\Omega)%20\\\\\therefore%20P(\varnothing)%20=%200\end{align*})

```
P(Ω) = P(Ω ∪ ∅)
     = P(Ω) + P(∅) (by definition 2.1)
     = 1
     
∴ P(∅) = 0
```
