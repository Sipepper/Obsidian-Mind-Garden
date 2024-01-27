---
Last time checked: 2024-01-23
Complete: false
aliases:
---
# The Leibniz kernel
***
###### tags: #Algebra 
***
>[!dsn]+ Definition
>Let $L$ be a Leibniz algebra. Let $\text{Leib}(L)$ be a subspace, spanned by elements $[a,a]$,$a\in L$, such subspace is said to be the *Leibniz kernel* of $L$.

>We can see that for Lie algebras such notion is non-constructive, because $[a,a]=0,\forall a\in L$.

>[!example]+
>
#### Properties
>[!dsn]+ Proposition
>1. $\text{Leib}(L)$ is an ideal of $L$.
>2. Quotient algebra $L/\text{Leib}(L)$ is a Lie algebra. Furthermore $\text{Leib}(L)$ is the smallest such subalgebra.
>3. Leibniz algebra which is not a Lie algebra has a non-trivial Leibniz kernel, thus always has at least three ideals $\langle 0 \rangle$, $\text{Leib}(L)$ and $L$.

>[!proof]+
>1. We need to show that
>   $$[[a,a],x]\in\text{Leib}(L)$$
>   $$[x,[a,a]]\in\text{Leib}(L)$$
>   for some arbitrary $x\in L$. 
>   $$[[a,a],x]=[a,[a,x]]-[a,[a,x]]=0\in\text{Leib}(L)$$
>   Now consider the element $[x+[a,a],x+[a,a]]\in\text{Leib}(L)$:
>   $$\begin{align}[x+[a,a],x+[a,a]]&= [x,x]+[x,[a,a]]+[[a,a],x]+[[a,a],[a,a]]\\ &=[x,x]+[x,[a,a]]+0+0\\ &=[x,x]+[x,[a,a]]\end{align}$$
>   Therefore
>   $$[x,[a,a]]=\underbrace{[x+[a,a],x+[a,a]]}_{\in\text{Leib}(L)}-\underbrace{[x,x]}_{\in\text{Leib(L)}}\in\text{Leib}(L)$$
>   Thus $\text{Leib}(L)$ is an ideal of $L$.
>2. Because $\text{Leib}(L)$ is an ideal of $L$, we can consider the  algebra $L/\text{Leib}(L)$. 
>   Let $a+\text{Leib}(L)\in L/\text{Leib}(L)$, then
>   $$[a+\text{Leib}(L),a+\text{Leib}(L)]=\underbrace{[a,a]}_{\in\text{Leib}(L)}+\text{Leib}(L)=\text{Leib}(L)$$
>   Thus the *square* of any element of $L/\text{Leib}(L)$ equals to zero, which means that $L/\text{Leib}(L)$ is a Lie algebra.
>   $_{}$
>   Let $H$ be an ideal of Leibniz algebra $L$ such that  quotient algebra $L/H$ is a Lie algebra. Then
>   $$H=[a+H,a+H]=[a,a]+H$$
>   from which we obtain that
>   $$\underbrace{[a,a]}_{\in\text{Leib}(L)}\in H$$
>   therefore $\text{Leib}(L)\le H$. Thus $\text{Leib}(L)$ is the smallest ideal with such property.
***
#### Keywords
- [[Leibniz algebra]],
- [[Vector space]],
- [[Linear span]],
- [[Lie algebra]],
- [[Ideal]],
- [[Quotient algebra]],
#### Possibly related
- [[Commutant in algebras]]
***
#### Sources: