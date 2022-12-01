
# Component of topological space
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $(X,\tau)$ be a topological space and $x$ is an arbitrary point of this space. Then the *component*(or *connectedness component*) in $X$ of point $x$, denoted by $C_{X}(x)$, we call the union of connected subsets of $X$ which contains $x$.

#### Component is connected
>[!dsn] Direct strict note
>Let $x$ be an arbitrary point of topological space $(X,\tau)$. Then $C_{X}(x)$ - connected.

>[!proof]
>Let $\set{C_{i}:i\in I}$ be a family of all connected subsets of space $(X,\tau)$ which contains point $x$. Then $C_{X}(x)=\bigcup_{i\in I}C_{i}$.
>
>Let $O$ be the subset of component $C_{X}(x)$ which is clopen in subspace topology on $C_{X}(x)$ induced by $\tau$. Then $O\cap C_{i}$ will be an clopen subset in topology on $C_{i}$.
>
>Because every $C_{i}$ is connected, then $O\cap C_{i}=C_{i}$ or $\emptyset$. If $O\cap C_{j}=C_{j}$ for some $j\in I$, then $x\in O$. In this case $O\cap C_{i}\ne\emptyset$, $\forall i\in I$ because every $C_{i}$ contains $x$. Therefore $O\cap C_{i}=C_{i}$ or $O\cap C_{i}=\emptyset$ for all $i\in I$; i.e. $O=C_{X}(x)$ or $O=\emptyset$.
>
>Thus we obtain that $C_{X}(x)$ have no proper non-empty clopen subsets and therefore is connected.
#### Equality of components
>[!dsn] Direct strinct note
>Let $a$ and $b$ - two point of topological space $(X,\tau)$. If exists connected space $C$ which contains $a$ and $b$ then $C_{X}(a)=C_{X}(b)$.

>[!proof] 
>By definition of component we know that $C_{X}(a)\supseteq C$ and $C_{X}(b)\supseteq C$. Therefore $a\in C_{X}(b)$.
>
>Because every component is connected, $C_{X}(b)$ is connected and also a connected set which contains $a$. Therefore from definition of component we obtain $C_{X}(b)\supseteq C_{X}(a)$.
>In similar manner we can show that $C_{X}(b)\supseteq C_{X}(a)$, thus $C_{X}(a)=C_{X}(b)$.

#### Component is a closed subset
>[!dsn] Direct strict note
>Component is a closed subset.

>[!proof] 
>Because closure of connected space is connected, and component by definition is the biggest connected subset containing a point, the closure must be equal to the set, thus the component is closed.

>[!example] 
>Let $(X,\tau)=[0,1]\cup[2,3]\cup[4,5]$ be the topological space with subspace topology induced by euclidean topology on $\mathbb{R}$. Then for point $x_{1}\in[0,1]$ the component is equal to $[0,1]$, for $x_{2}\in[2,3]$ the component is equal to $[2,3]$ etc.
***
#### Keywords
- [[Topological space]],
- [[Связное топологическое пространство]],
- [[Открытое и замкнутое множества]],
- [[Подпространственная топология]],
- [[Замыкание множества]],
- [[Евклидова топология]]
#### Possibly related
- [[Окрестность точки]]
***
#### Sources: