---
Last time checked: 2023-10-16
Complete: false
aliases:
---
# Modular arithmetic
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Theorem
>The set $\mathbb{Z}/n\mathbb{Z}$ of all residue classes has ring structure with respect to operations defined in [[properties of residue classes]].^[Lecture note from KAU, Eunege Polulyakh]

>[!proof]+
>Let $a=[k]_{n}$, $b=[l]_{n}$ and $c=[m]_{n}$. Then
>$$\begin{align}a\cdot(b+c)&=[k]_{n}\cdot([l]_{n}+[m]_{n})\\ &=[k]_{n}\cdot[l+m]_{n}\\ &=[k\cdot l+k\cdot m]_{n}\\&=[k\cdot l]_{n}+[k\cdot m]_{n}\\&=[k]_{n}\cdot [l]_{n}+[k]_{n}\cdot [m]_{n}\\ &=a\cdot b+a\cdot c \end{align}$$
>analogously %%If at some point i need to finish this proof, i will do it%% all properties ring can be checked using [[properties of residue classes]].

>If $n$ is prime, then $\mathbb{Z}/n\mathbb{Z}$ has no zero divisors. If $n$ is not prime there exists $a\ne0$ and $b\ne0$ in $\mathbb{Z}/n\mathbb{Z}$ such that
>$$a\cdot b=0$$
>or more explicitely
>$$[a]_{n}\cdot[b_{n}]=[0]_{n}$$
>In another words $\mathbb{Z}/n\mathbb{Z}$ is an integral domain if $n$ is prime.
>>[!proof]+
>>Let $p$ be prime, so irreducible. Let $a\in\mathbb{Z}/p\mathbb{Z}$, $a\ne0$. Suppose that $a=[l]_{p}$. As $[l]_{n}\ne [0]_{p}$, then $p\nmid l$. Then $\operatorname{gcd}(p,l)=1$ by [[relatively prime numbers]]. 
>>Then exists $q,k\in\mathbb{Z}$, such that $1=qp+kl$ by properties of [[greatest common divisor]].
>>So 
>>$$\mathbb{1}=[1]_{p}=[qp+kl]_{p}=[q]_{p}[p]_{p}+[k]_{p}[l]_{p}=[k]_{p}[l]_{p}$$
>>so $a'=[k]_{p}$ is a inverse element to $a$, i.e. $a\cdot a'=1$.
>>So we proved that if $p$ is prime then every element has an inverse.
>>
>>Now suppose that there is some $a,b\in\mathbb{Z}/n\mathbb{Z}$, such that $a\cdot b=0$. Then either $a=0$ or $a\ne 0$. Consider the latter case: there exists $a'$ such that $a'\cdot a=1$, and so
>>$$0=a'\cdot 0=a'\cdot a\cdot b=1\cdot b=b$$

>[!example]+ 
>For $\mathbb{Z}/5\mathbb{Z}$, 
>$$[3]_{5}+[2]_{5}=[5]_{5}=[0]_{5}$$
>$$[3]_{5}\cdot[2]_{5}=[6]_{5}=[1]_{5}$$
>but if we have $\mathbb{Z}/6\mathbb{Z}$, then
>$$[2]_{6}\cdot[3]_{6}=[2\cdot 3]_{6}=[6]_{6}=[0]_{6}$$
>so we have zero divisors.

***
#### Keywords
- [[Set]],
- [[Residue class]],
- [[Ring]],
- [[Prime number]],
- [[Divisibility]],
- [[Zero divisor]],
- [[Irreducible element]]
#### Possibly related
- 
***
#### Sources: