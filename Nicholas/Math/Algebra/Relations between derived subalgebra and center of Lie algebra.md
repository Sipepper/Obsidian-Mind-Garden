# Relations between derived subalgebra and center of Lie algebra
***
###### tags: #Algebra 
***
>[!dsn] Direct strict note
>Let $L$ be a Lie algebra and $\zeta(L)$ and $[L,L]$ be the center and derived subalgebra respectively. Then $$L=\zeta(L)$$ if and only if $L$ is abelian. On the other hand $[L,L]=<0>$ if $L$ is abelian. In another words if $L/\zeta(L)=<0>$ then $[L,L]=<0>$ and vice versa.


>[!proof]
>

>[!example] 
>

#### Dimensions
>[!dsn] Direct strict note
>Let $L$ be a Lie algebra over field $F$. If factor algebra $L/\zeta(L)$ has dimension $d$, then $\dim_{F}([L,L])\le d(d-1)/2$.

>[!proof]
>Because $\dim_{F}(L/\zeta(L))=d$, then $L=\zeta(L)+K$ for some subspace $K$. Let's choose a basis $\set{e_{1},\dots,e_{d}}$ in $K$. Let $x_{1},x_{2}\in L$. Then
>$$x_{1}=\alpha_{1}^{(1)}e_{1}+\dots+\alpha_{d}^{(1)}e_{d}+z_{1},\qquad x_{2}=\alpha_{1}^{(2)}e_{1}+\dots+\alpha_{d}^{(2)}e_{d}+z_{2}$$
>for some $\alpha_{i}^{(j)}\in F$, $z_{j}\in\zeta(L)$, $1\le i\le d$, $j=1,2$. Then
>$$\begin{align}[x_{1},x_{2}]&= [\alpha_{1}^{(1)}e_{1}+\dots+\alpha_{d}^{(1)}e_{d}+z_{1},\alpha_{1}^{(2)}e_{1}+\dots+\alpha_{d}^{(2)}e_{d}+z_{2}]\\ &=\sum\limits_{1\le i_{1},i_{2}\le d}\alpha_{i_{1}}^{(1)}\alpha_{i_{2}}^{(2)}[e_{i_{1}},e_{i_{2}}] \end{align}$$
>it's clear that subspace spanned by $[e_{i_{1}},e_{i_{2}}]$ contains a derived subalgebra $[L,L]$. Because $1\le i_{1},i_{2}\le d$ and by anticommutativity we obtain that
>$$\dim_{F}([L,L])\le d(d-1)/2$$

>The converse is *not* true in most cases, i.e. if derived subalgebra $[L,L]$ is finite-dimensional sometimes $L/\zeta(L)$ may be infinite dimensional.

***
#### Keywords
- [[Lie algebra]],
- [[Center of Lie algebra]],
- [[Derived subalgebra of Lie algebra]],
- [[Field]],
- [[Dimension of a vector space]],
- [[Basis of vector space]],
- [[Linear span]],
#### Possibly related
- 
***
#### Sources: