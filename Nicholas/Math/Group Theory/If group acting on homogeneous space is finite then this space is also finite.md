# If group acting on homogeneous space is finite then this space is also finite
***
###### tags: #Group_Theory #Geometry 
***
>[!dsn]+ Direct strict note
>Let $X$ be homogeneous under action $(G,X,\phi)$, then if $G$ is finite, so is $X$. Moreover, for every $x\in X$, we have $\# X=(\# G)/(\# G_{x})$.^[Marcer Berger - "Geometry 1" p.8]

>[!proof]+
>It's a corollary from definition of quotient set in [[Homogeneous space under group action]], that is as $\underline{\theta}$ is a bijection and $G/G_{x}$ finite (as $G$ is finite) $X$ must be finite. 
>
>As $G/G_{x}$ can be viewed as a set of left(right) cosets of stabilizer $G_{x}$, we can use  [[Lagrange's theorem for groups]] noting that $\# X$ is precisely the index $[G:G_{x}]$ of group $G$ by stabilizer $G_{x}$, that is number of left(right) cosets $g G_{x}$. Thus from $\# G=[G:G_{x}]\cdot\#G_{x}$ we have
>$$\# X=[G:G_{x}]=\frac{\# G}{\# G_{x}}$$

>[!example]+ 
>
***
#### Keywords
- [[Homogeneous space under group action]],
- [[Cardinality of a set]],
- [[Quotient set]],
- [[Function(mapping)]],
- [[Group coset]],
- [[Stabilizer subgroup]],
- [[Index of a subgroup]]
#### Possibly related
- 
***
#### Sources: