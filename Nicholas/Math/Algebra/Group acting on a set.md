---
Last time checked: 2024-03-08
Complete: true
aliases:
---
# Group acting on a set
***
###### tags: #Algebra #Group_Theory 
***
>[!dsn]+ Definition
>Let $S$ be a set and $G$ is a group. Mapping $G\times S\to S$, denoted as $xs$ as image of pair $(x,s)$, such that $\forall x,y\in G$ and $s\in S$ following properties holds $$(xy)s=x(ys)\quad\text{and}\quad es=s$$ is called a *left group action*.^[С. Ленг Алгебра с.32-33]

>Analogously we can define the *right group action* as a mapping from $S\times G\to S$. Right and left action are often different, as for two element $g,h\in G$ the left action $(gh)x$ can differ from the right action $x(hg)$.

>When group $G$ acting on a set $S$, the set $S$ is often called a *$G$-set*. 

>Group $G$ acting on a set $A$ can be viewed as a homomorphism $\phi:G\to S(A)$, that is a homomorphism to a symmetric group of $A$. And $\phi$ is said to be a *$G$-action* on $A$, or that $G$ *operates* (*acts*) on $A$.^[[[Marcel Berger - Geometry 1.pdf#page=17 |Marcel Berger - "Geometry 1" p.5]]] 

>[!example]+ 
>If $X$ is a vector space, its linear group
>$$G=GL(X)=\{f:X\to X|f\text{ is linear and bijective}\}$$
>acts on $X$.

>[!example]+
>Let $X$ be a set of vertices of octahedron and $G$ be the [[Octahedral group]], then $G$ acts on $X$ by symmetries.^[[Richard E. Borcherds - "Group theory 2"](https://youtu.be/AZUDhtnz-Do?si=7HcnXf0M8H0_qXuU)]

>[!example]+
>Let $S=G$ be a group. Then $G$ acts on itself in several important ways:
>- $\phi(g)(h)=gh$ *left translations*
>- $\phi(g)(h)=hg^{-1}$ *right translations*
>  >If we consider $\phi(g)(h)=hg$ action, it will *not* be an action as
>  >$$sgh=\phi(gh)(s)=\phi(g)(gh)=shg$$
>  >which is not true if $gh\ne hg$ 
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