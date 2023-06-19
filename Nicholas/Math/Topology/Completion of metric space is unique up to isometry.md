# Completion of metric space is unique up to isometry
***
###### tags: #Topology  
***
>[!dsn] Direct strict note
>Let $(A,d_{1})$ and $(B,d_{2})$ be a complete metric spaces. Let $X$ be a subset of a space $(A,d_{1})$ with subspace metric $d_{3}$, and $Y$ be a subset of $(B,d_{2})$ with subspace metric $d_{4}$. Further, let $X$ be a dense subset in $(A,d_{1})$ and $Y$ is dense in $(B,d_{2})$. If exist an isometry $f:(X,d_{3})\to(Y,d_{4})$, then exist the isometry $g:(A,d_{1})\to(B,d_{2})$ such that $g(x)=f(x)$ for all $x\in X$.^[Sidney A. Morris - "Topology without tears" c.158]

>[!proof]
>Let $a\in A$. As $X$ is dense in $(A,d_{1})$, there exists a sequence $x_{n}\to a$, where each $x_{n}\in X$. So $\{x_{n}\}$ is a Cauchy sequence. As $f$ is an isometry, $\{f(x_{n})\}$ is a Cauchy sequence in $(Y,d_{4})$ and hence also a Cauchy sequence in $(B,d_{2})$ is a complete metric space, there exists a $b\in B$, such that $f(x_{n})\to b$. 
>So we define $g(a)=b$.
>
>To show that $g$ is a well-defined map of $A$ into $B$, it is necessary to verify that if $\{z_{n}\}$ is any other sequence in $X$ converging to $a$, then $f(z_{n})\to b$. This follows from the fact that $d_{1}(x_{n},z_{n})\to0$ and thus $d_{2}(f(x_{n}),f(z_{n}))=d_{4}(f(x_{n}),f(z_{n}))\to0$.
>Next we need to show that $g:A\to B$ is a bijection. Different Cauchy sequences converges to different elements, thus mapping $g$ is injective. Every element of the complete metric space can be represented by a Cauchy sequence, and because isometry is a surjective mapping, every possible Cauchy sequence is an image of some cauchy sequence in $(A,d_{1})$.
>
>Finally, let $a_{1},a_{2}\in A$ and $a_{1n}\to a_{1}$ and $a_{2n}\to a_{2}$, where each $a_{1n}$ and each $a_{2n}$ is in $X$. Then
>$$d_{1}(a_{1},a_{2})=\lim_{n\to\infty}d_{3}(a_{1n},a_{2n})=\lim_{n\to\infty}d_{4}(f(a_{1n}),f(a_{2n}))=d_{2}(g(a_{1}),g(a_{2}))$$
>and so $g$ is indeed an isometry, as required.
***
#### Keywords
- [[Complete metric space]],
- [[Set]],
- [[Induced metric]],
- [[Dense subset]],
- [[Isometry]],
- [[Sequence]],
- [[Cauchy sequence]],
- [[Completion of a metric space]],
- [[Function(mapping)]],
- [[Convergence in metric spaces]],
- [[Limit]]
#### Possibly related
***
#### Sources: