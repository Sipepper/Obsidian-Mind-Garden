# About compact metrizable space as an image of continuous mapping of compact metric space
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $f$ be a continuous mapping of a compact metric space $(X,d)$ onto(surjective) a Hausdorff space $(Y,\tau_{1})$. Then $(Y,\tau_{1})$ is compact and metrizable.^[Sidney A. Morris - "Topology without tears" p.250]

>[!proof]
>Since every continuous image of a compact space is compact, the space $(Y,\tau_{1})$ is certainly compact. As the map $f$ is surjective, we can define a metric $d_{1}$ on $Y$ as follows: for each $y_{1},y_{2}\in Y$, $d_{1}(y_{1},y_{2})$ equals
>$$\inf\limits_{n\in\mathbb{N}}\set{d(a_{1},b_{1})+\dots+d(a_{n},b_{n}):f(a_{1})=y_{1}, f(b_{n})=y_{2}, b_{i}=a_{i+1},i=1,\dots,n-1}$$
>We need to show that $d_{1}$ is indeed a metric(If, somehow i will need this proof, i will complete it)
>Let $\tau_{2}$ be the topology induced on $Y$ by $d_{1}$. We have to show that $\tau_{1}=\tau_{2}$.
>Firstly, by the definition of $d_{1}$, $f:(X,\tau)\to(Y,\tau_{2})$ is certainly continuous and so $(X,\tau_{2})$ is compact.
>Observe that for a subset $C$ of $Y$,
>$$\begin{align}&C \text{ is a closed subset of }(Y,\tau_{1}) \\ \Rightarrow& f^{-1}(C)\text{ is a closed subset of }(X,\tau)\\ \Rightarrow& f^{-1}(C)\text{ is a compact subset of }(X,\tau)\\ \Rightarrow& f(f^{-1}(C))\text{is a compact subset of }(Y,\tau_{2})\\ \Rightarrow& C\text{ is a compact subset of }(Y,\tau_{2}) \\ \Rightarrow& C\text{ is closed in }(Y,\tau_{2}) \end{align}$$ 
>So $\tau_{1}\subseteq\tau_{2}$. Similarly we can prove $\tau_{2}\subseteq\tau_{1}$, and thus $\tau_{1}=\tau_{2}$

>[!example] 
>
***
#### Keywords
- [[Continuous mapping]],
- [[Compact set]],
- [[Function(mapping)]],
- [[Hausdorff space]],
- [[Compact set]],
- [[Supremum and infinum]],
- [[Metric space]],
- [[Topology induced by a metric]],
- [[Topological space]],
- [[Open and closed subsets]],
#### Possibly related
- 
***
#### Sources: