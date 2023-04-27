# Interval
***
###### tags: #Fundamental_math_objects #Topology 
***
>[!dsn]+ Direct strict note
>A subset $S$ of $\mathbb{R}$ is said to be the *interval* if for any $x,z\in S$ and $y\in\mathbb{R}$ are such that $x<y<z$, then $y\in S$.^[Sidney A. Morris - "Topology without tears" p.104]

>- Each singleton set $\{x\}$ is an interval.
>- Every interval has one of the following forms: $\{a\}$, $[a,b]$, $(a,b)$, $[a,b)$, $(a,b]$, $(-\infty,a)$, $(-\infty,a]$, $(a,\infty)$, $[a,\infty)$, $(-\infty,\infty)$.

>Every interval is homeomorphic to $(0,1)$, $[0,1]$, $[0,1)$ or $\{0\}$.
>>[!proof]+
>>

>Let $A=[a,b)\subset\mathbb{R}$. Then every element in $[a,b)$ is a limit point of $A$. The point $b$ also a limit point of $A$.
>>[!proof]+
>>


>Every open interval $(a,b)$, with $a<b$, is homeomorphic to $\mathbb{R}$.^[Sidney A. Morris - "Topology without tears" p.99]
>>[!proof]+
>> it's achivable via modified version of [[Homeomorphism between real line an open interval]]

#### Non-homeomorphic intervals
>[!dsn]+ Direct strict note
>If $a,b,c$ and $d$ are real numbers with $a<b$ and $c<d$, then
>1. $(a,b)\not\cong[c,d)$,
>2. $(a,b)\not\cong[c,d]$, and
>3. $[a,b)\not\cong[c,d]$.^[Sidney A. Morris - "Topology without tears" p.105]

>[!proof]+
>1. Let $(X,\tau)=[c,d)$ and $(Y,\tau_{1})=(a,b)$. Suppose that $(X,\tau)\cong(Y,\tau_{1})$. Then $X\setminus\{c\}\cong Y\setminus\{y\}$, by [[A homeomorphic spaces without one point are homeomorphic]], for some $y\in Y$. But $X\setminus\{c\}=(c,d)$ is an interval, therefore connected, while no matter which point we remove from $(a,b)$ the resultant space is disconnected. Hence by [[Connected topological space#Homeomorphisms preserves connectedness|Homeomorphisms preserves connectedness]]
>   $$X\setminus\{c\}\not\cong Y\setminus\{y\}\quad\forall y\in Y$$
>   This is a contradiction. So $[c,d)\not\cong(a,b)$.
>2. $[c,d]\setminus\{c\}$ is connected, while $(a,b)\setminus\{y\}$ is disconnected for all $y\in(a,b)$. Thus $(a,b)\not\cong[c,d]$.
>3. Suppose that $[a,b)\cong[c,d]$. Then $[c,d]\setminus\{c\}\cong[a,b)\setminus\{y\}$ for some $y\in[a,b)$. Therefore $([c,d]\setminus\{c\})\setminus\{d\}\cong([a,b)\setminus\{y\})\setminus\{z\}$, for some $z\in[a,b)\setminus\{y\}$; that is, $(c,d)\cong[a,b)\setminus\{y,z\}$, for some distinct $y$ and $z$ in $[a,b)$. But $(c,d)$ is connected, while $[a,b)\setminus\{y,z\}$, for any two distinct points $y$ and $z$ in $[a,b)$, is disconnected. So we have a contradiction. Therefore $[a,b)\not\cong[c,d]$.

>[!example]+ 
>


***
#### Keywords
- [[Set]],
- [[Real line]],
- [[Homeomorphism]],
- [[Limit point in topological space]],
- [[Connected topological space]],
#### Possibly related
- 
***
#### Sources: