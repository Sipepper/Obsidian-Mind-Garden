---
Last time checked: 2024-02-19
Complete: false
aliases:
---
# Lagrange's theorem for groups
***
###### tags: #Group_Theory 
***
>[!dsn]+ Theorem
>Let $G$ be a group and $H$ be a subgroup of $G$, then 
>$$|G|=|H|\cdot|G:H|$$
>i.e. the order of a subgroup always divide the order of the group.^[https://groupprops.subwiki.org/wiki/Lagrange's_theorem#Proof]

>Also, because the order of a cyclic group $(a)$ is equal to the order of a generator element $a$, then the order of an element always divide the order of the group.

>[!proof]+
>Because being in a coset is an equivalence relation, we can write a group $G$ as a disjoint union of left(right) cosets of $H$. Let $r=[G:H]$ be the index, i.e. the number of cosets of $H$ each denoted as $A_{i}$. Then we can write:
>$$G=\bigsqcup_{i=1}^{r}A_{i}$$
>Then
>$$|G|=\sum\limits_{i=1}^{r}|A_{i}|$$ because each coset has the same cardinality as the whole subgroup $H$ then 
>$$|G|=\sum\limits_{i=1}^{r}|H|=r|H|=|H|[G:H]$$
>as required

>[!example]+
>
***
#### Keywords
- [[Group]],
- [[Group order]],
- [[Index of a subgroup]],
- [[Divisibility]],
- [[Order of element in group]],
- [[Cyclic group]],
- [[Group coset]],
- [[Equivalence relation]],
- [[Cardinality of a set]]
#### Possibly related
- 
***
#### Sources: