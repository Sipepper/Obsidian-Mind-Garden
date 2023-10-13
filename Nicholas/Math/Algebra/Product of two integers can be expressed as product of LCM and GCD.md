---
Last time checked: 2023-10-12
Complete: true
aliases:
---
# Product of two integers can be expressed as product of LCM and GCD
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Direct strict note
>Let $a,b\in\mathbb{Z}$. Then
>$$ab=\operatorname{sign}(ab)\cdot\operatorname{gcd}(a,b)\cdot\operatorname{lcm}(a,b)$$

>[!proof]+
>As 
>$$m\cdot n=\min\{m,n\}\cdot\max\{m,n\}\quad\forall m,n\in\mathbb{N}$$
>we can represent $ab$ in the following form:
>$$\begin{align}ab&=\prod\limits_{i}p_{i}^{\alpha_{i}}\cdot\prod_{j}p_{j}^{\beta_{j}}\\&=\prod_{k}p_{k}^{\min\{\alpha_{k},\beta_{k}\}}\cdot\prod_{l}p_{l}^{\min\{\alpha_{l},\beta_{l}\}}\\ &=\operatorname{gcd}(a,b)\cdot\operatorname{lcm}(a,b) \end{align}$$
>The last step is true by properties of [[least common multiple]].

>[!example]+ 
>For example, $6\cdot20=120=2\cdot 60$.
***
#### Keywords
- [[Set of integers]],
- [[Sign function]],
- [[Greatest common divisor]],
- [[Least common multiple]],
- [[Fundamental theorem of arithmetic]]
#### Possibly related
- 
***
#### Sources: