# Stabilizer subgroup
***
###### tags: #Group_Theory 
***
>[!dsn]+ Direct strict note
>If $(X,G)$ is a group action and $x\in X$, then the *stabilizer* (or *isotropy group*) of $x$ is the subgroup $G_{x}=\{g\in G:g(x)=x\}$.^[Marcel Berger - "Geometry 1" p.7]

>In some sense stabilizers tells us how far a group is from acting simply transitively. As we can notice that $g(x)=h(x)$ if and only if $h^{-1}g$ is in the stabilizer of $x$.

>[!example]+ 
>Put $A=\{1,\dots,n\}$, $S_{A}=S_{n}$ (the symmetric group). Let $G=S_{n}$. Then $G$ acts on $A$ and it also acts on $X=\mathcal{P}_{n,p}=\{P\subset A:\#P=p\}$, the set of subsets of $A$ with $0\le p\le n$ elements. For $X=A$ and $x=1$, we have a natural isomorphism $G_{1}\cong S_{n-1}$. For $X=S_{n,p}$, we have
>$$G_{\{1,\dots,p\}}\cong S_{p}\times S_{n-p}$$
>>[!proof]+
>>To see that we can utilize the cycle decomposition of permutation and map all cycles which don't contain elements from $\{1,\dots,p\}$ to $\{e\}\times S_{n-p}$ and other to $S_{p}\times\{e\}$.

>[!example]+
>For inner automorphisms we have the following equality
>$$G_{g}=\{h\in G:hg=gh\}$$
>the set of elements of $G$ commuting with $g$, that is the [[Centralizer in a group]]
***
#### Keywords
- [[Group acting on a set]],
- [[Group]],
- [[Simply transitive group action on a set]],
- [[Symmetric group]],
- [[Permutation]],
- [[Set]],
- [[Isomorphism]],
- [[Direct product of groups]],
- [[Conjugation in groups]],
- [[Group automorphism]]
#### Possibly related
- 
***
#### Sources: