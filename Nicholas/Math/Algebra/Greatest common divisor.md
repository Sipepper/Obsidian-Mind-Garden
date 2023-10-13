# Greatest common divisor
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Definition
>Let $a,b\in\mathbb{Z}$. Number $d\ge0$ is said to be a *greatest common divisor* (or GCD for short) if
>- $(d|a)\land(d|b)$
>- $((c|a)\land(c|b))\Rightarrow c|d$

>[!example]+ 
>Let $a=14$, $b=35$, then $GCD(14,35)=7$, as $14=7\cdot 2$ and $35=7\cdot 5$.

>The greatest common divisor $d$ of integers $a$ and $b$ is always exists. Moreover 
>1. There exists such $m,n\in\mathbb{Z}$ such that
>   $$d=am+bn$$
>2. If $a\cdot b\ne0$, then $GCD(a,b)$ - is a smallest linear combination of $a$ and $b$.
>
>>[!proof]+
>>If $a=b=0$, then 
>>$$GCD(0,0)=0=0\cdot m+0\cdot n$$
>>
>>Suppose that $a\ne0$, consider a set
>>$$S=\{ma+nb:m,n\in\mathbb{Z},ma+nb>0\}$$
>>If $m=a$ and $n=b$, $ma+nb=a^{2}+b^{2}$ thus $S$ is non-empty. Let $d$ be the smallest element of $S$ which exists as $S\subset\mathbb{N}$ is totally ordered.
>>1. Suppose that $d\nmid a$, so $a=d\cdot q+r$, where $0<r<d$, but 
>>   $$\begin{align}r=a-dq&=a-maq-nbq\\ &=a(1-mq)-(nq)b \end{align}$$
>>   but this leads to contradiction as $r\in S$ and $r<d$, which contradict the choose of $d$. So $d|a$ and analogously $d|b$.
>>2. Suppose that $(c|a)\land(c|b)$ which means that $a=uc$ and $b=vc$, then
>>   $$d=ma+nb=muc+nvc=c(mu+nv)$$
>>   from which $c|d$

***
#### Keywords
- [[Set of integers]],
- [[Divisibility]],
- [[Logical operators]],
- [[Set]],
- [[Linearly ordered set]],
- [[Division with remainder]]
#### Possibly related
- 
***
#### Sources: