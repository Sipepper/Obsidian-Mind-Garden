---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Every vector from TVS can be scaled down to fit into a neighborhood of zero
***
###### tags: #Topology #Algebra/Linear 
***
>[!dsn]+ Proposition
>Let $U$ be a topological vector space and $\mathcal{V}$ a neighborhood of zero in $U$.  Given $u\in U$, there exists $r\in\mathbb{R}^{+}$ such that $\beta u\in\mathcal{V}$, $\forall\beta$ such that $|\beta|<r$.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page= 26|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.8]]]

>[!proof]+
>Observe that $u+\mathcal{V}$ is a neighborhood of $1\cdot u$, and then by the continuity of scalar multiplication, there exists $\mathcal{W}$ neighborhood of $u$ and $r>0$ such that
>$$\beta\mathcal{W}\subset u+\mathcal{V},\forall\beta:|\beta-1|<r$$
>so that
>$$\beta u\in u+\mathcal{V}$$
>or
>$$(\beta-1)u\in\mathcal{V},\;\text{where}\;|\beta-1|<r$$
>and thus
>$$\hat{\beta}u\in\mathcal{V},\forall\hat{\beta}:|\hat{\beta}|<r$$
>which completes the proof.

>[!example]+ 
>
***
#### Keywords
- [[Topological vector space]],
- [[Neighborhood in topological space]],
- [[Real line]],
- [[Absolute value]],
- [[Continuous mapping]]
#### Possibly related
- 
***
#### Sources: