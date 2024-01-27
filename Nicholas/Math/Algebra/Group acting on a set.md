---
Last time checked: 2024-01-20
Complete: true
aliases:
---
# Group acting on a set
***
###### tags: #Algebra #Group_Theory 
***
>[!dsn]+ Definition
> Let $S$ be a set and $G$ is a group. Mapping $G\times S\to S$, denoted as $xs$ as image of pair $(x,s)$, such that $\forall x,y\in G$ and $s\in S$ following properties holds $$(xy)s=x(ys)\quad\text{and}\quad es=s$$ is called a *left group action*.^[С. Ленг Алгебра с.32-33]

>When group $G$ acting on a set $S$, the set $S$ is often called a *$G$-set*. 

>Group $G$ acting on a set $A$ can be viewed as a homomorphism $\phi:G\to S(A)$, that is a homomorphism to a symmetric group of $A$. And $\phi$ is said to be a *$G$-action* on $A$, or that $G$ *operates* (*acts*) on $A$.^[[[Marcel Berger - Geometry 1.pdf#page=17 |Marcel Berger - "Geometry 1" p.5]]] 

>[!example]+ 
>If $X$ is a vector space, its linear group
>$$G=GL(X)=\{f:X\to X|f\text{ is linear and bijective}\}$$
>acts on $X$.

>[!example]+
>Let $X=G$ be a group. Then $G$ acts on itself in several important ways:
>- $\phi(g)(h)=gh$ *left translations*
>- $\phi(g)(h)=hg$ *right translations*
>- $\phi(g)(h)=ghg^{-1}$ *inner automorphisms* (*conjugation*)
***
#### Keywords
- [[Set]],
- [[Group]],
- [[Cartesian product of sets]]
- [[Function(mapping)]],
- [[Homomorphism]],
- [[Symmetric group]],
- [[Vector space]],
- [[Linear groups]],
- [[Linear map]],
- [[Conjugation in groups]],
- [[Group automorphism]]
#### Possibly related
- 
***
#### Sources: