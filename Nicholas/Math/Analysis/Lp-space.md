---
Last time checked: 2024-02-01
Complete: false
aliases:
---
# Lp-space
***
###### tags: #Analysis/Functional  
***
>[!dsn]+ Definition
>Let $1\le p<\infty$ and $(S,\Sigma,\mu)$ be a measure space. Consider the set $\mathcal{L}^{p}(S,\mu)$ of all measurable functions from $S$ to $\mathbb{C}$ or $\mathbb{R}$ whose absolute value raised to the $p$-th power has a finite integral, or equivalently, that
>$$\|f\|_{p}\equiv\left(\int_{S}|f|^{p}d\mu\right)^{1/p}<\infty$$
>Because the $\mathcal{L}^{p}$ is a vector space
>$$(f+g)(x)=f(x)+g(x)$$
>$$(sf)(x)=sf(x)$$
>and the $\|\cdot\|_{p}$ is a seminorm we can define the $\ker\|\cdot\|_{p}$
>$$\ker\|\cdot\|_{p}=\set{f\in\mathcal{L^{p}}(S,\mu):\left\|f\right\|_{p}=0}$$
>this is a closed vector subspace of $\mathcal{L}^{p}(S,\mu)$
>>[!proof]+
>>
>
>if $f$ is any measurable function, then $\|f\|_{p}=0$ if and only if $f=0$ almost everywhere.
>We can denote the kernel by $\mathcal{N}$
>Then the *Lebesgue space* $L^{p}$ is defined as factorspace by the kernel $\mathcal{N}$
>$$L^{p}(S,\mu):=\mathcal{L}^{p}(S,\mu)/\mathcal{N}=\set{f+\mathcal{N}:f\in\mathcal{L}^{p}(S,\mu)}$$
>It is a normed vector space which is also a Banach space for every $1\le p\le\infty$.^[https://en.wikipedia.org/wiki/Lp_space]

>[!example]+
>$L^{2}$ space is the only Hilbert space among $L^{p}$ spaces. In the complex case, we can defined the inner product on $L^{2}$ as 
>$$\langle f,g\rangle=\int_{S}f(x)\overline{g(x)}d\mu(x)$$
>Functions in $L^{2}$ is often called *square integrable*.

***
#### Keywords
- [[Measure]],
- [[Set]],
- [[Measurable function]],
- [[Complex plane]],
- [[Real line]],
- [[Absolute value]],
- [[Cardinality of a set]],
- [[Normed space]],
- [[Vector space]],
- [[Seminorm]],
- [[Kernel and image of a mapping]],
- [[Quotient vector space]],
- [[Banach space]],
- [[Hilbert space]],
- [[Inner product]],
- [[Complex conjugation]],
- [[Lebesgue measure]],
- [[Lebesgue integral]],
#### Possibly related
- [[Affine hyperplane]],
***
#### Sources: