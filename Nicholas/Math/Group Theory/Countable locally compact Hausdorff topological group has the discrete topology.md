# Countable locally compact Hausdorff topological group has the discrete topology
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $G$ be any countable locally compact Hausdorff topological group. Then $G$ has the discrete topology.^[Sidney A. Morris - "Topology without tears" p. 534]

>[!proof]+
>[[Souslin space]]
>
>every point of $X$ has a local base of closed compact neighbourhoods.
>Suppose that $f:G\to D$ is an arbitrary continuous mapping from $G$ to a countable discrete space. Consider an open neighborhood of $\{e\}$. As $G$ is locally compact there exists a neighborhood basis at $\{e\}$ which consists of compact sets. 
>Consider a sequence of compact sets
>$$U_{1}\supseteq U_{2}\supseteq\dots\supseteq U_{k}\supseteq\dots\supseteq\{e\}$$
>As [[restriction of continuous mapping of a subspace is continuous]] and [[Continuous image of compact space is compact]] every image $f(U_{k})$ is compact in $D$, and furthermore
>$$f(U_{k})\supseteq f(U_{k+1})\supseteq\dots\supseteq f(\{e\})$$
>but as subset of discrete space is compact if and only if it's finite. Therefore $f(\{e\})$ is finite.
>Suppose that $f(\{e\})$ has at least two elements $\{0,1\}$ (as $D$ is countable we can choose $0$ and $1$ without loss of generality). Then consider a preimage
>$$f^{-1}(\{0\})$$
>It's a clopen compact(as $G$ is Hausdorff) subset of $G$. Let $x\in f^{-1}(\{0\})$, then as $G$ is locallly compact there exists a neighborhoods basis which consists of compact subsets. Then consider the construction defined before
>$$f^{-1}(\{0\})\supseteq V_{2}\supseteq V_{3}\supseteq\dots\supseteq V_{l}\supseteq\dots\supseteq\{x\}$$
>As $G$ is Hausdorff, exists a number $N$ such that $U_{k}\cap V_{l}=\emptyset$, thus
>$$f(\{x\})=\{0\}\qquad f(\{e\})=\{1\}$$
>As $G$ is a topological group(thus homogeneous space) such argument is valid for every element $g\in G$.
>Therefore we obtained a continuous bijection between $G$ and $D$. Then $\{e\}$ is open as a preimage of open set. Thus $G$ is discrete. 

>[!proof]+
>Let $G$ be any countable locally compact Hausdorff topological group. Then exists a compact neighbourhood $U_{e}$ of $\{e\}$. If we prove that $U_{e}$ is finite, then $G$ will have discrete topology. Suppose that $U_{e}$ is infinite, then as [[Topological group translations are homeomorphisms]] and [[Continuous image of compact space is compact]] $U_{g}:=gU_{e}$ is a compact neighborhood of $g$, for any $g\in G$. As $G$ is Hausdorff and locally-compact there exists a neighborhood basis $\mathcal{V}_{g}$ for each $g\in G$ which consists of relatively compact sets, and there exists $V_{g}\in\mathcal{V}_{g}$ and $V_{h}\in\mathcal{V}_{h}$ such that $V_{g}\cap V_{h}=\emptyset$.
>Therefore there exists a two countable 

>Metrisability -> metric space -> 


>[!example]+ 
>
***
#### Keywords
- 
#### Possibly related
- 
***
#### Sources: