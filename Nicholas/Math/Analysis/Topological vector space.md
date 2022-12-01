# Topological vector space
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $V$ be a vector space, if we endow it with topology $\tau$ we can construct a *topological vector space*(or *TVS* in short). Except axioms of vector space and axioms of topological space, next two conditions must hold 
>1. Every point of space $(V,\tau)$ must be a closed set.
>2. Operation of addition and multiplication by a scalar must be continous mappings with respect to topology $\tau$.^[Fabio Silva Botelho - "Functional analysis and applied optimization in banach spaces" p.6]

#### Continuity of operations
Addition will be continuous if for any two vectors $u,v\in U$ and $\mathcal{V}\in\tau$ such that $u+v\in\mathcal{V}$, exists two neighbourhoods $\mathcal{V}_{u}\ni u$ and $\mathcal{V}_{v}\ni v$ such that $\mathcal{V}_{u}+\mathcal{V}_{v}\subset$.

Multiplication by scalar will be continuous if for $\alpha\in\mathbb{F}$,$u\in U$ and $\mathcal{V}\ni\alpha\cdot u$, exists $\delta>0$ and $\mathcal{V}\ni u$ such that $\forall\beta\in\mathbb{F}$ from condition $|\beta-\alpha|<\delta$ will follow that $\beta\mathcal{V}_{u}\subset\mathcal{V}$. 

>$A\subset U$ is an open set, then $\forall u\in A$, exists neighbourhood $\mathcal{V}$ of point $\theta$ (zero vector) such that $u+\mathcal{V}\subset A$.

>Because transition by a vector and scaling is a continuous mappings we can deduce that local basis of topology and basis of topology are equivalent, i.e. generate the same topology.

>[!example] 
>
***
#### Keywords
- [[Vector space]],
- [[Topological space]],
- [[Открытое и замкнутое множества]],
- [[Непрерывное отображение]],
- [[Окрестность точки]],
- [[Базис топологии]],
- [[Локальный базис топологии]]
#### Possibly related
-  
***
#### Sources: