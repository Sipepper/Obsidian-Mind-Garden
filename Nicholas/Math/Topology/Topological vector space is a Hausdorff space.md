---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Topological vector space is a Hausdorff space
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Any topological vector space $U$ is a Hausdorff space.^[Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.7]

>[!proof]
>Pick $u_{0},u_{1}\in U$ such that $u_{0}\ne u_{1}$. Thus $\mathcal{V}=U\setminus\set{u_{1}-u_{0}}$ is an open neighborhood of zero. As $\theta+\theta=\theta$, by the continuity of addition, there exist $\mathcal{V}_{1}$ and $\mathcal{V}_{2}$ neighborhoods of $\theta$ such that
>$$\mathcal{V}_{1}+\mathcal{V}_{2}\subset\mathcal{V}$$
>define $\mathcal{U}=\mathcal{V}_{1}\cap\mathcal{V}_{2}\cap(-\mathcal{V}_{1})\cap(-\mathcal{V}_{2})$, thus $\mathcal{U}=-\mathcal{U}$ (symmetric) and $\mathcal{U}+\mathcal{U}\subset\mathcal{V}$ and hence 
>$$u_{0}+\mathcal{U}+\mathcal{U}\subset u_{0}+\mathcal{V}\subset U\setminus\set{u_{1}}$$
>so that
>$$u_{0}+v_{1}+v_{2}\ne u_{1},\quad\forall v_{1},v_{2}\in\mathcal{U}$$
>or
>$$u_{0}+v_{1}\ne u_{1}-v_{2},\quad\forall v_{1},v_{2}\in\mathcal{U}$$
>and since $\mathcal{U}=-\mathcal{U}$
>$$(u_{0}+\mathcal{U})\cap(u_{1}+\mathcal{U})=\emptyset$$
***
#### Keywords
- [[Topological vector space]],
- [[Hausdorff space]],
- [[Neighborhood in topological space]],
- [[Open and closed subsets]],
#### Possibly related
- 
***
#### Sources:

