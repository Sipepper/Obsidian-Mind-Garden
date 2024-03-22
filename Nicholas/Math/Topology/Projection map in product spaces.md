---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Projection map in product spaces
***
###### tags: #Topology 
***
#### Finite case
>[!dsn]+ Definition
>Let $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ be topological spaces and $(X_{1}\times X_{2}\times\dots\times X_{n},\tau)$ their product space.
>For each $i\in\{1,\dots,n\}$, let $p_{i}:X_{1}\times X_{2}\times\dots\times X_{n}\to X_{i}$ be the *projection mapping*; that is $p_{i}((x_{1},x_{2},\dots,x_{i},\dots,x_{n}))=x_{i}$, for each $(x_{1},x_{2},\dots,x_{i},\dots,x_{n})\in X_{1}\times X_{2}\times\dots\times X_{n}$. Then
>1. each $p_{i}$ is a continous surjective open mapping
>2. $\tau$ is the coarsest topology on the set $X_{1}\times X_{2}\times\dots\times X_{n}$ such that each $p_{i}$ is continuous.

>[!proof]+
>Clearly each $p_{i}$ is surjective. To see that each $p_{i}$ is continuous, let $U$ be any open set in $(X_{i},\tau_{i})$. Then
>$$p_{i}^{-1}(U)=X_{1}\times X_{2}\times\dots\times X_{i-1}\times U\times X_{i+1}\times\dots\times X_{n}$$
>which is a product of open sets and so is open in $(X_{1}\times X_{2}\times\dots\times X_{n},\tau)$. Hence each $p_{i}$ is continuous.
>To show that $p_{i}$ is an open mapping it suffices to verify that for each basic open set $U_{1}\times U_{2}\times\dots\times U_{n}$, where $U_{j}$ is open in $(X_{j},\tau_{j})$, for $j=1,\dots,n$, the set $p_{i}(U_{1}\times U_{2}\times\dots\times U_{n})$ is open in $(X_{i},\tau_{i})$. But $p_{i}(U_{1}\times U_{2}\times\dots\times U_{n})=U_{i}$ which is, of course, open in $(X_{i},\tau_{i})$. So eah $p_{i}$ is an open mapping. We have now verified part $(1)$ of the proposition.
>Now let $\tau'$ be any topology on the set $X_{1}\times X_{2}\times\dots\times X_{n}$ such that each projection mapping $p_{i}:(X_{1}\times X_{2}\times\dots\times X_{n},\tau')\to(X_{i},\tau_{i})$ is continous. We have to show that $\tau'\supseteq\tau$.
>Recalling the definition of the basis for the topology $\tau$([[product topology#finite case]]) it suffices to show that if $O_{1},O_{2},\dots,O_{n}$ are open sets in $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ respectively, then $O_{1}\times O_{2}\times\dots\times O_{n}\in\tau'$. To show this, observe that as $p_{i}$ is continous, $p_{i}^{-1}(O_{i})\in\tau'$, for each $i=1,\dots,n$. Now
>$$p_{i}^{-1}(O_{i})=X_{1}\times X_{2}\times\dots\times X_{i-1}\times O_{i}\times X_{i+1}\times\dots\times X_{n}$$
>so that
>$$\bigcap\limits_{i=1}^{n}p_{i}^{-1}(O_{i})=O_{1}\times O_{2}\times\dots\times O_{n}$$
>Then $p_{i}^{-1}(O_{i})\in\tau'$ for $i=1,\dots,n$, implies $\bigcap_{i=1}^{n}p_{i}^{-1}(O_{i})\in\tau'$; that is $O_{1}\times O_{2}\times\dots\times O_{n}\in\tau'$, as required.

>Thus we now have another way of *defining* the product topology. Given topological spaces $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ be the product topology can be defined as the *coarsest* topology on $X_{1}\times X_{2}\times\dots\times X_{n}$ such that each projection $p_{i}:X_{1}\times X_{2}\times\dots\times X_{n}\to X_{i}$ is continous.

>For $n\ge2$, the projection mappings of $\mathbb{R}^{n}$ onto $\mathbb{R}$ are continuous open mappings.

>Let $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ be topological spaces and $(X_{1}\times X_{2}\times\dots\times X_{n},\tau)$ the product space. Then each $(X_{i},\tau_{i})$ is homeomorphic to a subspace of $(X_{1}\times X_{2}\times\dots\times X_{n},\tau)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=201|Sidney A. Morris - "Topology without tears" p.201]]]
>>[!proof]+
>>p201

>[!example]+ 
>

#### Countable case
>[!dsn]+ Direct strict note
>Let $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n}),\dots$ be a countably infinite family of topological spaces and $(\prod_{i=1}^{\infty}X_{i},\tau)$ their product space. For each $i$, let $p_{i}:\prod_{j=1}^{\infty}X_{j}\to X_{i}$ be the *projection mapping*; that is $p_{i}((x_{1},x_{2},\dots,x_{n},\dots))=x_{i}$ for each $(x_{1},x_{2},\dots,x_{n},\dots)\in\prod_{j=1}^{\infty}X_{j}$. Then
>1. each $p_{i}$ is a continous surjective open mapping
>2. $\tau$ is the coarsest topology on the set $\prod_{j=1}^{\infty}X_{j}$ such that each $p_{i}$ is continuous.^[[[Sidney A. Morris - Topology without tears.pdf#page=225|Sidney A. Morris - "Topology without tears" p.225]]]

>[!proof]+
>

>[!example]+ 
>
#### Case of arbitrary cardinality
>[!dsn]+ Direct strict note
>Let $I$ be a set and let $\{(X_{i},\tau_{i}):i\in I\}$ be a family of topological spaces having product space $\left(\prod_{i\in I}X_{i},\tau\right)$. For each $j\in I$, let $p_{j}:\prod_{i\in I}X_{i}\to X_{j}$ be the projection mapping; that is, $p_{j}\left(\prod_{i\in I}x_{i} \right)=x_{j}$, for each $\prod_{i\in I}x_{i}\in\prod_{i\in I}X_{i}$. Then
>1. each $p_{j}$ is a continous surjective open mapping
>2. $\tau$ is the coarsest topology on the set $\prod_{i\in I}X_{i}$ such that each $p_{j}$ is continuous.

>[!proof]+
>

>[!example]+
>
***
#### Keywords
- [[Topological space]],
- [[Product topology]],
- [[Cartesian product of sets]],
- [[Function(mapping)]],
- [[Continuous mapping]],
- [[Open and closed mappings]],
- [[Topology comparison]],
- [[Preimage]],
- [[Open and closed subsets]],
- [[Topology basis]],
- [[Euclidean space]],
- [[Real line]],
- [[Subspace topology]],
- [[Cardinality of a set]],
#### Possibly related
- 
***
#### Sources: