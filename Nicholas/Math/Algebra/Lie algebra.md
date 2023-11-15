# Lie algebra
***
###### tags: #Algebra 
***
>[!dsn] Direct strict note
>Let $L$ be an algebra over field $F$. Then $L$ is said to be a *Lie algebra*, if it's multiplication $[\cdot,\cdot]$ also satisfies the following conditions
>1. $[a,a]=0_{L}$
>2. $[[a,b],c]+[[b,c],a]+[[c,a],b]=0_{L}$
>
>for all $a,b,c\in L$. Second equality is often called the *Jacobi identity*.

>The $[a,a]=0_{L}$ identity apply the *anticommutativity* of $[\cdot,\cdot]$ and vice versa
>>[!proof]
>>Let $[a+b,a+b]=0_{L}$, then
>>$$[a,a]+[a,b]+[b,a]+[b,b]=0_{L}$$
>>$$0_{L}+[a,b]+[b,a]+0_{L}=0_{L}$$
>>$$[a,b]+[b,a]=0_{L}$$
>>$$[a,b]=-[b,a]$$
>>Suppose now that $\text{char}(F)\ne2$ and let $[a,b]=-[b,a]$,$\forall a,b\in L$. Let $a=b$, then $[a,a]=-[a,a]$ from which we get that 
>>$$2[a,a]=0_{L}$$
>>Because $\text{char}(F)\ne2$, then $[a,a]=0_{L}$.

>In general Lie algebras are *non*-associative.

>[!example] 
>Let $\mathbb{R}^{3}$ be a vector space over a field $\mathbb{R}$. Then the vector product $[\overline{a},\overline{b}]$ of two vectors $\overline{a},\overline{b}\in\mathbb{R}^{3}$ forms a Lie algebra. 

>The subspace $A$ of $L$ is said to be a *subalgebra* of algebra $L$, if $[a,b]\in A$ for all $a,b\in A$. In another words, the subspace $A$ is a subalgebra of $L$ if 
>$$[A,A]\subseteq A$$
>Subalgebras often denoted as $A\le L$. If $A$ is a proper subspace $A<L$.

***
#### Keywords
- [[Algebra]],
- [[Characteristic]],
- [[Euclidean space]],
- [[Vector]],
- [[Cross product]],
- [[Vector space]],
- [[Commutant in algebras]]
#### Possibly related
- 
***
#### Sources: