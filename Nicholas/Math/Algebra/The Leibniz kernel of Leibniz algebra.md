# The Leibniz kernel of Leibniz algebra
***
###### tags: #Algebra 
***
>[!dsn] Direct strict note
>Let $L$ be a Leibniz algebra. Let $\text{Leib}(L)$ be a subspace, spanned by elements $[a,a]$,$a\in L$, such subspace is said to be the *Leibniz kernel* of $L$.

>We can see that for Lie algebras such construction is non-constructive, because $[a,a]=0,\forall a\in L$.

#### Properties
>[!dsn] Direct strict note
>1. $\text{Leib}(L)$ is an ideal of $L$.
>2. Factor algebra $L/\text{Leib}(L)$ is a Lie algebra. Furthermore $\text{Leib}(L)$ is the smallest such subalgebra.
>3. Leibniz algebra which is not a Lie algebra has a non-trivial Leibniz kernel, thus always has at least three ideals $<0>$, $\text{Leib}(L)$ and $L$.

>[!proof]
>1. We need to show that
>   $$[[a,a],x]\in\text{Leib}(L)$$
>   $$[x,[a,a]]\in\text{Leib}(L)$$
>   for some arbitrary $x\in L$. 
>   $$[[a,a],x]=[a,[a,x]]-[a,[a,x]]=0\in\text{Leib}(L)$$
>   Now consider the element $[x+[a,a],x+[a,a]]\in\text{Leib}(L)$:
>   $$[x+[a,a],x+[a,a]]=$$
>   $$[x,x]+[x,[a,a]]+[[a,a],x]+[[a,a],[a,a]]=$$
>   $$[x,x]+[x,[a,a]]+0+0=$$
>   $$[x,x]+[x,[a,a]]$$
>   Therefore
>   $$[x,[a,a]]=\underbrace{[x+[a,a],x+[a,a]]}_{\in\text{Leib}(L)}-\underbrace{[x,x]}_{\in\text{Leib(L)}}\in\text{Leib}(L)$$
>   Thus $\text{Leib}(L)$ is an ideal of $L$.
>2. Because $\text{Leib}(L)$ is an ideal of $L$, we canconsider the factor algebra $L/\text{Leib}(L)$. 
>   Let $a+\text{Leib}(L)\in L/\text{Leib}(L)$, then
>   $$[a+\text{Leib}(L),a+\text{Leib}(L)]=\underbrace{[a,a]}_{\in\text{Leib}(L)}+\text{Leib}(L)=\text{Leib}(L)$$
>   Thus the *square* of any element of $L/\text{Leib}(L)$ equals to zero, which means that $L/\text{Leib}(L)$ is a Lie algebra.
>   $_{}$
>   Let $H$ be an ideal of Leibniz algebra $L$ such that  factoralgebra $L/H$ is a Lie algebra. Then
>   $$H=[a+H,a+H]=[a,a]+H$$
>   from which we obtain that
>   $$\underbrace{[a,a]}_{\in\text{Leib}(L)}\in H$$
>   therefore $\text{Leib}(L)\le H$. Thus $\text{Leib}(L)$ is the smallest ideal with such property.




>[!example] 
>
***
#### Keywords
- [[Leibniz algebra]],
- [[Vector space]],
- [[Linear span]],
- [[Lie algebra]],
- [[Ideal]],
- [[Leibniz subalgebras]],
- [[Factor algebra]],
#### Possibly related
- 
***
#### Sources: