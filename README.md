# Probabilistic Graphical Models Solutions
This repository is for discussion and organization of solution of exercise in PGM book.

## Chapter 2
### Exercise 2.1
Prove the following properties using basic properties of definition 2.1:

a. P(∅) = 0

![a](https://latex.codecogs.com/svg.latex?\begin{align*}P(\Omega)%20=%20P(\Omega%20\cup%20\varnothing)%20&=%20P(\Omega)%20+%20P(\varnothing)%20=%201%20\quad\text{(definition%202.1)}%20\\\\\Leftrightarrow%20P(\varnothing)%20=%201%20-%20P(\Omega)%20\\\\\therefore%20P(\varnothing)%20=%200\end{align*})

b. If α ⊆ β, then P(α) ≤ P(β).

![b](https://latex.codecogs.com/svg.latex?\begin{align*}P(\beta)%20&=%20P(\beta%20\cap%20U)%20=%20P(\beta%20\cap%20(\alpha%20\cup%20\alpha^{\mathsf{c}}))%20=%20P((\beta%20\cap%20\alpha)%20\cup%20(\beta%20\cap%20\alpha^{\mathsf{c}}))%20\\\\&=%20P(\beta%20\cap%20\alpha)%20+%20P(\beta%20\cap%20\alpha^{\mathsf{c}})%20%20\quad\text{(definition%202.1)}%20%20\\\\&=%20P(\alpha)%20+%20P(\beta%20\cap%20\alpha^{\mathsf{c}})%20\\%20\\&\geq%20P(\alpha)%20\quad%20(\because%20P(\beta%20\cap%20\alpha^{\mathsf{c}})%20\geq%200%20\quad%20\text{by%20definition%202.1}%20)\end{align*})

c. P(α ∪ β) = P(α) + P(β) - P(α ∩ β)

![c](https://latex.codecogs.com/svg.latex?\begin{align*}&%20P(\beta)%20=%20P((\beta%20\cap%20\alpha)%20\cup%20(\beta%20-%20\alpha))%20=%20P(\beta%20\cap%20\alpha)%20+%20P(\beta%20-%20\alpha)%20\quad%20\text{(definition%202.1)}%20\\\\&%20\Leftrightarrow%20P(\beta%20-%20\alpha)%20=%20P(\beta)%20-%20P(\beta%20\cap%20\alpha)%20\quad%20\quad%20\text{(1)}\end{align*})

![c](https://latex.codecogs.com/svg.latex?\begin{align*}P(\alpha%20\cup%20\beta)%20=%20P(\alpha%20\cup%20(\beta%20-%20\alpha))%20&=%20P(\alpha)%20+%20P(\beta%20-%20\alpha)%20%20\quad\text{(definition%202.1)}%20%20\\\\&=%20P(\alpha)%20+%20P(\beta)%20-%20P(\alpha%20\cap%20\beta)%20\quad%20\text{by%20(1)}\\%20\end{align*})

