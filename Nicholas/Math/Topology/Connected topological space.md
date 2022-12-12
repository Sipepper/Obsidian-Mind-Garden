# Connected topological space
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $(X,\tau)$ be a topological space. Then it is said to be *connected* if only clopen subsets in $(X,\tau)$ are $X$ and $\emptyset$.^[Sidney A. Morris - "Topology without tears" - p.87]

>[!example] 
>Let $X=\set{a,b,c,d,e}$ and $$\tau=\set{X,\emptyset,\{a\},\{c,d\},\{a,c,d\},\{b,c,d,e\}}$$ then $(X,\tau)$ is not connected, because $\set{b,c,d,e}$ is a clopen nonempty subset.

>[!example]
>Let $(X,\tau)$ any discrete space with one or more elements, then $(X,\tau)$ is not connected because every singleton set is a clopen subset.

>[!example]
>Topological space $\mathbb{R}$ is connected. Because only clopen subsets in $\mathbb{R}$ is $\emptyset$ and $\mathbb{R}$. This follows from [[Clopen subsets of the set of real numbers]].

#### Continuous surjective mappings preserve connectedness
>[!dsn]
>Let $(X,\tau)$ and $(Y,\tau_{1})$ be a topological spaces and $f:(X,\tau)\to(Y,\tau_{1})$ is a surjective continuous mapping. If $(X,\tau)$ is connected, then $(Y,\tau_{1})$ will also be connected.

>[!proof]
>Let $d:f(X)\to D$ be a discrete valued mapping. The $d\circ f$ be a discrete balued mapping on $X$ and thus must be constant. But it means that $d$ is a constant mapping, therefore $f(X)$ will be connected space.^[Glen E. Bredon - "Topology and geometry" p.11]

#### Homeomorphisms preserves connectedness
>[!dsn]
>Any topological space homeomorphic to a connected space, is also connected.^[Sidney A. Morris - "Topology without tears" p.102]

>[!proof]
>It's true because homeomorphism is also a surjective continuous mapping, by [[Connected topological space#Continuous surjective mappings preserve connectedness|continuous surjective mappings preserve connectedness]] we know that such mapping preserve connectedness. Thus homeomorhism preserve connectedness as required.
***
#### Keywords
- [[Topological space]],
- [[Открытое и замкнутое множества]],
- [[Дискретная топология]],
- [[Евклидова топология]],
- [[Множество действительных чисел]],
- [[Function(mapping)]],
- [[Непрерывное отображение]],
- [[Дискретно-значное отображение]],
- [[Homeomorphism]],
#### Possibly related
- 
***
#### Sources: