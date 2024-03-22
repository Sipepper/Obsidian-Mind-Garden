---
Last time checked: 2024-02-20
Complete: true
aliases:
---
# Group center
***
###### tags: #Group_Theory 
***
>[!dsn]+ Definition
>Let $G$ be a group, then the *center* of $G$, denoted $Z(G)$, is the set of elements $g$ which satisfy the following equivalent conditions
>1. $xgx^{-1}=g,\forall x\in G$, i.e. elements which is fixed under conjugation.
>2. $C_{G}(g)=G$, i.e. centralizer of each such element equals to whole group $G$.
>3. Conjugacy class of $g$ in $G$ is the singleton set $\set{g}$.
>
>If center is a trivial subgroup, then it's often said that $G$ has *trivial center*, or *has no center*.^[https://groupprops.subwiki.org/wiki/Center]

>Group $G$ is abelian if and only if $G=Z(G)$.

>Every subgroup of $Z(G)$ is a normal subgroup of $G$.
>>[!proof]+
>>Let $H\le Z(G)$, that is for every $h_{1},h_{2}\in H$, $h_{1}h_{2}^{-1}\in H$ and for every $g\in G$, $gh_{1}g^{-1}=h_{1}$. Then consider set
>>$$gHg^{-1}=\{ghg^{-1}:h\in H,g\in G\}$$
>>but as $h\in Z(G)$, $ghg^{-1}=h$, thus
>>$$gHg^{-1}=H$$
>>therefore $gH=Hg$, that is $H$ is normal in $G$. 

>[!example]+
>The center of the [[Quaternion group]], 
>$$Q_{8}=\{1,-1,i,-i,j,-j,k,-k\}$$
>is $\{1,-1\}$.^[https://en.wikipedia.org/wiki/Center_(group_theory)]
***
#### Keywords
- [[Group]],
- [[Set]],
- [[Conjugation in groups]],
- [[Fixed point]],
- [[Centralizer in a group]],
- [[Conjugacy class]],
- [[Trivial group]],
- [[Abelian group]],
- [[Normal subgroup]],
- [[Group coset]]
#### Possibly related
- 
***
#### Sources: