# Defining Lie algebra by structure constants
***
###### tags: #Algebra 
***
>[!dsn] Direct strict note
> Let $L$ be a vector space over a finite field $F_{2}$, $\dim_{F_{2}}(L)=2$. By $e_{1},e_{2}$ we denote the basis of $L$. And let $[\cdot,\cdot]$ be the *bilinear* law of composition defined on $L$ for which the following is true:
> $$[e_{1},e_{1}]=0,\;[e_{1},e_{2}]=e_{1},\;[e_{2},e_{1}]=e_{1},\;[e_{2},e_{2}]=0$$
> i.e. we have the following structure constants: $0,0$,$1,0$,$1,0$,$0,0$.
> Then $L$ is a Lie algebra.

>[!proof]
>We only should check the Jacobi identity, because other properties are trivial. Because $F_{2}$ consists only of two elements we have $8$ possible identities on elements $a,b,c$:
>1. $$[[e_{1},e_{1}],e_{1}]+[[e_{1},e_{1}],e_{1}]+[[e_{1},e_1],e_{1}]=0$$
>   $$[0,e_{1}]+[0,e_{1}]+[0,e_{1}]=0$$
>   $$0=0$$
>2. $$[[e_{1},e_{1}],e_{2}]+[[e_{1},e_{2}],e_{1}]+[[e_{2},e_1],e_{1}]=0$$
>   $$[0,e_{2}]+[e_{1},e_{1}]+[e_{1},e_{1}]=0$$
>   $$0=0$$
>3. $$[[e_{1},e_{2}],e_{1}]+[[e_{2},e_{1}],e_{1}]+[[e_{1},e_1],e_{2}]=0$$
>   $$[e_{1},e_{2}]+[e_{1},e_{1}]+[0,e_{2}]=0$$
>   $$0=0$$
>4. $$[[e_{1},e_{2}],e_{2}]+[[e_{2},e_{2}],e_{1}]+[[e_{2},e_1],e_{2}]=0$$
>   $$[e_{1},e_{2}]+[0,e_{1}]+[e_{1},e_{2}]=0$$
>   $$e_{1}+0+e_{1}=0$$
>   $$2e_{1}=0$$
>   $$0=0$$ 
>5. $$[[e_{2},e_{1}],e_{1}]+[[e_{1},e_{1}],e_{2}]+[[e_{1},e_2],e_{1}]=0$$
>   $$[e_{1},e_{1}]+[0,e_{2}]+[e_{1},e_{1}]=0$$
>   $$0=0$$ 
>6. $$[[e_{2},e_{1}],e_{2}]+[[e_{1},e_{2}],e_{2}]+[[e_{2},e_{2}],e_{1}]=0$$
>   $$[e_{1},e_{2}]+[e_{1},e_{2}]+[0,e_{1}]=0$$
>   $$e_{1}+e_{1}+0=0$$
>   $$2e_{1}=0$$
>   $$0=0$$ 
>7. $$[[e_{2},e_{2}],e_{1}]+[[e_{2},e_{1}],e_{2}]+[[e_{1},e_{2}],e_{2}]=0$$
>   $$[0,e_{1}]+[e_{1},e_{2}]+[e_{1},e_{2}]=0$$
>   $$0+e_{1}+e_{1}=0$$
>   $$2e_{1}=0$$
>   $$0=0$$ 
>8. $$[[e_{2},e_{2}],e_{2}]+[[e_{2},e_{2}],e_{2}]+[[e_{2},e_{2}],e_{2}]=0$$
>   $$[0,e_{2}]+[0,e_{2}]+[0,e_{2}]=0$$
>   $$0=0$$ 
>
>Therefore $L$ is indeed a Lie algebra.
***
#### Keywords
- [[Vector space]],
- [[Finite field]],
- [[Dimension of a vector space]],
- [[Basis of vector space]],
- [[Law of composition]],
- [[Lie algebra]],
- [[Linear map]],
- [[Structure constants of an algebra]]
#### Possibly related
- [[Билинейная форма]]
***
#### Sources: