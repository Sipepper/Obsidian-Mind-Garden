# Homomorphism 
***
###### tags: #Algebra #Group_Theory 
***
#### Monoid homomorphism
>[!dsn] Direct strict note
>Let $(G,\cdot)$ and $(G',*)$ are monoids. *Monoid homomorphism* $G$ in $G'$ is defined as mapping $f:G\to G'$, such that $f(x\cdot y)=f(x)*f(y)$ for all $x,y\in G$ and $f(1_{G})\mapsto 1_{G'}$

>[!example]
>

#### Group homomorphism
>[!dsn] Direct strict note  
>Let $G$ and $G'$ are groups, then *group homomorphism* $G$ in $G'$ is just a monoid homomorphism, which also sends inverses to inverses, i.e. $f(x^{-1})\mapsto (f(x))^{-1}$

>[!example]
>Let $G=GL_{n}(\mathbb{R})$ and $G'=\mathbb{R}\setminus{0}$ then the "taking determinant" operation is a group homomorphism because $$\det(AB)=\det(A)\det(B)$$ and $$\det(A^{-1})=\det(A)^{-1}$$

##### Kernel of a group homomorphism
>[!dsn] Direct strinct note
>Let $H$ be an image of group homomorphism of group $G$. Then set of elements $T\subseteq G$ which maps to identity element called a *kernel* of group homomorphism.

>[!example] 
>Suppose we have homomorphism $f:\mathbb{Z}\to\mathbb{Z}/{2\mathbb{Z}}$ which maps integer to it's remainder after dividing by two. The kernel of such homomorphism is all even integers.
***
#### Keywords
- [[Monoid]],
- [[Function(mapping)]],
- [[Determinant]],
- [[Linear groups]],
- [[Кольцо вычетов]],
- [[Set of integers]],
- [[Kernel and image of a mapping]]
#### Possibly related
- 
***
#### Sources: