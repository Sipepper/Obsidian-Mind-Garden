# Clopen subsets of the set of real numbers
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $T$ be a clopen subset of $\mathbb{R}$. Then either $T=\mathbb{R}$ or $T=\emptyset$.^[Sidney A. Morris - "Topology without tears" p.86]

>[!proof]
>Suppose that $T\ne\mathbb{R}$ and $T\ne\emptyset$. Then there exists an element $x\in T$ and an element $z\in\mathbb{R}\setminus T$. Without loss of generality, assume that $x<z$. Put $S=T\cap[x,z]$. Then $S$, being the intersection of two closed sets, is closed. It is also bounded above, since $z$ is obviously an upper bound. Let $p$ be the supremum of $S$. By lemma [[Об ограниченных подмножествах множества действительных чисел|about bounded subsets of the real number line]], $p\in S$. Since $p\in[x,z]$, $p\le z$. As $z\in\mathbb{R}\setminus S$, $p\ne z$ and so $p<z$.
>Now $T$ is also an open set and $p\in T$. So there exist $a$ and $b$ in $\mathbb{R}$ with $a<b$ such that $p\in(a,b)\subseteq T$. Let $t$ be such that $p<t<\min(b,z)$. So $t\in T$ and $t\in[p,z]$. Thus $t\in T\cap[x,z]=S$. This is a contradiction since $t>p$ and $p$ is a supremum of $S$. Hence our supposition is false and consequently $T=\mathbb{R}$ or $T=\emptyset$.
***
#### Keywords
- [[Открытое и замкнутое множества]],
- [[Множество действительных чисел]],
- [[Супремум и инфинум]],
- [[Ограниченное множество]],
#### Possibly related
- 
***
#### Sources: