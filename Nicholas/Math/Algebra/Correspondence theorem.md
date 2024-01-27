---
Last time checked: 2024-01-26
Complete: false
aliases:
---
# Correspondence theorem
***
###### tags: #Algebra 
***
#### For rings
>[!dsn]+ Theorem
>Let $R$ be a ring, $I$ ideal in $R$. Let $\pi:R\to R/I$ be a projection. Then map $\phi:2^{R}\to 2^{R/I}$, $\forall A\subset R$, $\phi(A)=\pi(A)$, defines a bijection between ideals of $R$ which contains $I$ and ideals of $R/I$.^[[Lectures at KAU - Yevgen Polulyakh 7](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>By [[surjective homomorphic image of an ideal is an ideal]] we have the following surjective correspondence
>$$\left(J-\text{ideal in }R\text{ such that I}\subset J \right)\overset{\overline{\phi}}{\to}\left(\pi(J)-\text{ideal in }R/I\right)$$
>Also by [[homomorphic preimage of an ideal is an ideal]] we have an inverse correspondence
>$$\left(K-\text{ideal in } R/I\right)\overset{\overline{\psi}}{\to}\left(\pi^{-1}(K)-\text{ideal in }R\right)$$
>Now we prove that $\overline{\psi}=\overline{\phi}^{-1}$.
>As $\pi(\pi^{-1}(K))=K$ for any ideal $R/I$, we only should check that $\pi^{-1}(\pi(J))=J$ for any ideal $J$ of $R$, such that $I\subset J$.
>Let $J$ be an ideal in $R$, $I\subset J$. We only need to prove that $J$ is saturated with respect to partition of $R$ by $r+I$ sets (preimages of points of $R/I$).
>So, let $r\in J$, $s\in\pi^{-1}(\pi(r))\subset\pi^{-1}(\pi(J))$. Then 
>$$s\in r+I\subset r+J=\{r+u:u\in J\}=J$$
>as $J$ is closed under addition.
>Thus as $r\in J$ is an arbitrary, $\pi^{-1}(\pi(J))=J$ and $\overline{\psi}=\overline{\phi}^{-1}$.

>[!example]+ 
>
***
#### Keywords
- [[Ring]],
- [[Ideal]],
- [[Projection map]],
- [[Function(mapping)]],
- [[Power set]],
- [[Quotient ring]],
- [[Preimage]],
- [[Saturated set]],
- [[Partition of a set]]
#### Possibly related
- 
***
#### Sources: