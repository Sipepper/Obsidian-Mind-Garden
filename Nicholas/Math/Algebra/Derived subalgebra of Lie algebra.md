---
Last time checked: 2024-01-23
Complete: false
aliases:
---
# Derived subalgebra of Lie algebra
***
###### tags: #Algebra 
***
>[!dsn]+ Definition
>Let $L$ be a Lie subalgebra. The commutant $[L,L]$ is said to be the *derived subalgebra* of $L$, often denoted as $L'$.

>By [[Properties of subalgebras, ideals and sums of subalgebras in Lie algebras]] we know that $L\triangleleft L$ and that if $H,K\triangleleft L$ then $[H,K]\triangleleft L$. Then $[L,L]\triangleleft L$.

#### Properties
>[!dsn]+ Proposition
>Let $L$ be a Lie algebra, then
>1. quotient algebra $L/[L,L]$
 is abelian
>2. derived subalgebra $[L,L]$ is a minimal ideal of $L$ such that quotient algebra $L/[L,L]$ is abelian 

>[!proof]+
>1. Let $x,y\in L$. Then
>   $$[x+[L,L],y+[L,L]]=[x,y]+[L,L]$$
>   Because $[x,y]\in[L,L]$, then
>   $$[x+[L,L],y+[L,L]]=[L,L]$$
>   thus $L/[L,L]$ is abelian.
>2. Let's assume the converse. Let there be some proper subalgebra $I\le[L,L]$ such that quotient algebra $L/I$ is abelian. It means that, for any $x,y\in L$
>   $$[x+I,y+I]=I$$
>   on the other hand,
>   $$[x+I,y+I]=[x,y]+I$$
>   Which means that
>   $$[x,y]\in I$$
>   Because $x,y$ were chosed arbitrarily, it means that $[L,L]\subseteq I$. Thus we have a contradiction.

>[!example]+
>
***
#### Keywords
- [[Lie algebra]],
- [[Commutant in algebras]],
- [[Ideal]],
- [[Quotient algebra]],
#### Possibly related
- 
***
#### Sources: