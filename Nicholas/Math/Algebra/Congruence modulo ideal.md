---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# Congruence modulo ideal
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Definition
>Let $R$ be a ring, $I$ be an ideal. The *congruence modulo ideal $I$* is the following relation
>$$(a\equiv_{I}b)\Leftrightarrow(a\equiv b\mod I)\Leftrightarrow(a-b\in I)$$

>$a\equiv_{I}b$ is an equivalence relation.
>>[!proof]+
>>Let $I$ be an ideal in $R$.
>>1. $\forall a\in R$, $a\equiv a\mod{I}$, as $a-a=0_{R}\in I$.
>>2. Let $a,b\in R$, then as $a-b\in I$ so does $b-a\in I$, so $b\equiv_{I}a$.
>>3. Let $a,b,c\in R$. If $a\equiv_{I}b$ and $b\equiv_{I}c$, then $a-b\in I$ and $b-c\in I$, so $(a-b)+(b-c)=a-c\in I$, thus $a\equiv_{I}c$.

>[!example]+ 
>[[Congruent integers]] is an example of congruence modulo ideal, where we consider ideals in $\mathbb{Z}$, namely $k\mathbb{Z}$.
***
#### Keywords
- [[Ring]],
- [[Ideal]],
- [[Equivalence relation]],
- [[Set of integers]]
#### Possibly related
- [[Congruent integers]]
***
#### Sources: