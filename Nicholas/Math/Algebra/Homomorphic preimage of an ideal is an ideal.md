---
Last time checked: 2024-01-26
Complete: false
aliases:
---
# Homomorphic preimage of an ideal is an ideal
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Lemma
>Let $f:R\to S$ be a ring homomorphism and $J$ is an ideal in $S$. Then it's preimage $f^{-1}(J)$ is an ideal in $R$.^[[Lectures at KAU - Yevgen Polulyakh 7](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>A set $f^{-1}(J)$ is closed under addition and multiplication in $R$. Let $r,u\in f^{-1}(J)$, then $f(r+u)=f(r)+f(u)\in J$, so $r+u\in f^{-1}(J)$. Analogously, $f(ru)=f(r)f(u)\in J$ thus $ru\in f^{-1}(J)$.
>
>$f^{-1}$ satisfies the absorption property. Let $r\in R$, $u\in f^{-1}(J)$. Then $f(ru)=f(r)f(u)\in J$, as $J$ is an ideal. Therefore $ru\in f^{-1}(J)$. Analogously $ur\in f^{-1}(J)$.

>[!example]+ 
>
***
#### Keywords
- [[Ring]],
- [[Homomorphism]],
- [[Ideal]],
- [[Preimage]]
#### Possibly related
- 
***
#### Sources: