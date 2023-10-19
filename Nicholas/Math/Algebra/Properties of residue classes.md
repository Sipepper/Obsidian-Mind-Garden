---
Last time checked: 2023-10-13
Complete: true
aliases:
---
# Properties of residue classes
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Lemma
>Let $a,b,n,a',b'\in\mathbb{Z}$, $n\ge0$ and $[a]_{n}=[a']_{n}$ and $[b]_{n}=[b']_{n}$.
>1. If $r$ is a remainder of division $a$ by $n$, then $[a]_{n}=[r]_{n}$
>2. Residue classes $[0]_{n},[1]_{n},\dots,[n-1]_{n}$ are disjoint.
>3. $[a+b]_{n}=[a]_{n}+[b]_{n}$, or equivalently $$a+b\equiv a'+b'\mod{n}$$
>4. $[ab]_{n}=[a]_{n}[b]_{n}$, or equivalently $$ab\equiv a'b'\mod{n}$$

>[!proof]+
>1. Let $a=nq+r$. Then $a-r=nq$, so $n|(a-r)$, from which $a\equiv r\mod{n}$.
>2. Let $0\le r_{1}<n$ and $0\le r_{2}<n$. Suppose that $[r_{1}]_{n}=[r_{2}]_{n}$. Then $n|(r_{2}-r_{1})$, and so either $r_{1}=r_{2}$ or $|r_{2}-r_{1}|\ge n$ by properties of [[divisibility]]. But $|r_{2}-r_{1}|<n$, so $r_{1}=r_{2}$.
>3. There exists $k,l$ such that $a'-a=nk$ and $b'-b=nl$. So
>   $$(a'+b')-(a+b)=nk+nl=n(k+l)$$
>   so indeed
>   $$a+b\equiv a'+b'\mod{n}$$
>4. Analogously
>   $$\begin{align}a'b'-ab&=a'b'-a'b+a'b-ab\\ &=a'(b'-b)+(a'-a)b\\ &=a'nl+nkb\\ &=n(a'l+kb) \end{align}$$
>   So $ab\equiv a'b'\mod{n}$.

***
#### Keywords
- [[Residue class]],
- [[Set of integers]],
- [[Division with remainder]],
- [[Divisibility]]
#### Possibly related
- 
***
#### Sources: