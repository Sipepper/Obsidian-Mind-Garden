# Fixed points of a continuous mapping of interval to itself
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $f$ be a continuous mapping of $[0,1]$ into $[0,1]$. Then there exists a $z\in[0,1]$ such that $f(z)=z$, i.e. $z$ is the fixed point.^[Sidney A. Morris - "Topology without tears" p.120]

>This proposition is a special case of the [[Brouwer fixed point theorem]].

>[!proof]
>If $f(0)=0$ or $f(1)=1$, the result is obvious. Thus it suffices to consider the case when $f(0)>0$ and $f(1)<1$.
>Let $g:[0,1]\to\mathbb{R}$ be defined by $g(x)=x-f(x)$. Clearly $g$ is continuous, $g(0)=-f(0)$, and $g(1)=1-f(1)>0$. Consequently by corollary [[Weierstrass Itermediate Value theorem#5.2.10. Следствие о нуле функции|existence of zero of a funtion]], there exists a $z\in[0,1]$ such that $g(z)=0$; that is , $z-f(z)=0$ or $f(z)=z$.

>[!example] 
>
***
#### Keywords
- [[Continuous mapping]],
- [[Interval]],
- [[Fixed point]],
- [[Function(mapping)]],
#### Possibly related
- 
***
#### Sources: 