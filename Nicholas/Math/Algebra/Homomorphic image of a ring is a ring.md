---
Last time checked: 2024-01-26
Complete: false
aliases:
---
# Homomorphic image of a ring is a ring
***
###### tags: #Algebra 
***
>[!dsn]+ Proposition
>Let $f:R\to S$ be a ring homomorphism. Then image $S'=\operatorname{Im}f:=f(R)$ is a subring of $S$.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>As $f(0_{R})=0_{S}$ and  $f(1_{R})=1_{S}$, $0_{S},1_{S}\in S'$.
>Let $s_{1},s_{2}\in S'$. Then exists $r_{1},r_{2}\in R$ such that $s_{1}=f(r_{1})$ and $s_{2}=f(r_{2})$. Thus
>$$s_{1}+s_{2}=f(r_{1})+f(r_{2})=f(r_{1}+r_{2})\in S'$$
>and
>$$s_{1}\cdot s_{2}=f(r_{1})\cdot f(r_{2})=f(r_{1}\cdot r_{2})\in S'$$
>
>Let $s\in S'=f(R)$, $r\in f^{-1}(s)\subset R$.
>So
>$$0_{S}=f(0_{R})=f(r+(-r))=f(r)+f(-r)$$
>and consequently $-s=f(-r)\in S'$
>Therefore $S'$ is a subring of $S$ by [[subring criterion]].

>If $R'$ is a subring of $R$ then $f(R')$ is a subring of $S$.
>>[!proof]+
>>Proof is analogous to the proof of main proposition.

>[!example]+ 
>
***
#### Keywords
- [[Ring]],
- [[Homomorphism]],
- [[Kernel and image of a mapping]],
- [[Preimage]]
#### Possibly related
- 
***
#### Sources: