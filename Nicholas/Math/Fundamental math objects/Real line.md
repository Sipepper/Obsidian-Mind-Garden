---
Last time checked: 2024-02-07
Complete: true
aliases:
---
# Real line
***
###### tags: #Fundamental_math_objects 
***
#### Cantor fundamental sequences
>[!dsn]+ Definition
>A real number is defined as a limit of converging Cauchy sequence on $\mathbb{Q}$, that is
>$$\forall\varepsilon>0\quad\exists N(\varepsilon):\forall n>N(\varepsilon),\forall m>0\quad|a_{n+m}-a_{n}|<\varepsilon$$
>i.e. all element from sequence after some number will lie arbitrarly close to each other.
>We denote such real number as $\alpha=[a_{n}]$.^[https://ru.wikipedia.org/wiki/Вещественное_число#Свойства]

>Two real numbers $[a_{n}]$ and $[b_{n}]$ are said to be *equal* if 
>$$\lim\limits_{n\to\infty}(a_{n}-b_{n})=0$$

>Addition and multiplication is performed component-wise, i.e.
>$$[a_{n}]+[b_{n}]=[a_{n}+b_{n}]\qquad[a_{n}]\cdot[b_{n}]=[a_{n}\cdot b_{n}]$$

>Partial order can be introduces as follows: let $\alpha=[a_{n}]$ and $\beta=[b_{n}]$, then $\alpha>\beta$ if
>$$\exists\varepsilon>0\quad\exists N:\forall n>N\quad a_{n}\ge b_{n}+\varepsilon$$

>As we can see such definition is a special case of completing the metric spaces.

#### Infinite decimal fractions
>[!dsn]+ Definition
>A real number $\alpha$ is defined as a *infinite decimal fraction*, that is
>$$\pm a_{0},a_{1}a_{2}\dots a_{n}\dots$$
>where $a_{0}\in\mathbb{N}\cup\{0\}$ and $a_{1},a_{2},\dots,a_{n},\dots$ is a sequence of decimal numbers $\{0,1,\dots,9\}$.^[https://ru.wikipedia.org/wiki/Вещественное_число#Свойства]

>Addition and multiplication is done by *law of carries* as for rational numbers.

>Comparing two real numbers is performed bitwise, that is if $a_{0}<b_{0}$ then $\alpha<\beta$. If $a_{0}=b_{0}$ we go to the $a_{1}$ and $b_{1}$ etc. 

#### Dedekind cuts
>[!dsn]+ Definition
>A *cut* in $\mathbb{Q}$ is a partition of $\mathbb{Q}$ into two non-empty classes - *upper* $A$ and *lower* $A'$ such that every element from $A$ is strictly less then every element from $A'$ i.e.
>$$\mathbb{Q}=A\cup A'\quad\land\quad A,A'\ne\emptyset\quad\land\quad\forall a\in A,\forall a'\in A':a<a'$$
>If there exist a number $\alpha$ which is a maximal in $A$ or minimal in $A'$, we say thay $\alpha$ *dividing* $A$ and $A'$. Rational number $\alpha$ *performs* the cut.
>
>If there is no maximal number in $A$ or minimal in $A'$ then there is no such rational number which is dividing $A$ and $A'$. In such case we say that cut is *defining* some *irrational number* $\alpha$, which is lie between $A$ and $B$ and performs such cut.
>
>Union of rational and irrational numbers is call *set of real numbers* (*real line*), and it's elements are said to be *real numbers*.^[https://ru.wikipedia.org/wiki/Вещественное_число#Свойства]

***
#### Keywords
- [[Limit]],
- [[Convergence]],
- [[Cauchy sequence]],
- [[Absolute value]],
- [[Sequence]],
- [[Partially ordered set]],
- [[Completion of a metric space]],
- [[Rational numbers]],
- [[Set of natural numbers]],
- [[Cardinality of a set]],
- [[Equivalence relation]],
- [[Greatest element, upper bound and maximal element of a partially ordered set]]
- [[Set]],
- [[Logical operators]]
#### Possibly related
- 
***
#### Sources: