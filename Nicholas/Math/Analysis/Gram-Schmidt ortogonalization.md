---
Last time checked: 2024-01-28
Complete: false
aliases:
---
# Gram-Schmidt ortogonalization
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Proposition
>Let $H$ be a Hilbert space and $\{u_{n}\}\subset H$ be a sequence on linearly independent vectors. Then the following algorithm $$w_{1}=u_{1},\quad v_{1}=\frac{w_{1}}{||w_{1}||_{H}}$$ $$w_{2}=u_{2}-(v_{1},u_{2})_{H}v_{1},\quad v_{2}=\frac{w_{2}}{||w_{2}||_{H}}$$
and so on $$w_{n}=u_{n}-\sum\limits_{k=1}^{n-1}(v_{k},u_{n})_{H}v_{k},\quad v_{n}=\frac{w_{n}}{||w_{n}||_{H}},\forall n \in \mathbb{N},n>2$$ will give us an orthonormal set and for all $m\in\mathbb{N}$ $\{v_{k}\}_{k=1}^{m}$ and $\{u_{k}\}_{k=1}^{m}$ spans the same vector subspace of the space $H$.

>Such algorithm is called *Gram-Schmidt ortogonalization*.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page= 57|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.39]]]

>[!proof]+
>

>[!example]+
>
***
#### Keywords
- [[Hilbert space]],
- [[Sequence]],
- [[Linearly dependent vectors]],
- [[Normed space]],
- [[Inner product]],
- [[Orthonormal basis]],
- [[Vector space]],
- [[Linear span]],
#### Possibly related
- 
***
#### Sources: