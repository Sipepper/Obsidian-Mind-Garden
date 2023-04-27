# Metric space
***
###### tags: #Fundamental_math_objects  
***
>[!dsn] Direct strict note
>Let $X$ be some non-empty set, and $d$ be a function defined on $X\times X$ such that $\forall a,b\in X$ the following condition holds:
>1. $d(a,b)\ge0$ and $d(a,b)=0$ if and only if $a=b$
>2. $d(a,b)=d(b,a)$
>3. $d(a,c)\le d(a,b)+d(b,c)$, $\forall a,b,c\in X$ (*triangle inequality*)
>Such function $d$ is called a *metric* on $X$.^[Sidney A. Morris - "Topology without tears" c.124]

>The pair $(X,d)$, is called a *metric space*. 

>The falue of $d$ in points $a$ and $b$ is called a *distance* between points $a$ and $b$.
#### Discrete metric
>[!example] 
>Let $X$ be a non-empty set, define a metric $d:X\times X\to\mathbb{R}$ in the following way 
>$$d(a,b)=\begin{cases}0&a=b\\1&a\ne b \end{cases}$$
>Then function $d$ will be a metric on $X$ which is called a *discrete metric*.

#### Metrics on the set of continuous functions
>[!example] Area between graphs
>We can define a metric on $C_[0,1]$ by 
>$$d(f,g)=\int_{0}^{1}|f(x)-g(x)|dx$$ 
>where $f,g\in C_[0,1]$
>
>$d(f,g)$ exactly describes the area between of two functions on the $[0,1]$ interval.

>[!example] Maximum difference
>Let $C_{[0,1]}$ be a set of continuous functions from $[0,1]$ to $\mathbb{R}$. We can define a different metric by 
>$$d^{*}(f,g)=\sup\{|f(x)-g(x)|:x\in[0,1]\}$$
>
>$d^{*}$ is exactly the maximum difference in values of two functions on $[0,1]$.

#### Metrics on Euclidean space
>[!example] "Cubes" metric
>$$d^{*}(a,b)=\max\limits_{1\le i\le n}\set{|a_{i}-b_{i}|}$$ 
>(every ball in such space is has the form of a cube)

>[!example] "Manhattan" metric
>$$d_{1}(a,b)=\sum\limits_{i=1}^{n}|a_{i}-b_{i}|$$
>(metric in which there are no "diagonal moves")
***
#### Keywords
- [[Euclidean space]],
- [[Function(mapping)]],
- [[Cartesian product of sets]],
- [[Set]],
- [[Space of all continuous functions on the interval]],
- [[Supremum and infinum]],
- [[Open ball in metric space]]
#### Possibly related
- 
***
#### Sources: