---
Last time checked: 2024-01-20
Complete: true
aliases:
---
# Homomorphism 
***
###### tags: #Algebra 
***
#### Monoid homomorphism
>[!dsn]+ Direct strict note
>Let $(G,\cdot)$ and $(G',*)$ are monoids. *Monoid homomorphism* $G$ in $G'$ is defined as mapping $f:G\to G'$, such that $f(x\cdot y)=f(x)*f(y)$ for all $x,y\in G$ and $f(1_{G})\mapsto 1_{G'}$

>[!example]+
>Consider two monoids $(\mathbb{N},+,0)$ and $(\mathbb{N},\times,1)$. Define a map $x\mapsto 2^{x}$, it's an injective but not surjective homomorphism.^[https://en.wikipedia.org/wiki/Monoid#:~:text=Example%20monoid%20homomorphism%20x%20%E2%86%A6,is%20injective%2C%20but%20not%20surjective.]
>>[!proof]+
>>Let $x\ne y$, then
>>$$(x+y)\mapsto 2^{(x+y)}=2^{x}\cdot2^{y}$$
>>and as $x\mapsto 2^{x}$ is a bijection on $\mathbb{R}$ it's an injection on $\mathbb{N}$. So indeed $x\mapsto 2^{x}$ is an injective monoid homomorphism. But it's obvious that $x\mapsto2^{x}$ is not surjective as $2^{x}\ne 3$, $\forall x\in\mathbb{N}$.

#### Group homomorphism
>[!dsn] Direct strict note  
>Let $G$ and $G'$ are groups, then *group homomorphism* $G$ in $G'$ is just a monoid homomorphism, which also sends inverses to inverses, i.e. $f(x^{-1})\mapsto (f(x))^{-1}$

>[!example]
>Let $G=GL_{n}(\mathbb{R})$ and $G'=\mathbb{R}\setminus{0}$ then the "taking determinant" operation is a group homomorphism because $$\det(AB)=\det(A)\det(B)$$ and $$\det(A^{-1})=\det(A)^{-1}$$

#### Ring homomorphism
>[!dsn]+ Definition
>Let $R$ and $S$ be rings. A map $f:R\to S$ is said to be the *ring homomorphism* if $f(1_{R})=1_{S}$ and $\forall a,b\in R$ the following conditions holds
>$$\begin{align}f(a+b)&=f(a)+f(b)\\ f(a\cdot b)&=f(a)\cdot f(b) \end{align}$$
>.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>If $f:R\to S$ is a ring homomorphism then $f(0_{R})=0_{S}$.
>>[!proof]+
>>$$\begin{align}0_{S}+f(0_{R})&=f(0_{R})\\ &=f(0_{R}+0_{R})\\ &=f(0_{R})+f(0_{R})\end{align}$$
>>therefore $0_{S}=f(0_{R})$

>Also ideals may be viewed as a kernels of some ring homomorphisms.^[[Lectures at KAU - Yevgen Polulyakh 6](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!example]+
>Let $R$ be a ring and $T=\{0_{T}\}$ is a trivial ring. Then map $\textbf{0}:R\to T$, $r\mapsto 0_{T}$, $\forall r\in R$ is a ring homomorphism.
>
>Then $\textbf{0}$ is said to be the *zero homomorphism*.
>
>>[!warning]+
>>If $S\ne\{0_{S}\}$, then map $R\to S$, which sends all elements $r$ to $0_{S}$ is *not* a ring homomorphism, as $1_{S}\ne 0_{S}$.

>[!example]+
>A [[Complex conjugation]] defined as 
>$$z=a+bi\mapsto\overline{z}=a-bi\quad\forall z\in\mathbb{C}$$
>is a ring homomorphism as $\overline{1}=1$, $\overline{z+w}=\overline{z}+\overline{w}$ and $\overline{zw}=\overline{z}\cdot\overline{w}$.
***
#### Keywords
- [[Monoid]],
- [[Function(mapping)]],
- [[Set of natural numbers]],
- [[Real line]],
- [[Group]],
- [[Determinant]],
- [[Linear groups]],
- [[Ring]],
- [[Trivial ring]],
- [[Kernel and image of a mapping]]
#### Possibly related
- 
***
#### Sources: