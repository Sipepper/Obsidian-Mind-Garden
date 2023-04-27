# Normalizer in a group
***
###### tags: #Group_Theory 
***
>[!dsn] Direct strict note
>Let $M\subset H$, where $H\le G$, then the set
>$$N_{H}(M)=\set{h:h\in H,M^{h}=M}$$
>is said to be the *normalizer* of $S$ in subgroup $H$.

>The normalizer $N_{H}(M)$ is a subgroup of a group $H$.
>>[!proof]
>>The normalizer is non empty since $eS=Se$. For all  $a,b\in N$ we have $aS=Sa$ and $bS=Sb$, and hence
>>$$(ab)S=a(bS)=a(Sb)=(aS)b=S(ab)$$
>>which shows that $ab\in S$. For the inverse; if $c\in N$ then $Sc=cS$ and so
>>$$c^{-1}Sc=c^{-1}cS=S$$
>>therefore $c^{-1}S=Sc^{-1}$, from which we have that $c^{-1}\in N$.

>Normalizer is a special case of *stabilizer* of group action, in particular it's just a stabilizaer of group acting on it's power set.^[https://math.stackexchange.com/questions/1407012/proof-that-normalizer-and-center-are-subgroups]

>[!example] 
>

#### Properties
>[!dsn]+ Direct strict note
>Let $H\le G$. Then 
>1. $H\trianglelefteq N_{H}$, that is $H$ is normal subgroup of it's normalizer
>2. If $K$ is any subgroup of $G$ containing $H$ and such that $H$ is normal in $K$, then $K\subset N_{H}$
>3. If $K\le N_{H}$, then $KH$ is a group and $H$ is normal in $KH$.
>4. The normalizer of $H$ is the largest subgroup of $G$ in which $H$ is normal.

>[!proof]+
>
***
#### Keywords
- [[Set]],
- [[Group]],
- [[Conjugation in groups]],
- [[Group acting on a set]],
- [[Stabilizer subgroup]],
- [[Normal subgroup]]
#### Possibly related
- 
***
#### Sources: