---
Last time checked: 2024-02-28
Complete: false
aliases:
---
# Euclidean models of p-adic integers
***
###### tags: #p-adic 
***
>[!dsn]+ Proposition
>Let $V$ be a finite dimensional Euclidean vector space. Define a injective map
>$$v:S=\{0,1,2,\dots,p-1\}\to V\quad v(S)=\Sigma\subset V$$
>now define a vector function
>$$\Psi=\Psi_{v,b}:\mathbb{Z}_{p}\to V\qquad\sum\limits_{i\ge0}a_{i}p^{i}\mapsto\nu\sum\limits_{i\ge0}\frac{v(a_{i})}{b^{i+1}}$$
>As ring $\mathbb{Z}_{p}$ can be represented as a disjoint union $\mathbb{Z}_{p}=\bigsqcup\limits_{a_{0}\in S}(a_{0}+p\mathbb{Z}_{p})$, we have that
>$$\Psi(\mathbb{Z}_{p})=\bigcup\limits_{v\in\Sigma}\left(\nu\frac{v}{b}+\frac{1}{b}\Psi(\mathbb{Z}_{p}) \right)$$
>For $b$ big enough the image $F=F_{v,b}=\Psi_{v,b}(\mathbb{Z}_{p})$ is a *disjoint* union of self similar images. Thus we obtain a spatial model of $\mathbb{Z}_{p}$ by iterating similarly to the construction of Cantor set.^[[[Alain M. Robert - A course in p-adic analysis.pdf#page=28 |Alain M. Robert - "A course in p-adic analysis" p.12-16]]]

>Let $\widehat{\Sigma}$ be a convex hull of vectors $\Sigma$ in $V$. Let $\lambda$ be the affine functional on $V$ such that $\lambda\le1$ on $\Sigma$ and $\lambda(1)$ for some $v\in\Sigma$. Choose $\nu=b-1$. Then
>$$\lambda\left(\nu\sum\limits_{i\ge0}\frac{v(a_{i})}{b^{i+1}}\right)\le\nu\sum\limits_{i\ge0}\frac{1}{b^{i+1}}=\nu\frac{1}{b-1}=\frac{b-1}{b-1}=1$$
>thus $F\subset\widehat{\Sigma}=K_{0}$. Furthermore, by choice of the constant $\nu$
>$$\lambda\left(\nu\sum\limits_{i\ge0}\frac{v}{b^{i+1}}\right)=1$$
>By self similarity of $F$ we obtain a better approximation
>$$F=\bigcup_{v\in\Sigma}\left(\nu\frac{v}{b}+\frac{F}{b}\right)\subset K_{1}=\bigcup_{v\in\Sigma}\left(\nu\frac{v}{b}+\frac{K_{0}}{b}\right)$$
>Repeating in a similar manner we obtain even better approximation
>$$F=\bigcup_{v\in\Sigma}\left(\nu\frac{v}{b}+\frac{F}{b}\right)\subset K_{2}=\bigcup_{v\in\Sigma}\left(\nu\frac{v}{b}+\frac{1}{b}\bigcup_{v\in\Sigma}\left(\nu\frac{v}{b}+\frac{K_{0}}{b}\right)\right)$$
>In the end such iterative process will lead to fractal structure of intersection of decreasing sequence of compact sets $K_{n}$. 

>[!proof]+
>

>[!example]+ 
>Let $p=3$, $V=\mathbb{R}^{3}$ with common basis $e_{0}$, $e_{1}$, $e_{2}$ and let $v(k)=e_{k}$. Then we can define corresponding vector maps $\Psi:\mathbb{Z}_{3}\to\mathbb{R}^{3}$ given by
>$$a=\sum\limits_{i\ge0}a_{i}3^{i}\mapsto\Psi(a)=\nu\sum\limits_{i\ge0}\frac{e_{a_{i}}}{b^{i+1}}$$
>Choose constant $\nu$ such that
>$$\Psi(0)=\nu\sum\limits_{i\ge0}\frac{e_{0}}{b^{i+1}}=e_{0}$$
>that is $\nu=b-1$. In that case image of $\Psi$ is contained in $x+y+z=1$ plane. Since the components of the images $\Psi(a)$ are positive, the image of the map $\Psi$ is contained in the unit simplex of $\mathbb{R}^{3}$ (convex span of the basis vectors).
>
>Mappins $\Psi$ are injective for $b>2$ and thus gives us the homeomorphic images of $\mathbb{Z}_{3}$ in $2$-simplex. When $b=2$, the image is a *Sierpinski gasket* hence connected in this simplex. In general, the image is a fractal having self-similarity dimension $\log3/\log b$.
>![[Pasted image 20220912162314.png]]
>>[!proof]+
>>
>>



***
#### Keywords
- [[Dimension of a vector space]],
- [[Euclidean space]],
- [[Vector space]],
- [[Function(mapping)]],
- [[Ring of p-adic integers]],
- [[Self-similarity]],
- [[Kernel and image of a mapping]],
- [[Cantor space]],
- [[Convex hull]],
- [[Affine map]],
- [[Functional]],
- [[Sequence]],
- [[Compact set]],
- [[Basis of vector space]],
- [[n-simplex]],
- [[Homeomorphism]],
- [[Connected topological space]],
- [[Sierpinski fractals]],
- [[Non-integer base of numeration]]
#### Possibly related
- [[Hausdorff dimension]],
- [[Vector]]
***
#### Sources: