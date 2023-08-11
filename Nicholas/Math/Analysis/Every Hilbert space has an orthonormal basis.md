# Every Hilbert space has an orthonormal basis
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Let $U$ be a Hilbert space. Then it's *always* has an orthonormal basis.^[Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.37]

>[!proof]+
>Let $C$ be a family of all orthonormal sets in $H$. Define a partial order of $C$ as follows: $S_{1}\le S_{2}$ if $S_{1}\subset S_{2}$. Then $C$ is a partially ordered set and non-empty as
>$$\frac{v}{\|v\|_{H}}\in C\quad\forall v\in H,v\ne\emptyset$$
>Further let $\{S_{\alpha}\}_{\alpha\in L}$ be a linearly ordered subset of $C$. A union $\bigcup\limits_{\alpha\in L}S_{\alpha}$ therefore is a orthonormal set and an upper bound for $\{S_{\alpha}\}_{\alpha\in L}$.
>Thus every linearly ordered subset contains an upper bound, and by [[Zorn's lemma]] $C$ has a maximal element, i.e. orthonormal set which doesn't contained in any other orthonormal set. Therefore basis always exists.

>[!example]+ 
>
***
#### Keywords
- [[Hilbert space]],
- [[Orthonormal basis]],
- [[Partially ordered set]],
- [[Set]],
- [[Linearly ordered set]],
- [[Greatest element, upper bound and maximal element of a partially ordered set]],
- [[Basis of vector space]]
#### Possibly related
- 
***
#### Sources: