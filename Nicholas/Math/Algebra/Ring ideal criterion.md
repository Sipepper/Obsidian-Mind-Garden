---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# Ring ideal criterion
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Proposition
>A non-empty subset $I$ of a ring $R$ is an ideal if and only if $I$ is closed under addition and satisfies the absorption property, i.e.
>$$\forall a\in I,\forall r\in R\qquad (ra\in I)\land(ar\in I)$$
>.^[[Lectures at KAU - Yevgen Polulyakh 6](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>In other words, we can skip checking the $(1)$-$(4)$ axioms from definition of a [[ring]].

>[!proof]+
>$\Rightarrow$
>Let $I$ be an ideal. Then by definition $I$ is closed under addition and satisfies the absorption property.
>
>$\Leftarrow$
>Let $I$ be closed under addition and has an absorption property. 
>Addition is associative and commutative in $I$ as $I\subset R$. $I\ne\emptyset$, so there exist $a\in I$. Then $0_{R}=0_{R}\cdot a\in I$ by absorption property. Let $a\in I$. Then $-a=(-1)\cdot a\in I$, therefore $I$ is an ideal.

>[!example]+ 
>$\mathbb{Z}$ is *not* an ideal in $\mathbb{Q}$, as (for example) $\frac{1}{2}\cdot 3=\frac{3}{2}\notin\mathbb{Z}$.
***
#### Keywords
- [[Set]],
- [[Ring]],
- [[Ideal]],
- [[Associative property]],
- [[Commutative property]],
- [[Set of integers]],
- [[Rational numbers]]
#### Possibly related
- 
***
#### Sources: