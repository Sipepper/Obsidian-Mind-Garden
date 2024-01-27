---
Last time checked: 2024-01-21
Complete: true
aliases:
---
# Properties of subalgebras, ideals and sums of subalgebras in Lie algebras
***
###### tags: #Algebra 
***
>[!dsn]+ Proposition
>Let $L$ be a Lie algebra, then
>1. if $H\triangleleft L$ and $K\le L$, then $H+K\le L$
>2. if $H,K\triangleleft L$, then $H+K\le L$
>3. if $H,K\triangleleft L$, then $[H,K]\triangleleft L$

>[!proof]+
>1. Let $x,y\in H+K$. We need to show that
>   $$[x,y]\in H+K$$
>   By 
>   $$x=a+b,\quad a\in H,b\in K,$$
>   $$y=u+v,\quad u\in H,v\in K,$$
>   we have that
>   $$\begin{align}[x,y]&=[a+b,b+v]\\ &=\underbrace{[a,u]}_{\in H}+\underbrace{[a,v]}_{\in H}+\underbrace{[b,u]}_{\in H}+\underbrace{[b,v]}_{\in K} \end{align}\in H+K$$
>   Therefore $H+K$ is a subalgebra of $L$.
>2. Let $x\in L$, $y\in H+K$. We need to show that
>   $$[x,y]\in H+K$$
>   Because
>   $$y=u+v,\quad u\in H,v\in K$$
>   then
>   $$\begin{align}[x,y]&=[x,u+v]\\ &=\underbrace{[x,u]}_{\in H}+\underbrace{[x,v]}_{\in K} \in H+K\end{align}$$
>   therefore, $H+K$ - ideal in $L$.
>3. Let $x\in H$,$y\in K$, $z\in L$. We need to show that
>   $$[[x,y],z]\in[H,K]$$
>   Because 
>   $$[[x,y],z]+[[y,z],x]+[[z,x],y]=0$$
>   then
>   $$\begin{align}[[x,y],z]&=-[[y,z],x]-[[z,x],y]\\&=\underbrace{[x,\underbrace{[y,z]}_{\in K}]}_{\in[H,K]}-\underbrace{[\underbrace{[z,x]}_{\in H},y]}_{\in[H,K]}\in[H,K] \end{align}$$
>   Therefore, $[H,K]$ is an ideal of $L$.

***
#### Keywords
- [[Lie algebra]],
- [[Ideal]],
- [[Commutant in algebras]],
- [[Lie algebra]],
- [[Sum and direct sum of lie subalgebras]],
#### Possibly related
- 
***
#### Sources: