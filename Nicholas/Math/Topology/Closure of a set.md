# Closure of a set
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $A$ be a subset of the topological space $(X,\tau)$. Then the set $A\cup A'$ which consists of $A$ and set $A'$ of all limit points of $A$ is called a *closure* of a set $A$ in $(X,\tau)$, denoted as $\overline{A}$.^[Sidney A. Morris - "Topology without tears" p.77]


>[!example] 
>Let $\mathbb{Q}$ be a set of all rational numbers, $\mathbb{Q}\subset\mathbb{R}$, then $\overline{\mathbb{Q}}=\mathbb{R}$.^[Sidney A. Morris - "Topology without tears" p.78]
>>[!proof]
>>Suppose $\overline{\mathbb{Q}}\ne\mathbb{R}$. Then there exists an $x\in\mathbb{R}\setminus\overline{\mathbb{Q}}$. As $\mathbb{R}\setminus\overline{\mathbb{Q}}$ is open in $\mathbb{R}$, there exxist $a,b$ with $a<b$ such that $x\in(a,b)\subseteq\mathbb{R}\setminus\overline{\mathbb{Q}}$. But in every interval $(a,b)$ there is a rational number $q$. So $q\in\mathbb{R}\setminus\overline{\mathbb{Q}}$ which implies $q\in\mathbb{R}\setminus\mathbb{Q}$. This is a contradiction, as $q\in\mathbb{Q}$. Hence $\overline{\mathbb{Q}}=\mathbb{R}$.

>[!example]
>Let $X=\set{a,b,c,d,e}$ and 
>$$\tau=\set{X,\emptyset,\{a\},\set{c,d},\set{a,c,d},\set{b,c,d,e}}$$
>then $\overline{\{b,e\}}$, $\overline{\set{a,c}}=X$, and $\overline{\set{b,d}}=\set{b,c,d,e}$
>>[!proof]
>>The closed sets are $\emptyset$,$X$,$\set{b,c,d,e}$,$\set{a,b,e}$,$\set{b,e}$ and $\{a\}$. So the smallest closed set containing $\{b\}$ is $\{b,e\}$; i.e. $\overline{b}=\set{b,e}$. Similarly $\overline{\set{a,c}}=X$, and $\overline{\set{b,d}}=\set{b,c,d,e}$.

#### Closure and "closedness"
>[!dsn] Direct strict note
>Let $A$ be a subset of topological space $(X,\tau)$. Then closure $\overline{A}$ is a closed set in $(X,\tau)$, moreover it's the *smallest* closed set containing $A$.^[Sidney A. Morris - "Topology without tears" p.77]

>[!proof]
>From definition of a closed set as a set which contains all of it's limit point it suffices to show that the set $A\cup A'$ contains all of *its* limit points or equivalently that no element of $X\setminus(A\cup A')$ is a limit point of $A\cup A'$.
>
>Let $p\in X\setminus(A\cup A')$. As $p\notin A'$, there exists an open set $U$ containing $p$ with $U\cap A=\{p\}$ or $\emptyset$. But $p\notin A$, o $U\cap A=\emptyset$. We claim also that $U\cap A'=\emptyset$. For if $x\in U$ then as $U$ is an open set and $U\cap A=\emptyset$, $x\notin A'$. Thus $U\cap A'=\emptyset$. That is, $U\cap(A\cup A')=\emptyset$, and $p\in U$. This implies $p$ not as a limit point of $A\cup A'$ and so $A\cup A'$ is a closed set.
>Also because if $T\subseteq S$, where $T$ and $S$ are some subsets of $(X,\tau)$, and $p$ is a limit point in $T$ then it's also a limit point in $S$, every closed set containing $A$ must also contain the set $A'$. So $A\cup A'=\overline{A}$ is the smallest closed set containing $A$. This implies that $\overline{A}$ is the intersection of all closed sets containing $A$.
***
#### Keywords
- [[Set]],
- [[Topological space]],
- [[Limit point in topological space]],
- [[Rational numbers]],
- [[Real line]],
- [[Open and closed subsets]],
- [[Euclidean topology]],
- [[Interval]],
#### Possibly related
- 
***
#### Sources: