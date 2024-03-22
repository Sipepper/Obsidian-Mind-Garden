---
Last time checked: 2024-03-03
Complete: false
aliases:
---
# Cantor space
***
###### tags: #Topology #Fundamental_math_objects 
***
>[!dsn]+ Definition
>Suppose we have a closed interval $[0,1]$ and we starting to remove "middle thirds" from it as follows
>$$G_{1}=\left[0,\frac{1}{3}\right]\cup\left[\frac{2}{3},1\right]$$
>$$G_{2}=\left[0,\frac{1}{9}\right]\cup\left[\frac{2}{9},\frac{1}{3} \right]\cup\left[\frac{2}{3},\frac{7}{9}\right]\cup\left[\frac{8}{9},1\right]$$
>$$\vdots$$
>as depicted on a diagram
>![[Pasted image 20220720141610.png]]
>we obtain a nested sequence of such sets
>$$G_{1}\supset G_{2}\supset G_{3}\supset\dots\supset G_{n}\supset\dots$$
>The *Cantor space* $G$ is a space which is homeomorphic to the intersection 
>$$\bigcap\limits_{n=1}^{\infty}G_{n}$$
>As every $G_{n}$ is closed and $[0,1]$ is compact, $G$ is also compact.^[[[Sidney A. Morris - Topology without tears.pdf#page=222|Sidney A. Morris - "Topology without tears" p.222-223]]]

>We can view elements of middle third cantor space as a real numbers expressed in $3$*-adic* number system, that is
>$$0,\alpha_{1}\alpha_{2}\dots=\frac{\alpha_{1}}{3}+\frac{\alpha_{2}}{3^{2}}+\dots$$
>with integral coefficients $0$ or $2$.
>>[!proof]+
>>

>We can construct a bijection between set of binary sequences and Cantor middle thirds space as follows
>$$\psi:\sum\limits_{i\ge0}a_{i}2^{i}\mapsto\sum\limits_{i\ge0}\frac{2a_{i}}{3^{i+1}}\quad\mathbb{Z}_{2}\to G$$
>.^[[[Alain M. Robert - A course in p-adic analysis.pdf#page=24 |Alain M. Robert - "A course in p-adic analysis" p.8]]]
>>[!proof]+
>>

***
#### Keywords
- [[Open and closed subsets]],
- [[Interval]],
- [[Sequence]],
- [[Set]],
- [[Homeomorphism]],
- [[Compact set]],
- [[Integer Bases]],
- [[Function(mapping)]],
#### Possibly related
- [[Ring of p-adic integers]],
***
#### Sources: