# Product of completely regular spaces is completely regular
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>If $\{(X_{i},\tau_{i}):i\in I\}$ is any family of completely regular spaces, then $\prod_{i\in I}(X_{i},\tau_{i})$ is completely regular.^[Sidney A. Morris - "Topology without tears" p.275]

>[!proof]+
>Let $a=\prod_{i\in I}a_{i}\in\prod_{i\in I}X_{i}$ and $U$ be any open set containing $a$. Then there exists a finite subset $J$ of $I$ and sets $U_{i}\in\tau_{i}$ such that
>$$a\in\prod\limits_{i\in I}U_{i}\subseteq U$$
>where $U_{i}=X_{i}$ for all $i\in I\setminus J$. As $(X_{j},\tau_{j})$ is completely regular for each $j\in J$, there exists a continuous mapping $f_{j}:(X_{j},\tau_{j})\to[0,1]$ such that $f_{j}(a_{j})=0$ and $f_{j}(y)=1$, for all $y\in X_{j}\setminus U_{j}$. Then $f_{j}\circ p_{j}:\prod_{i\in I}(X_{i},\tau_{i})\to[0,1]$, where $p_{j}$ denotes the projection of $\prod_{i\in I}(X_{i},\tau_{i})$ onto $(X_{j},\tau_{j})$.
>
>If we put $f(x)=\max\{f_{j}\circ p_{j}(x):j\in J\}$, for all $x\in\prod_{i\in I}X_{i}$, then $f:\prod_{i\in I}(X_{i},\tau_{i})\to[0,1]$ is continuous as $J$ is finite. Further, $f(a)=0$ while $f(y)=1$ for all $y\in X\setminus U$. So $\prod_{i\in I}(X_{i},\tau_{i})$ is completely regular.


>[!example]+ 
>
***
#### Keywords
- [[Completely regular and Tychonoff spaces]],
- [[Product topology]],
- [[Open and closed subsets]],
- [[Cardinality of a set]],
- [[Set]],
- [[Neighborhood in topological space]],
- [[Continuous mapping]],
- [[Projection map in product spaces]],
- [[Interval]],
- [[Function(mapping)]]
#### Possibly related
- 
***
#### Sources: