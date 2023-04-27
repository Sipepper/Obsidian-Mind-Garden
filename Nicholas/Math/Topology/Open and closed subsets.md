# Open and closed subsets
***
###### tags: #Topology 
***
#### Open set
>[!dsn] Direct strict note
>Let $(X,\tau)$ be some topological space. Then any set from $\tau$ is said to be *open* in $(X,\tau)$.^[Sidney A. Morris - "Topology without tears" p.32]

>Let $\mathfrak{B}$ be a basis for a given topology $\tau$ on a set $X$. Then subset $U\subset X$ is open if and only if for any $x\in U$ there exists $B\in\mathfrak{B}$ such that $x\in B\subseteq U$.^[Sidney A. Morris - "Topology without tears" p.64]
>>[!proof]
>>Let $U$ be any subset of $X$. Assume that for each $x\in U$, there exists a $B_{x}\in\mathfrak{B}$ such that $x\in B_{x}\subseteq U$. Clearly $U=\bigcup_{x\in U}B_{x}$. So $U$ is a union of open sets and hence is open, as required.
>>The converse statement follows from necessary and sufficient conditions of topology basis.


>Let $U$ be some subset of $(X,\tau)$. Then $U\in\tau$ if and only if $\forall x\in U$ there exists a $V\in\tau$ such that $x\in V\subseteq U$.^[Sidney A. Morris - "Topology without tears" p.82]

###### Opennes in metric spaces using open balls
>[!dsn] Direct strict note
>Let $(X,d)$ be a metric space, and $\tau$ be a topology induced by metric $d$. Then subset $U\subseteq X$ will be open in $(X,\tau)$ if and only if for every point $a\in U$ there exist an $\varepsilon>0$ such that open ball $B_{\varepsilon}(a)\subseteq U$.^[Sidney A. Morris - "Topology without tears" p.132]

>[!proof]
>Assume that $U\in\tau$. Then by necessary and sufficient conditions for topology basis and [[Topology induced by a metric]], for any $a\in U$ there exists a point $b\in X$ and a $\delta>0$ such that $a\in B_{\delta}(b)\subseteq U$.
>
>Let $\varepsilon=\delta-d(a,b)$. Then 
>$$a\in B_{\varepsilon}(a)\subseteq U$$
>Conversely, assume that $U$ is a subset of $X$ with the property that for each $a\in U$ there exists an $\varepsilon_{a}>0$ such that $B_{\varepsilon_{a}}(a)\subseteq U$. Then by openness by basis and [[Topology induced by a metric]], $U$ is an open set.

#### Closed set
>[!dsn] Direct strict note
>Let $(X,\tau)$ be a topological space. A subset $S$ of $X$ is said to be a *closed set* in $(X,\tau)$ if its complement in $X$, namely $X\setminus S$, is open in $(X,\tau)$.^[Sidney A. Morris - "Topology without tears" p.34]

###### Properties
>Let $(X,\tau)$ be a topological space, then:
>- $\emptyset$ and $X$ are closed sets.
>- intersection of any number(any cardinality) of closed set is a closed set.
>- union of any finite number of closed sets is a closed set.

###### Closedness using neighbourhoods
>[!dsn] Direct strict note
>Let $A$ be a subset of a topological space $(X,\tau)$. Then the set $A$ is closed if and only if for each $x\in X\setminus A$ there is a neighbourhood $N$ of $x$ such that $N\subseteq X\setminus A$.^[Sidney A. Morris - "Topology without tears" p.82]
###### Closedness in metric space using sequences
>[!dsn] Direct strict note
>Let $(X,d)$ be a metric space. A subset $A$ of $X$ is closed in $(X,d)$ if and only if every converegent sequence of points in $A$ converges to a point in $A$, i.e. $A$ is closed in $(X,d)$ if and only if $a_{n}\to x$, where $x\in X$ and $a_{n}\in A$  for all $n$, implies $x\in A$.^[Sidney A. Morris - "Topology without tears" p.142]

>[!proof]
>Assume that $A$ is closed in $(X,d)$ and let $a_{n}\to x$, where $a_{n}\in A$ for all positive integers $n$. Suppose that $x\in X\setminus A$. Then, as $X\setminus A$ is an open set containing $x$, there exists an open ball $B_{\varepsilon}(x)$ such that $x\in B_{\varepsilon}(x)\subseteq X\setminus A$. Noting that each $a_{n}\in A$, this implies that $d(x,a_{n})>\varepsilon$ for each $n$. Hence the sequence $\{a_{n}\}$ does not converge to $x$. This is a contradiction. So $x\in A$, as required.
>
>Conversely, assume that every convergent sequence of points in $A$ converges to a point of $A$. Suppose that $X\setminus A$ is not open. Then there exists a point $y\in X\setminus A$ such that for each $\varepsilon>0$, $B_{\varepsilon}(y)\cap A\ne\emptyset$. For each positive integer $n$, let $x_{n}$ be any point in $B_{1/n}(y)\cap A$. Then we claim that $x_{n}\to y$. To see this let $\varepsilon$ be any positive real number, and $n_{0}$ any integer greater than $1/\varepsilon$. Then for each $n\ge n_{0}$.
>$$x_{n}\in B_{1/n}(y)\subseteq B_{1/n_{0}}(y)\subseteq B_{\varepsilon}(y)$$
>So $x_{n}\to y$ and, by our assumption, $y\notin A$. This is a contradiction and so $X\setminus A$ is open and thus $A$ is closed in $(X,d)$.

#### Clopen subset
>[!dsn] Direct strict note
>A subset $S$ of a topological space $(X,\tau)$ is said to be *clopen* if it is both open and closed in $(X,\tau)$.^[Sidney A. Morris - "Topology without tears" p.36]

>In every topological space $(X,\tau)$ both $X$ and $\emptyset$ are clopen.
#### Keywords
- [[Topological space]],
- [[Set]],
- [[Topology basis]],
- [[Metric space]],
- [[Topology induced by a metric]],
- [[Open ball in metric space]],
- [[Neighborhood in topological space]],
- [[Sequence]],
- [[Convergence in metric spaces]],
- [[Real line]],
#### Possibly related
- 
***
#### Sources: