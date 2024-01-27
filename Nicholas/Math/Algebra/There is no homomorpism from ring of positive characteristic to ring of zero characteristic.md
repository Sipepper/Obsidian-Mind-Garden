---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# There is no homomorpism from ring of positive characteristic to ring of zero characteristic
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Proposition
>Let $R$ and $S$ be rings, $\operatorname{char}S=0$. If $\operatorname{char}R>0$, then there is no ring homomorphism $R\to S$.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>Suppose that we have such homomorphism $\phi:R\to S$, then as $\operatorname{char}S=n>0$, 
>$$0_{S}=\phi(0_{R})=\phi(n\cdot 1_{R})=n\cdot\phi(1_{R})=n\cdot 1_{S}$$
>thus $S$ have characteristic equal to $n$, which contradicts that $\operatorname{char}S=0$, so we have a contradiction. Therefore such homomorphism cannot exist.

>[!example]+ 
>Consider the [[determinant]] map $\det:M_{2}(\mathbb{R})\to\mathbb{R}$. It is well known that $\det I=1$, $\det(A\cdot B)=\det A\cdot\det B$, $\forall A,B\in M_{2}(\mathbb{R})$.
>On the other hand
>$$1=\det I=\det\left(\begin{pmatrix}1&0\\0&0 \end{pmatrix}+\begin{pmatrix}0&0\\0&1 \end{pmatrix} \right)\ne \det\begin{pmatrix}1&0\\0&0 \end{pmatrix}+\det\begin{pmatrix}0&0\\0&1 \end{pmatrix}=0+0=0 $$
>Thus $\det$ is *not* a ring homomorphism, despite the fact that $\det$ is a group homomorphism.
***
#### Keywords
- [[Ring]],
- [[Characteristic]],
- [[Homomorphism]],
- [[Determinant]],
- [[Function(mapping)]],
- [[Matrix]]
#### Possibly related
- 
***
#### Sources: