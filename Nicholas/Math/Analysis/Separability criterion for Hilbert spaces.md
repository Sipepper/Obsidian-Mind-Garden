# Separability criterion for Hilbert spaces
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Hilbert space $H$ separable if and only if it has countable orthonormal basis. If $\dim(H)=N<\infty$, i.e. finite, then $H$ is isomorphic to $\mathbb{C}^{N}$. If $\dim(H)=+\infty$, then $H$ is isomorphic to $l^{2}$ space.^[Fabio Silva Botelho - "Functional analysis and applied optimization in banach spaces" p.39-40]

>[!proof]+
>Let $H$ be separable and $\{u_{n}\}$ is a countable dense subset of $H$. By applying the [[Gram-Schmidt ortogonalization]] to the largest linearly independent subset of $\{u_{n}\}$ we obtain orthonormal basis.
>
>Conversely, let $B=\{v_{n}\}$ be an orthonormal basis for $H$, the set of all linear combinations of elements from $B$ with rational coefficients is dense in $H$, and thus $H$ is separable.
>
>If $\dim(H)=+\infty$, we can consider the isomorphism $F:H\to l^{2}$ defined as 
>$$F(u)=\{(u_{n},u)_{H}\}_{n\in\mathbb{N}}$$
>
>Finally, if $\dim(H)=N<+\infty$, consider the isomorphism $F:H\to\mathbb{C}^{N}$ defined as
>$$F(u)=\{(u_{n},u)_{H}\}_{n=1}^{N}$$
>which completes the proof.

***
#### Keywords
- [[Hilbert space]],
- [[Separable space]],
- [[Cardinality of a set]],
- [[Orthonormal basis]],
- [[Dimension of a vector space]],
- [[Isomorphism]],
- [[Sequence spaces]],
- [[Linear span]],
- [[Dense subset]],
- [[Complex plane]]
#### Possibly related
- 
***
#### Sources: