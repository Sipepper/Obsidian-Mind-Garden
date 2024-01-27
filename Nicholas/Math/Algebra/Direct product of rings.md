---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# Direct product of rings
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Definition
>Let $R$ and $S$ be rings. The *direct product* of $R$ and $S$ is a ring $(R\times S,+,\cdot)$, with operations defined as
>$$(r_{1},s_{1})+(r_{2},s_{2}):=(r_{1}+r_{2},s_{1}+s_{2})$$
>$$(r_{1},s_{1})\cdot(r_{2},s_{2}):=(r_{1}\cdot r_{2},s_{1}\cdot s_{2})$$
>with 
>$$\begin{align}0_{R\times S}&=(0_{R},0_{S})\\ 1_{R\times S}&=(1_{R},1_{S})  \end{align}$$
>respectively.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>Direct product of rings is never an integral domain.
>>[!proof]+
>>Even if rings $R$ and $S$ are integral domains, we have that
>>$$(r,0_{S})\cdot(0_{R},s)=(0_{R},0_{S})\quad \forall r\in R\quad\forall s\in S$$
>>thus $R\times S$ is not an integral domain.

>[!example]+ 
>Consider a ring $(\mathbb{Z}/2\mathbb{Z})\times(\mathbb{Z}/2\mathbb{Z})$. It's a set of all pairs $(a,b)$, where $a,b\in\{[0]_{2},[1]_{2} \}$.
>Moreover $2\cdot (a,b)=([0]_{2},[0]_{2})$, for all $a,b$. Thus $\operatorname{char}(\mathbb{Z}/2\mathbb{Z})\times(\mathbb{Z}/2\mathbb{Z})=2$ in contrary to $\mathbb{Z}/4\mathbb{Z}$, that is $(\mathbb{Z}/2\mathbb{Z})\times(\mathbb{Z}/2\mathbb{Z})$ and $\mathbb{Z}/4\mathbb{Z}$ are different rings.

>We can define projection mappings from $R\times S$ to its components
>$$\begin{align}\pi_{R}:R\times S\to R\qquad  (r,s)\mapsto r\\ \pi_{S}:R\times S\to R\qquad  (r,s)\mapsto s\end{align}\quad\forall r\in R\quad \forall s\in S$$
>Note that $\pi_{R}$ and $\pi_{S}$ are ring homomorphisms as
>$$\begin{align}\pi((r_{1},s_{1})+(r_{2}s_{2}))&=\pi(r_{1},s_{1})+\pi(r_{2},s_{2})\\ \pi((r_{1},s_{1})\cdot(r_{2}s_{2}))&=\pi(r_{1},s_{1})\cdot\pi(r_{2},s_{2})\end{align}\quad \forall r\in R\quad \forall s\in S$$
>Here $\pi$ is either $\pi_{R}$ or $\pi_{S}$.
***
#### Keywords
- [[Ring]],
- [[Cartesian product of sets]],
- [[Law of composition]],
- [[Integral domain]],
- [[Modular arithmetic]],
- [[Residue class]],
- [[Characteristic]],
- [[Projection map]],
- [[Homomorphism]]
#### Possibly related
- 
***
#### Sources: