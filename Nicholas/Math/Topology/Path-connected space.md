---
Last time checked: 2024-03-12
Complete: false
aliases:
---
# Path-connected space
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>A topological space $(X,\tau)$ is said to be *path-connected* (or *pathwise connected*) if for each pair of distinct points $a$ and $b$ of $X$ ther exists a continuous mapping $f:[0,1]\to(X,\tau)$, such that $f(0)=a$ and $f(1)=b$. The mapping $f$ is said to be a *path joining $a$ to $b$*.^[[[Sidney A. Morris - Topology without tears.pdf#page=118|Sidney A. Morris - "Topology without tears" p.118]]]

>[!example]+
>Every interval is path-connected.
>>[!proof]+
>>

>[!example]+
>For each $n\ge1$, $\mathbb{R}^{n}$ is path-connected.
>>[!proof]+
>>

>Every path-connected space is connected.^[[[Sidney A. Morris - Topology without tears.pdf#page=118|Sidney A. Morris - "Topology without tears" p.118]]]
>>[!proof]+
>>Let $(X,\tau)$ be a path-connected space and suppose that it is not connected.
>>Then it has a proper non-empty clopen subset $U$. So there exist $a$ and $b$ such that $a\in U$ and $b\in X\setminus U$. As $(X,\tau)$ is path-connected there exists a continuous function $f:[0,1]\to(X,\tau)$ such that $f(0)=0$ and $f(1)=b$.
>>However, $f^{-1}(U)$ is a clopen subset of $[0,1]$. As $a\in U$, $0\in f^{-1}(U)$ and so $f^{-1}(U)\ne\emptyset$. As $b\notin U$, $1\notin f^{-1}(U)$ and thus $f^{-1}(U)\ne[0,1]$. Hence $f^{-1}(U)$ is a proper non-empty clopen subset of $[0,1]$, which contradicts the connectedness of $[0,1]$.
>>Consequently $(X,\tau)$ is connected.

>[!example]+ 
>Not every connected space is path-connected. Consider the following subspace of $\mathbb{R}^{2}$:
>$$X=\{(x,y):y=\sin(1/x),0<x\le1\}\cup\{(0,y):-1\le y\le1\}$$
>then $X$ is connected but not path connected. There is no path joining $(0,0)$ to, say, the point $(1/\pi,0)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=119|Sidney A. Morris - "Topology without tears" p.119]]]
>>[!proof]+
>>

***
#### Keywords
- [[Topological space]],
- [[Continuous mapping]],
- [[Interval]],
- [[Open and closed subsets]],
- [[Function(mapping)]],
- [[Euclidean space]],
- [[Connected topological space]],
- [[Set]],
- [[Trigonometric functions]],
#### Possibly related
- 
***
#### Sources: