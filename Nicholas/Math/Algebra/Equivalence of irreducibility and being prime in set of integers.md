---
Last time checked: 2023-10-10
Complete: true
aliases:
---
# Equivalence of irreducibility and being prime in set of integers
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Theorem
>Let $p\in\mathbb{Z}$, $p\ne0$. Then $p$ is prime if and only if $p$ is irreducible.

>[!proof]+
>If $p=\pm1$, then $p$ is neither irreducible nor prime. Therefore suppose that $|p|>1$.
>
>$\Rightarrow$
>Let $p$ be prime and $d|p$. Then as $d|p$ there exists $q$ such that $p=dq=dq\cdot 1$ and $p|dq$ and consequently $(p|d)\lor(p|q)$
>- Let $p|d$, then $(p|d)\land(d|p)\Rightarrow |p|=|d|$, so $d=\pm p$
>- Let $p|q$, then $q=rp$, $p=drp$, so $p(1-dr)=0$, as $p\ne0$, then $1-dr=0$, $dr=1$ from which $d|1$ and $d=\pm1$
>
>$\Leftarrow$
>Suppose that $p$ is irreducible. Let $p=ab$, then $p|ab$. Let $p\nmid a$. Then $gcd(p,a)=1$ by properties of [[irreducible element]] and $p|b$ by properties of [[divisibility]].

***
#### Keywords
- [[Set of integers]],
- [[Prime number]],
- [[Irreducible element]],
- [[Absolute value]],
- [[Divisibility]],
- [[Logical operators]],
- [[Greatest common divisor]]
#### Possibly related
- 
***
#### Sources: