---
Last time checked: 2023-10-13
Complete: true
aliases:
---
# Quotient map
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Direct strict note
>Let $f:A\to B$ be a map between sets $A$ and $B$. Suppose that we have partition $\mathcal{R}=\{Q_{\alpha}\}_{\Lambda}$, with respect to equivalence relation $\sim$. Then the map
>$$\overline{f}:A/\mathcal{{R}}\to B$$
>$$[a]\mapsto f(a)$$
>is said to be the *quotient mapping*.

>The necessary and sufficient condition is
>$$[b]=[a]\Rightarrow f(b)=f(a)$$
>>[!proof]+
>>As all equivalence classes are disjoint, if $f(b)=f(a)$, but $[a]\ne[b]$, then $f([a])=a\ne b=f([b])$, so we come to contradiction.

>[!example]+ 
>A [[Canonical homomorphism of groups]] is an example of quotient map, which sends group cosets to corresponding element in [[Quotient group]].
***
#### Keywords
- [[Function(mapping)]],
- [[Set]],
- [[Partition of a set]],
- [[Equivalence relation]],
- [[Group coset]],
- [[Quotient group]]
#### Possibly related
- 
***
#### Sources: