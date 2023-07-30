# Every normal second countable Hausdorff space is metrizable
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Every normal second countable Hausdorff space $(X,\tau)$ is metrizable.^[Sidney A. Morris - "Topology without tears" p.283]

>[!proof]+
>It suffices to show that $(X,\tau)$ can be embedded in the Hilbert cube $I^{\infty}$. By [[The embedding lemma]] and as every [[hausdorff space]] is a [[T1 space]], to verigy that $(X,\tau)$ can be embedded in the Hilbert cube it is enough to find a countable family of continuous maps of $(X,\tau)$ into $[0,1]$ which separates points and closed sets.
>
>Let $\mathcal{B}$ be a countable basis for $\tau$, and consider the set $\mathcal{S}$ of all pairs $(V,U)$ such that $U\in\mathcal{B}$, $V\in\mathcal{B}$ and $\overline{V}\subseteq U$. Then $S$ is countable. For each pair $(V,U)$ in $\mathcal{S}$ we can, by [[Every T4 space is T3.5 space]] and [[Normality criterion or Urysohn lemma]], find a continuous mapping 
>$$f_{VU}\colon(X,\tau)\to[0,1]$$
>such that $f_{VU}(\overline{V})=0$ and $f_{VU}(X\setminus U)=1$. Put $\mathcal{F}$ equal to the family of functions, $f$, so obtained. Then $\mathcal{F}$ is countable by [[Properties of countable sets]].
>To see that $\mathcal{F}$ separates points and closed sets, let $x\in X$ and $W$ any open set containing $x$. Then there exists a $U\in\mathcal{B}$ such that $x\in U\subseteq W$. By [[Regular and T3 space]](need clarification), $(X,\tau)$ is regular and so there exists a set $P\in\tau$ such that $x\in\overline{V}\subseteq\overline{P}\subseteq U$. Therefore there exists a $V\in\mathcal{B}$ with $x\in V\subseteq P$. So $x\in\overline{V}\subseteq\overline{P}\subseteq U$. Then $(V,U)\in\mathcal{S}$ and if $f_{VU}$ is the corresponding mapping in $\mathcal{F}$, then $$f_{VU}(x)=0\notin\{1\}=\overline{f_{VU}(X\setminus W)}$$

>[!example]+ 
>
***
#### Keywords
- [[Normal space]],
- [[Second axiom of countability]],
- [[Hausdorff space]],
- [[Metrizable space]],
- [[Embedding of topological spaces]],
- [[Hilbert's cube]],
- [[Cardinality of a set]],
- [[Continuous mapping]],
- [[Interval]],
- [[Topology basis]],
- [[Set]],
- [[Function(mapping)]],
- [[Open and closed subsets]],
- [[Regular and T3 space]],
- [[Closure of a set]]
#### Possibly related
- 
***
#### Sources: