# Every finite p-group has a non-trivial center
***
###### tags: #Group_Theory 
***
>[!dsn]+ Direct strict note
>Every $p$-group has a non-trivial center.^[Marcel Berger - "Geometry 1." p.11]

>[!proof]+
>Consider the action of $G$ on itself by inner automorphisms(conjugation), call $Z_{G}$ the center of $G$, and look at the induced $G$-action on $X=G\setminus Z_{G}$. If $A$ parametrizes $X/G$ we have, by [[The Class formula]]
>$$\#X=\sum\limits_{x\in A}\frac{\# G}{\# G_{x}}$$
>whence
>$$\#G=p^{m}=\#Z_{G}+\sum\limits_{x\in A}\frac{\#G}{\#G_{x}}$$
>But $\# G_{x}$ is a power of $p$, since it divides $p^{m}$, and $\#G/\#G_{x}=p^{m(x)}$, where $m(x)\ge1$. Then $p$ divides $\# G$ and $\#X$, whence also $\#Z_{G}$.

>[!example]+ 
>
***
#### Keywords
- [[p-group]],
- [[Group center]],
- [[Group acting on a set]],
- [[Conjugation in groups]],
- [[Orbit in homogeneous space]],
- [[Stabilizer subgroup]],
- [[The Class formula]],
- [[Group order]]
#### Possibly related
- 
***
#### Sources: