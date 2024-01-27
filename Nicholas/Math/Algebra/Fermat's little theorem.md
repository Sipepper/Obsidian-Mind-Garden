---
Last time checked: 2023-11-03
Complete: true
aliases:
---
# Fermat's little theorem
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Theorem
>Let $p$ be a positive prime number. Then $\forall a\in\mathbb{Z}$
>$$a^{p}\equiv a\mod{p}$$
>moreover for any $k\ge1$
>$$a^{p^{k}}\equiv a\mod{p}$$
>.^[Lecture note from KAU, Eunege Polulyakh]

>[!proof]+
>If $p|a$, then $[a]_{p}=[0]_{p}$ and
>$$[a^{p}]_{p}=[a]_{p}^{p}=[0]_{p}^{p}=[0]_{p}=[a]_{p}$$
>Suppose that $p\nmid a$, then $[a]_{p}\ne[0]_{p}$. Then
>$$[a]_{p}\cdot[a^{p-1}]_{p}=[a]_{p}\cdot 1$$
>so $a^{p-1}\equiv 1\mod{p}$, by [[properties of residue classes]].
>
>Consider the following residue classes
>$$[a]_{p},[2a]_{p},\dots,[(p-1)a]_{p}$$
>they are all different, indeed
>$$[a]_{p}\cdot[k]_{p}=[ka]_{p}[la]_{p}=[a]_{p}\cdot[l]_{p}\Rightarrow [k]_{p}=[l]_{p}$$
>as $p$ is prime and $[a]_{p}\ne0$. But $[k]_{p}\ne[l]_{p}$ if $k\ne l$ by [[properties of residue classes]].
>As $p\nmid a$ and $p\nmid k$, $\forall k\in\{1,\dots,p-1\}$, $p\nmid ka$. Thus all residue classes from family defined before are non-zero.
>Thus it coincide with 
>$$[1]_{p},[2]_{p},\dots,[p-1]$$
>Therefore
>$$[a]_{p}[2a]_{p}\cdot\ldots\cdot[(p-1)a]_{p}=[1]_{p}\cdot[2]_{p}\cdot\ldots\cdot[p-1]_{p}$$
>so
>$$\begin{align}[(p-1)!]_{p}\cdot[a]_{p}^{p-1}&=[1\cdot2\cdot\ldots\cdot(p-1)\cdot a^{p-1}]_{p}\\ &=[1\cdot2\cdot\ldots\cdot(p-1)]_{p}\\ &=[(p-1)!]_{p}\cdot[1]_{p} \end{align}$$
>As $p\nmid(p-1)!$, $[(p-1)!]_{p}\ne[0]_{p}$ and $[a]_{p}^{p-1}=[1]_{p}$.
>The second part of a theorem we will prove by induction on $k\ge1$.
>For $k=1$ we have that $a^{p}\equiv a\mod{p}$.
>Let $k>1$ and suppose that $a^{p^{k-1}}\equiv a\mod{p}$. Then
>$$a^{p^{k}}=a^{p\cdot p^{k-1}}=(a^{p})^{p^{k-1}}\equiv a^{p^{k-1}}\equiv a\mod{p}$$

>[!example]+ 
>$$4^{3}=64=3\cdot20+4\Rightarrow 4^{3}\equiv 4\mod{3}$$

>Let $p>0$ be a prime number. If $m\equiv 1\mod{(p-1)}$, then $a^{m}\equiv a\mod{p}$, $\forall a\in\mathbb{Z}$.
>
>>[!proof]+
>>If $p|a$, then $[0]_{p}=[a]_{p}=[a]_{p}^{m}=[a^{m}]_{p}$. Let $p\nmid a$, then $[a]_{p}\ne[0]_{p}$. By supposition $m-1=(p-1)k$ for some $k\in\mathbb{Z}$, so $m=1+(p-1)k$. Therefore
>>$$\begin{align}a^{m}&=a^{1+(p-1)k}\\ &=a\cdot a^{(p-1)k}\\&=a\cdot(a^{p-1})^{k}\\&\equiv a\mod{p} \end{align}$$
>>as $a^{p-1}\equiv1\mod{p}$.

***
#### Keywords
- [[Prime number]],
- [[Set of integers]],
- [[Congruent integers]],
- [[Modular arithmetic]],
- [[Residue class]],
- [[Divisibility]],
- [[Mathematical induction]]
#### Possibly related
- 
***
#### Sources: