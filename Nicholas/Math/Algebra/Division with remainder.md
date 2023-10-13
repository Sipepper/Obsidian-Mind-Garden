# Division with remainder
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Theorem
>Let $a,b\in\mathbb{Z}$, $b\ne0$. Then exists a unique $q\in \mathbb{Z}$ and $r\in\mathbb{Z}$, such that
>$$a=bq+r\qquad 0\le r<|b|$$

>[!proof]+
>Let $b>0$, consider a set
>$$S:=\{a-bx:x\in\mathbb{Z},a-bx\ge0\}\subset\mathbb{N}$$
>then
>$$a<0\quad x=a\quad a-ba=a(1-b)\ge0$$
>$$a\ge0\quad x=0\quad a-ba=a\ge0$$
>As $(\mathbb{N},<)$ is linearly ordered, there exists a minimal element
>$$\min_{k\in S}k=z\in[0,|b|)$$
>suppose it's false, that is $r>|b|$, then
>$$r-b=a-bk-b=a-b(k+1)\ge0$$
>so $z-b\in S$, which contradicts the choose of $r$ as minimal element.
>So such element exists. Now to prove uniqueness
>$$\begin{align}a=bq+r&=bq'+r'\\ bq-bq'&=r'-r\\ b(q-q')&=(r'-r) \\ b|(r'-r)&\Rightarrow r'-r\ge b\end{align}$$
>which leads to contradiction as
>$$-|b|<(r'-r)<|b|$$

>[!example]+ 
>Let $a=28$ and $b=5$, then $a=5\cdot 5+3$.
***
#### Keywords
- [[Set of integers]],
- [[Absolute value]],
- [[Linearly ordered set]],
- [[Greatest element, upper bound and maximal element of a partially ordered set]],
- [[Divisibility]]
#### Possibly related
- 
***
#### Sources: