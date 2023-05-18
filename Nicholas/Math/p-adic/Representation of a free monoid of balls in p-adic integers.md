# Representation of a free monoid of balls in p-adic integers
***
###### tags: #p-adic 
***
>[!dsn] Direct strict note
>Let $\mathcal{M}_{p}$ be a free monoid generated by a set $S=\set{0,1,\dots,p-1}$. For every finite word from elements of $S$, for example $a_{0}a_{1}\dots a_{n}$ we can find a ball with centre in $a=0+a_{1}p+\dots+a_{n}p^{n}$ of radius $r=p^{-n}$. Therefore we obtained a bijection between $\mathcal{M}_{p}$ and the set of all balls in $\mathbb{Z}_{p}$.^[Alain M. Robert - "A course in p-adic analysis" c.12]

>Monoid $\mathcal{M}_{p}$ has several matrix representations 
>$$\mathcal{M}_{p}\to GL_{n}(\mathbb{Z}_{p})$$

>[!example]
>For example, if $n=1$, we can define
>$$s\mapsto T_{s}=\begin{pmatrix}p&s\\ 0&1 \end{pmatrix}\quad s\in S=\set{0,1,\dots,p-1}$$
>Indeed 
>$$T_{a}T_{b}=\begin{pmatrix}p&a \\ 0&1 \end{pmatrix}\begin{pmatrix}p&b \\ 0&1\end{pmatrix}=\begin{pmatrix}p^{2}&a+bp\\0&1 \end{pmatrix}$$
>and for general case
>$$T_{a_{0}}T_{a_{1}}\dots T_{a_{n}}=\begin{pmatrix}p^{n+1}&a_{0}+a_{1}p+\dots+a_{n}p^{n} \\ 0&1\end{pmatrix}$$

With such representation the *length* of the word correlates to order of the matrix determinant(order in p-adic integers). From the "balls viewpoint" radius is an absolute value of the determinant, and center of a ball is an element in top-right corner of a matrix.

In the symbolic notation we have
$$B_{<r}(a)=B_{<r}(s_{n})\longleftrightarrow a_{0}a_{1}\dots a_{n}(\in\mathcal{M})\longleftrightarrow\begin{pmatrix}p^{n+1}&s_{n} \\ 0&1\end{pmatrix}$$
***
#### Keywords
- [[Balls in the ring of p-adic integers]],
- [[Free monoid]],
- [[Function(mapping)]],
- [[Matrix representation]],
- [[Determinant]],
- [[Matrix]],
- [[p-adic order]],
- [[p-adic norm]],
- [[p-adic metric]]
#### Possibly related
- [[Linear groups]]
***
#### Sources: