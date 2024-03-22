---
Last time checked: 2024-02-14
Complete: false
aliases:
---
# Hausdorff measure
***
###### tags: #Measure_theory #Geometry/Fractal 
***
>[!dsn]+ Definition
>Let $F\subset\mathbb{R}^{n}$ and $s\in\mathbb{R}$. For each $\delta>0$ define
>$$\mathcal{H}_{\delta}^{s}=\inf\left\{\sum\limits_{i=1}^{\infty}|U_{i}|^{s}:\{U_{i}\} - \delta\text{-cover of }F \right\}$$
>i.e. we looking at all $\delta$ coverings and tying to minimize the sum. When $\delta$ is decreasing so do the class of all admissible coverings of $F$. Therefore infimum $\mathcal{H}_{\delta}^{s}(F)$ will increase when $\delta\to0$. 
>![[Pasted image 20220726194024.png]]
>Then the limit 
>$$\mathcal{H}^{s}(F)=\lim_{\delta\to0}\mathcal{H}_{\delta}^{s}(F)$$
>is said to be a $s$*-dimensional Hausdorff measure* of set $F$.^[[[Kenneth Falconner - Fractal geometry 2e.pdf#page=53|Kenneth Falconner - "Fractal geometry" p.28 ]]]

>[!example]+
>

#### Basic properties
>[!dsn]+ Proposition
>- $\mathcal{H}^{s}=0$
>- If $E\subset F$, then $\mathcal{H}^{s}(E)\le\mathcal{H}^{s}(F)$
>- If $\{F_{i}\}$ some countable family of sets, then
>  $$\mathcal{H}^{s}\left(\bigcup_{i=1}^{\infty}F_{i}\right)\le\sum\limits_{i=1}^{\infty}\mathcal{H}^{s}(F_{i})$$
>  .^[[[Kenneth Falconner - Fractal geometry 2e.pdf#page=53|Kenneth Falconner - "Fractal geometry" p.28 ]]]

>[!proof]+
>

#### Relation to Lebesgue measure
>[!dsn]+ Proposition
>Let $F$ be a Borel subset of $\mathbb{R}^{n}$, then
>$$\mathcal{H}^{n}(F)=c_{n}^{-1}\text{vol}^{n}(F)$$
>where $c_{n}$ is a volume of $n$-dimensional ball with diameter $1$.^[[[Kenneth Falconner - Fractal geometry 2e.pdf#page=53|Kenneth Falconner - "Fractal geometry" p.28 ]]]

>[!proof]+
>

#### Scaling property
Analogously to case when area and volume scales by "$\lambda^{2}$ and $\lambda^{3}$" respectively, for the sets with arbitrary Hausdorff measure the following is true
>[!dsn] Direct strict note
>Let $S$ be a similarity transformation of scale factor $\lambda>0$. If $F\subset\mathbb{R}^{n}$, then^[[[Kenneth Falconner - Fractal geometry 2e.pdf#page=54|Kenneth Falconner - "Fractal geometry" p.29 ]]]
>$$\mathcal{H}^{s}(S(F))=\lambda^{s}\mathcal{H}^{s}(F)$$
>![[Pasted image 20220809193537.png]]

>[!proof]+
>Let $\set{U_{i}}$ be a $\delta$-cover of $F$, then $\set{S(U_{i})}$ is a $\lambda\delta$-cover of $S(F)$ therefore
>$$\sum|S(U_{i})|^{s}=\lambda^{s}\sum|U_{i}|^{s}$$
>and thus
>$$\mathcal{H}_{\lambda\delta}^{s}(S(F))\le\lambda^{s}\mathcal{H}_{\delta}^{s}(F)$$
>by taking infimum. Letting $\delta\to0$ we obtain that $\mathcal{H}^{s}(S(F))\le\lambda^{s}\mathcal{H}^{s}(F)$. Replacing $S$ by $S^{-1}$ and $\lambda$ by $1/\lambda$, we obtain the opposite inequality as required.
***
#### Keywords
- [[Euclidean space]],
- [[Real line]],
- [[Supremum and infinum]],
- [[Delta covering]],
- [[Set diameter]],
- [[Limit]]
- [[Measure]],
- [[Set]],
- [[Monotonicity]],
- [[Cardinality of a set]],
- [[Borel set]],
- [[Open ball in metric space]],
- [[Dimension]],
- [[Similarity transformation]],
- [[Lebesgue measure]]
#### Possibly related
- 
***
#### Sources: